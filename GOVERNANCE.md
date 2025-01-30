# Governance

> [!NOTE]
> This is a working draft, although we'll intend to migrate this to the wiki in the future.

This document outlines the governance model for Recap Time Squad. This includes
detailed descriptions of different roles, nomination processes, code review processes,
and Code of Conduct enforcement. Note that since we maintain our team handbook
publicly as part of the Squad Wiki, we'll usually link to the handbook instead of duplicating it here.

👉 **All community members must follow the [Code of Conduct (CoC)](CODE_OF_CONDUCT.md).**
Consequences for CoC violations are detailed in [Moderation](#moderation).

👉 **Want to trigger a vote, nomination, or perform some other action?**
Scroll down to [Playbook](#governance-playbook).

ℹ️ **This documentation will be always work in progress.** While Recap Time Squad
is currently running as a one-man operation by @ajhalili2006, we hope that by
building the community and recuriting enough community maintainers (and even promote some
of them as team members) we can ensure the future sustainability of our open source projects,
as well as the organization as a whole.

## Get Involved

**Anything that supports the Recap Time Squad and its community is a valuable contribution!**

All types of contribution are meaningful. This can include code changes, type fixes,
Zulip activity, and even posting about Recap Time Squad to your personal blog.
No contribution is too small!

Anyone can become an community contributor (yes, even you!). Engineering ability is not required.
Our goal is to recognize all contributors to the project regardless of skill, experience or background.

## Contributor Levels

We recognize different levels of contribution as four different **Contributor Levels.**
Because each level comes with a new set of privileges and responsibilities, you may also
see these levels referred to as **Contributor Roles**.
balance
Contributor levels are available to **all members** of the Recap Time Squad community, regardless
of coding skill or experience.

Two important things that we look for in a contributor are:

- **Being here** - Everyone's time is valuable, and the fact that you're here and contributing
to Recap Time Squad is amazing! Thank you for being a part of this project with us.
- **Being a positive member of our community** - Go above and beyond our [Code of Conduct](CODE_OF_CONDUCT.md)
and commit to healthy communication across merge requests/email patches, issue discussions, Zulip threads, and any interactions outside of our community (ex: no Twitter bullies allowed :)

All Contributor roles are granted for as long as the individual wishes to engage with the project.

Contributors can voluntarily leave the project at any time. See [Retiring a Role](#retiring-a-role-and-alumni-status) below for more information.

In extreme cases -- such as a Code of Conduct violation -- a role may be revoked by a project Steward at their discretion.

Each new Contributor level unlocks new privileges and responsibilities both on Discord and on GitHub. Below is a summary of each level.

### Level 1 - Contributor

Have you done something (big or small) to contribute to the health, success, or growth of Recap Time Squad?
**Congratulations, you're officially recognized as a contributor to our team!**

#### Examples of recognized contributions

* **GitHub/GitLab/sourcehut**: Submitting an accepted merge request/email patch
* Filing a detailed bug report or RFC
* Updating documentation or fixing a typo.
* Answering community questions on `<insert platform here>`
* Blogging, Vlogging, Podcasting, and Livestreaming about Recap Time Squad
* This list is incomplete! Similar contributions are also recognized.

#### Privileges

* Developer level access to most open-source projects run/maintained under Recap Time Squad (managed via `@recaptime-dev/contributors`
subgroup or team)
* Addition to the `recaptime-dev/contributors` user group in Zulip
* Invitations to contributor-only events, sticker drops, and the occasional swag drop.

#### Responsibilities

This role does not require any extra responsibilities nor time commitment. We hope you stick around and keep participating in our community!

If you're interested in reaching the next level and becoming a **Maintainer**, you can explore some of those responsibilities in the
[next section](#level-2---community-maintainer).

### Level 2 - Community Maintainer

The **Maintainer** role is available to contributors who want to join the team and take part in the long-term maintenance and growth of
Recap Time Squad's open-source projects. (In similar note, squad members are automatically considered as community maintainers, even through
some of them might be working part-time.)

**Maintainers are not required to write code!** Some Maintainers spend most of their time inside of Zulip/Matrix, maintaining a healthy community there.
Others work on technical documentation, support, or design.

**A Maintainer has moderation privileges!** All maintainers are trusted with the ability to help moderate our Zulip, Matrix and GitHub communities for things like spam.
There is also a special (optional, opt-in) `@mods` role open to maintainers who are also interested in helping out when a community member reaches out for moderation help.
Maintainers can also join our Trust and Safety team to help moderate our fediverse and Matrix instances (in the future) to be in compliance against myriad of
international laws, particularly on intellectual property and CSAM (Child Sexual Abuse Material).

#### Nomination

- To be nominated, a nominee is expected to already be performing some of the responsibilities of a Maintainer.
- You can be nominated by any existing Maintainer (L2 or above).
- Once nominated, there will be a vote by existing Maintainers.
- Access to their own `@community.recaptime.dev` email address

### Level 3 - Squad Members

Squad members (as part of the team roaster or under community capacity) as we call it, or sometimes referred to the core team,
is community members who have a larger-than-usual impact on Recap Time Squad and the wider community. They are seen as leaders in the project and are
listened to by the wider community, often before they have even reached this level. A squad member is recognized for contributing a significant
amount of time and energy to the project through issues, pull requests, bug fixes, implementing advanced enhancements/features, and/or actively posting
on Zulip/Matrix.

Not every contributor will reach this level, and that's okay! Community Maintainers still have significant responsibility and privileges within our community.

#### Privileges

- All privileges of the [Maintainer role](#level-2---community-maintainer), plus...
- `@recaptime-dev/squad` role on [Discord](https://astro.build/chat)
- Invitation to the private `#staff/*` channels on Zulip.
- Invitation to the `squad` team on GitHub (and `@recaptime-dev/squad` on GitLab).
- Ability to vote on most initiatives (see [Voting](#voting) below).
- Access to their own `@crew.recaptime.dev` email address

#### Responsibilities

- All of the responsibilities of L2, including...
- Ownership over specific part(s) of the organization (also known as getting assigned to specific teams and projects)
- Ownership over the long-term health and success of Recap Time Squad.
- Leadership as a role-model to other maintainers and community members.

### Level 4 - Squad Leads

The **Squad Leads** is an additional role bestowed to 1 (or more) Core member of the project.
Sometimes called as
Project Leadership Committee or just simply put leadership team/council. Under the squad handbook,
squad leads are usually consisting of leaders and representatives from different projects under
Recap Time Squad.

The role of Squad Lead is mainly an administrative one. Stewards control and
maintain sensitive information (including API keys and secrets), considered as Project Liaisons
between the organization and our fiscal host (in this case, [Hack Club](https://hackclub.com/hcb))
and act as tiebreakers in the event of disagreements.

In extremely rare cases, a Steward can act unilaterally when they believe it is in the project's best
interest and can prove that the issue cannot be resolved through normal governance procedure.
The steward must publicly state their reason for unilateral action before taking it.

Our SABDFL, @ajhalili2006, will serve both as Squad Lead and Primary Project Liaison for our fiscal host.

#### Responsibilities

- Access to the [@RecapTimeSquad@mastodon.xyz on fediverse](https://mastodon.xyz/@RecapTimeSquad)
and [@recaptime.dev on Bluesky Social](https://bsky.app/profile/recaptime.dev), among other socials
- Administration privileges on the [recaptime-dev GitHub org](https://github.com/recaptime-dev) and affliated projects
- Administration privileges on the [recaptime-dev Zulip Cloud org](https://recaptime-dev.zulipchat.com)
- Domain registrar and DNS access to `recaptime.dev` and related domains via Cloudflare and friends
- Administration access to the `recaptime-dev` Vercel + Netlify + Cloudflare accounts/orgs
- Ability to initiate a [vote](GOVERNANCE.md#voting)
- Ability to veto [votes](GOVERNANCE.md#voting) and resolve voting deadlocks
- Define org direction and planning, and to assist in E2C (Exit to Community)
- Ability to decide on moderation decisions
- Admin access to the `*@crew.recaptime.dev` email addresses (although they don't read your personal inbox w/o permission)
- As Project Liaisons for HCB:
  - Review reimbursement requests from team and community members
  - Be contract signee with the HCB team for the fiscal sponsorship agreement

#### Nomination

- Stewards cannot be self-nominated.
- Only Core members are eligible, although community maintainers wishing to join the
leadership council will need to be promoted to regular squad member first and wait for 60 days
from day of confirmation.
- New Stewards will be added based on a unanimous vote by the existing Steward(s).
- In the event that someone is unreachable then the decision will be deferred.

## Other roles

We document other roles in the organization that worth mentioning in the pursuit
of radical transparency and to assist in transition to community-based governance from
BDFL-styled one.

### Staff members

Readers from Astro's governance documentation might be surprised why we're treating L3 as staff,
even through most of the team are volunteers. Some of us (including @ajhalili2006) are working
full-time here while juggling with other things outside open-source, so its a complicated mess
regarding how to do salary thing (so we opted out of that for now).

### Hack Club staff

Hack Clubbers affiliated with the HQ in official capacity, including those working for HCB,
its fiscal sponsorship program, are technically considered as honorary team members
under [L2 Community Maintainer](#level-2---community-maintainer) role.

## Governance Playbook

Our governance playbook is hosted as part of our [Squad Handbook] in the wiki and in
the [`@recaptime-dev/squad` GitLab subgroup readme under the `cookbooks` folder](https://mau.dev/recaptime-dev/squad/gitlab-profile/tree/main/cookbooks)
([github mirror](https://github.com/recaptime-dev/squad/tree/main/cookbooks)).

[Squad Handbook]: https://wiki.recaptime.dev/handbook

---

## Credits

This goverance documentation is adopted from [Astro's governance docs](https://github.com/withastro/.github/blob/main/GOVERNANCE.md),
with additional reference from [Rust programming language](https://www.rust-lang.org/governance) and [Homebrew](https://docs.brew.sh/Homebrew-Governance)
governance documents.

We also adopted some language from Arch Linux
