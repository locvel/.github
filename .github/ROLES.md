# Locvel roles

How access works at Locvel. GitHub Free does not allow custom-named roles, so the
roles below are built from teams + GitHub's five built-in repo roles
(Read, Triage, Write, Maintain, Admin) + branch protection.

## The ladder

| Role | Team | Access | Can | Cannot |
|---|---|---|---|---|
| Owner | — (org-level, not a team) | Admin on everything | Everything: delete repos, change org settings, remove anyone, transfer the org | — |
| Maintainer | Maintainers | Maintain on all repos | Merge PRs, manage issues and PRs, manage repo settings | Delete repos, change org settings, remove the owner |
| Contributor | Contributors | Write on voite | Push branches, open PRs, review code | Merge alone, push to other repos, change settings |
| Triage | Triage | Triage on voite | Label, assign, close and reopen issues, request reviews | Push code, merge |
| Everyone else | — | None (fork + PR) | Open issues, fork, open PRs from a fork | Push to any Locvel repo |

New members start with the org default: Read on every repo, nothing more.
A team adds the higher role on top. Nobody gets a role by asking for it — the
owner adds people to teams.

## The merge gate

Merging is controlled by branch protection, not by team membership. Today the
gate is 0 required approvals, because the owner is the only person who can
review and nobody can approve their own PR.

When the first Maintainer joins, the owner flips the gate to 1 required approval
on voite, .github and locvel.github.io. From that day, no PR merges without
another person's approval. A Contributor can never merge their own PR alone.

## How to join a team

1. The owner invites you as an org member (Settings → People → Invite member).
2. The owner adds you to a team. Start as Contributor or Triage.
3. Maintainer comes after regular, good contributions over time, by owner invite.
   It is earned, not requested.
4. Owner is NOT a step on this ladder — except the single backup-owner seat. See below.

## Owner is not a promotion

Owner is equal to the founder: an Owner can delete every repo, remove any
member including the founder, and transfer the org. Someone becomes an Owner
only if the founder trusts them with the org itself — not because they
contribute a lot. Maintainer is the top contributor role. If you are reading
this as a friend of the founder: Maintainer is the role you want.

The one exception is the backup-owner seat: exactly one trusted person holds Owner purely as break-glass cover, in case the founder ever loses access to his own account. The backup owner does not run the org, does not make decisions, and does not act unless the founder asks or is unreachable. That seat is filled only by the founder, by hand, and it is never a reward for contributions.

## Changing this file

Role changes are decided by the owner and recorded here in the same PR that
makes the change. If this file and GitHub settings disagree, the settings win
and this file must be fixed.
