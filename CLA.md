# SMBPal Contributor Licence Agreement

**Version 1.0, 13 September 2026.**

## Why this exists, in plain terms

This summary is here to be read. It is not part of the agreement, and where the two differ the
agreement below is what counts.

SMBPal is GPL-3.0-or-later and stays that way. Apple's App Store terms and the GPL are in
long-standing conflict, and GPL applications have been removed from the store over it. The only
route to an iOS build is dual licensing: the GPL for this project, a separate proprietary grant
for an App Store build, the same code under two grants. **Dual licensing is only available where
one party can licence the whole work.** A single merged contribution whose copyright sits
somewhere else ends the possibility of an iOS build, for everyone, permanently.

So this agreement asks you to licence your contribution broadly enough that the dual licence
stays possible. Three things it does not do, which are as much the point as what it does:

- **You keep your copyright.** This is a licence, not an assignment. Your contribution is still
  yours and you may use it anywhere else, under any terms you like.
- **Your contribution stays free software here.** Clause 4 is a promise in your favour and it is
  the reason the rest is reasonable: what you contribute remains available under
  GPL-3.0-or-later in the public repository, permanently. That is not something this agreement
  lets anyone take back.
- **It does not ask you to vouch for anything you cannot know.** The warranties in clause 6 are
  about whether the work is yours to give.

If you would rather not sign, an issue describing the bug or the design is genuinely as useful,
and often more so.

## The agreement

### 1. Definitions

**"The Project"** means SMBPal, in any repository owned by the `smbpal` organisation on GitHub.

**"The Maintainer"** means the owner of the SMBPal copyright in this project, and any successor
to whom that ownership passes as a whole.

**"You"** means the person or legal entity agreeing to this document.

**"Contribution"** means any work of authorship you intentionally submit to the Project for
inclusion, in any form and by any means, including code, documentation, configuration and
artwork. Submission includes opening a pull request and posting a patch in an issue. It does not
include anything you clearly mark, at the time of submission, as not being a Contribution.

### 2. Copyright licence

You grant the Maintainer a perpetual, worldwide, non-exclusive, royalty-free, irrevocable licence
to reproduce, prepare derivative works of, publicly display, publicly perform, sublicense and
distribute your Contribution and derivative works of it.

**That licence includes the right to sublicense the Contribution under any terms, including terms
that are not free software terms, and to combine it with other works and distribute the result
under any terms.** This is the clause that makes an App Store build possible and it is the reason
this agreement exists. It is subject to clause 4.

You retain all right, title and interest in your Contribution. Nothing here assigns your
copyright or limits what you may do with your own work elsewhere.

### 3. Patent licence

You grant the Maintainer and every recipient of the Project a perpetual, worldwide,
non-exclusive, royalty-free, irrevocable licence under any patent claims you own or control that
are necessarily infringed by your Contribution alone or by its combination with the Project, to
make, have made, use, offer to sell, sell, import and otherwise transfer the Project.

If you institute patent litigation against any entity alleging that the Project or a Contribution
within it constitutes patent infringement, any patent licence granted by you under this clause
terminates as of the date that litigation is filed.

### 4. What the Maintainer promises in return

This clause binds the Maintainer and is not revocable by later versions of this agreement.

Every Contribution accepted into the Project will be made available under **GPL-3.0-or-later** in
a public repository, and will remain so available. Relicensing under clause 2 is additional to
that, never instead of it. The Maintainer may not withdraw a Contribution from the GPL, and may
not make a future version of this agreement apply retroactively to a Contribution already
submitted under this one.

If the Project is discontinued, this clause survives.

### 5. Third-party material

If your Contribution includes work that is not yours, or that carries licence terms of its own,
you must identify it clearly at the time of submission, including its source and its licence, and
you must not submit it as your own work.

Material under the GPL cannot be accepted into the Project even though the Project is itself
GPL-licensed, because incorporating it removes the relicensing ability described in clause 2.
The Project uses GPL software as separate processes, which is a different thing and is unaffected.

### 6. What you are stating

You represent that:

- each Contribution is your original work, or is material you have identified under clause 5;
- you are legally entitled to grant the licences above;
- if your employer has rights to work you create, you have permission to make the Contribution on
  their behalf, or your employer has waived those rights for the Contribution, or your employer
  has agreed to this document; and
- you are not aware of any claim, lien or agreement that conflicts with these grants.

You are not asked to represent that your Contribution is free of defects, does not infringe any
patent you are unaware of, or is fit for any purpose.

### 7. No warranty, and no obligation

Your Contribution is provided **as is**, without warranty of any kind, express or implied, except
for the representations you make in clause 6.

Nothing obliges the Maintainer to use, merge, or continue to distribute any Contribution.

### 8. Governing law

This agreement is governed by the law of England and Wales, and the courts of England and Wales
have exclusive jurisdiction over any dispute arising from it.

To the extent permitted by law, you agree not to assert moral rights in your Contribution against
the Maintainer or against anyone receiving the Project, insofar as doing so would prevent the
Contribution being modified, combined with other work, or distributed under clause 2. Where those
rights cannot be waived, you agree not to enforce them for those purposes.

If any provision of this agreement is held unenforceable, the rest continues in force.

## How to sign

There is no bot. This project has one maintainer and no contributors yet, and a manual process is
honest at that size.

In the description of your first pull request, include this line, with your own name and the date:

```
I have read and agree to the SMBPal Contributor Licence Agreement, version 1.0.
Signed: <your name>, <date>
```

If you are contributing on behalf of an employer, say so on the same line and name them.

Your name and the date will be recorded in `CONTRIBUTORS.md` in this repository when the pull
request is merged, so that what was agreed and when is a matter of public record rather than
something buried in a thread.
