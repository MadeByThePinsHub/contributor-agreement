# Contributor Agreement

This repoistory contains our CLAs based on Harmony CLA and the combined CLA containing our Individual CLA + Linux DCO. 

## Signing to the agreement

There are two versions of this Contributor Agreement, one for [individuals who contributing to our projects without any corporate affliation][individual]
and one for [corporate contributions][corporate]. Please take some time to read them all before filing an new issue.

[individual]: meta/CLA-Individual-v1.md
[corporate]: meta/CLA-Entity-v1.md

Once you're fully read them, please file a new issue [using this link][cla-individual-sign] for individuals or [this one][cla-entity-sign] for entities. Once filed an new issue, our robots will greet you with any additional instructions if needed.

[cla-individual-sign]: https://signoff.rtapp.tk/contributor-agreement/sign-individual
[cla-entity-sign]: https://signoff.rtapp.tk/contributor-agreement/sign-entity

### The Process

By default, [our service account](https://github.com/RecapTimeBot) will prompt first-time contributors to [read both the Linux DCO and our Individual CLA](meta/ThePinsTeam-CLA-DCO-v1.md) and optionally prompt the user to rebase their commits with `--signoff` flag.

For CI stuff, this is enforced by the [DCO GitHub App](https://github.com/apps/dco).


## FAQs

### Do you have any previous CLAs before this?

None. Period.

### Why the fuck you have an CLA? It just legalese bullshit.

TL;DR: You don't need to sign the CLA. Our robots will ask nicely if you agree to the Linux DCO and if you optionally want to rebase your commits with `Signed-off-by` attached on the commit message body.

We know you hate legal text, and we do too. These CLAs reinforces your commit sign-offs (aka your compliance with [DCO](https://developercertificate.org/))
and your commitment to an vibrant and inclusive community (aka your agreement to [Community Code of Conduct](https://github.com/MadeByThePinsHub/policies/blob/master/CODE_OF_CONDUCT.md)). If you don't want to sign-off your work (perhaps you do GPG signing on commits) or just want to cerfity you have the rights to submit your contributions as part of our projects' lifetime, we recommend to sign the CLA.

We remind you again that **signing CLA for our projects is recommended, but optional.** You **MUST** and still follow our code of conduct and contributing guidelines.

### What if I don't signed the CLA?

Without signing the CLA, you're required to:
   * sign-off your commits with `--signoff` (`-s` for shortcut), in case of using Commitizen in some of our projects, please rebase your latest commit with `git rebase HEAD --signoff`.

Even you are signed the CLA, you should and must do these:
   * read our contributing guidelines in each project's `CONTRIBUTING.md` file
   * **(optionally, but recommended)** sign your commits with GPG as your signature that you have the rights to submit your work and to prevent impersonation on commits.

### Do this CLA allows The Pins Team to transfer copyright assignment from contributors like me?

Not really. We chose not to have an copyright assignment agreement (CAA) while we crafting our own CA. If we ever want to change the project's license, we may ask contributors if they want to and if majority wants it, we may change the license slowly.

But what if they don't or didn't reach the required number? Well,
multi-licensing is the key, but sometimes it's chaos.

### Do you have PDFs for these?

Not yet, but we're working on improving them and we'll publish these forms in the distant future. In an meanwhile, please file an new issue using the **Sign the CLA** template.

### I'm an GitLab SaaS (GitLab.com) user and I don't GitHub anymore. How do I sign the CLA?

We're working on making signing the CLA for GitLab SaaS users easy and also automated as their GitHub counterpart.

### I have more questions. Where I can ask?

* The [Discussions tab](https://github.com/MadeByThePinsHub/contributor-agreement/discussions), on its repo's GitHub counterpart
* [In the Community Forums](https://community.madebythepins.tk), under `Community Lounge` category and `CLA and DCO stuff` as subcategory.
* Probably ask us directly, just using [our contact details provided on our website](https://madebythepins.tk/contact).

**Remember that we're not an law firm nor we don't have any experience in practicing any law. We're just regular open-source maintainers and contributors like you.**
