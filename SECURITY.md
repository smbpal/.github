# Security policy

SMBPal installs a daemon that runs as **root** and manages Samba configuration and cifs mounts on
the machine it is installed on. A defect in it is worth reporting carefully.

## Reporting a vulnerability

**Please do not open a public issue.** Use GitHub's private vulnerability reporting:

- [Report a vulnerability in smbpal-desktop](https://github.com/smbpal/smbpal-desktop/security/advisories/new)

That channel stays private between you and the maintainer until an advisory is published. There
is deliberately no email address on this page: a private form is better than an address that ends
up scraped, and it keeps the report attached to the repository it concerns.

## What to expect

This is a one person project, so the honest answer is acknowledgement within a week and no
promise faster than that. You will be told what is being done about it, and credited in any
advisory unless you would rather not be.

## Scope

- The daemon, the command line and the GUI in `smbpal-desktop`
- The Debian packaging, including the maintainer scripts that create the `smbpal` group and
  install the polkit policy
- The distribution channels: `smbpal.app` and `apt.smbpal.app`

## Supported versions

The latest release only. `v0.1.0` is the first, so there is nothing older to support yet.

## Documented behaviour, not vulnerabilities

These are design decisions with reasons, not oversights. If you think the reasoning is wrong,
that is a conversation worth having in the open as a design question rather than privately as an
advisory.

- **Membership of the `smbpal` group is access to a root daemon.** This is exactly why the
  package will not add you to the group during installation and the install instructions make it
  a separate, deliberate step. Granting it is the machine administrator's decision.
- **Shares are reachable by other machines on your network.** SMBPal never reaches the public
  internet, and it does not attempt to defend you from the other devices on your own LAN.
- **One credential per share, and no user management.** No domains, no permission trees. That is
  the intended scope, not a missing feature.
