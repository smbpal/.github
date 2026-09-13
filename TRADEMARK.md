# SMBPal trademark policy

**Version 1.0, 13 September 2026.**

SMBPal is free software under GPL-3.0-or-later. That licence gives you broad rights over the
**code**. It does not give you rights over the **name**, and this page explains the difference
and where the line sits.

## What is claimed

The name **SMBPal**, the SMBPal wordmark, and the SMBPal logo when one exists. Used publicly
since 18 August 2026. Unregistered, so `SMBPal (TM)` rather than a registered mark.

**Not claimed: the three status icons** in `packaging/icons/` in `smbpal-desktop`. Those were
published under GPL-3.0-or-later with the rest of that repository, publication is one way, and
they are three abstract glyphs rather than a mark. They are GPL and they stay GPL. Anyone may use
and modify them, a fork included.

## Why a free software project reserves a name at all

Not to restrict the software. The reason is that a user who installs something called SMBPal
should be able to tell whose software it is. SMBPal runs a daemon as root on the machine it is
installed on, so "who built this and who do I report a problem to" is a security question and not
a branding one. A fork is free to exist, free to be better, and free to be distributed. It should
not be mistakable for this one.

GPL-3.0 anticipates exactly this. Section 7(e) permits a supplementary term "declining to grant
rights under trademark law for use of some trade names, trademarks, or service marks". This
policy is that term. It restricts nothing about the code, and the software remains free software
under the GPL with or without it.

## What you may do, with no permission needed

- **Say what your software does.** "Works with SMBPal", "compatible with SMBPal", "an alternative
  to SMBPal", "imports SMBPal configuration". Using the name to refer accurately to this project
  is fair and is not something this policy touches.
- **Write about it.** Articles, reviews, tutorials, videos, conference talks, criticism. Use the
  name and the logo as needed to refer to the project.
- **Redistribute the official packages unmodified**, under the name, including mirroring them.
- **Fork the code and modify it.** The GPL guarantees this and nothing here qualifies it. Give
  the result its own name.
- **Use the status icons for anything.** They are GPL, as above.

## What needs a different name

- **Distributing a modified version of SMBPal under the name SMBPal**, where the modifications go
  beyond the packaging cases below.
- **Naming your own product, service, domain, app store listing or organisation** SMBPal, or
  something close enough to be confused with it.
- **Implying endorsement**, affiliation, or that a modified version is the official one.

## Distributors and packagers

**You may distribute SMBPal under its own name with the patches that packaging normally
requires**, and you do not need to ask. That means build fixes, backports, dependency and path
adjustments, security patches, and changes made to satisfy a distribution's own policies. This
permission is deliberate and it is here because the alternative has been tried: a project that
forces a rename over ordinary downstream patching ends up with its software shipped under a name
nobody recognises, which serves nobody.

What is outside it is changing what the software does or how it behaves and keeping the name. If
you are unsure which side of the line a patch falls on, ask, and the answer will almost certainly
be yes.

## Asking

Open an issue on [smbpal-desktop](https://github.com/smbpal/smbpal-desktop/issues) describing what
you want to do. Permission for anything reasonable is likely and free.

## If this policy and the GPL ever appear to conflict

The GPL wins as to the code. This policy governs only the name and the marks, and nothing in it
is intended to add a restriction on copying, modifying or distributing the software. If any part
of it reads as though it does, that part does not apply.
