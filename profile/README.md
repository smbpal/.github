## SMBPal

Share a folder from one machine and open it on another. SMB is the protocol every operating
system already knows how to open, so nothing on the other end needs SMBPal installed.

**[smbpal.app](https://smbpal.app)** has the install instructions.

### Where it runs today

**Linux only.** `v0.1.0` ships as a `.deb` and is tested on Raspberry Pi OS Trixie, on a
Raspberry Pi 4. Nothing else has been run in anger, though one file installs on arm64, armhf and
amd64. Apps for macOS, Windows, Android and iOS are intended and do not exist yet.

Built first for the Raspberry Pi desktop user, for whom Pi OS ships no SMB GUI at all. There is a
command line for the far more common case of a Pi with no screen attached.

Deliberately small. A file sharing utility asks for admin rights and stores credentials, so it
should look like it does one thing competently rather than like a 200 MB installer.

### Repositories

- **[smbpal-desktop](https://github.com/smbpal/smbpal-desktop)** is the GUI, daemon and command
  line, shipped as one package so the client and the daemon cannot drift apart.
  `GPL-3.0-or-later`.

The website and the Phase 0 toolkit spikes are in private repositories.

### Security

SMBPal installs a daemon that runs as root. Please report vulnerabilities privately rather than
in a public issue: see [SECURITY.md](https://github.com/smbpal/.github/blob/main/SECURITY.md).
