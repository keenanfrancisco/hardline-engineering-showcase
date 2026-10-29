# Contribution record

This document records internally verified portfolio attribution while keeping the production repository private.

## Method

On October 28, 2026, GitHub's contributors endpoint reported:

- Keenan Francisco ([keenanfrancisco](https://github.com/keenanfrancisco)): 460 authored commits
- Caleb Ponce ([calebponce](https://github.com/calebponce)): 257 authored commits

The selected entries below were also checked against the private repository's local Git history for author, date, subject, and affected surfaces. Short commit identifiers are included as private-history references; they do not expose or link to the underlying source, and an outside reviewer cannot independently verify them.

Commit counts include work written with AI coding assistants (Claude Code, Codex). Those commits carry co-author lines in the private history, and GitHub separately lists 23 commits under a claude account that are not counted here. The founders chose the work, made the architecture, review, and security decisions, and approved every change before it shipped.

Counts can change after the stated date. They represent attributed commits, not lines of code, relative importance, or sole ownership of collaborative product decisions.

## Keenan Francisco

Selected authored work:

| Private reference | Date | Public-safe summary |
| --- | --- | --- |
| c60e832 | 2026-10-23 | Labeled shared records that no person has approved as unreviewed AI output |
| 3ec85e2 | 2026-10-22 | Scoped storage access to the owning scan during a pre-launch security review |
| d309478 | 2026-06-13 | Built human review and approval for utility records |
| d47ee80 | 2026-09-05 | Tightened the capture-to-return accuracy contract across backend, web, and iOS surfaces |
| c916f70 | 2026-09-06 | Prevented ground-truth measurements from being derived from a reference frame that did not share the required datum |
| 0b05bcb | 2026-09-04 | Added an independent replay baseline for adversarial evaluation |
| 55098e0 | 2026-08-14 | Added a wall-coverage gate to the capture workflow |
| da1275b | 2026-08-20 | Made silent scan and worker failures observable |
| c2a767b | 2026-08-25 | Added release checks and secret scanning |

Public-safe focus: spatial contracts, reliability, field validation, human review, security review, iOS capture, observability, and release safety.

## Caleb Ponce

Selected authored work:

| Private reference | Date | Public-safe summary |
| --- | --- | --- |
| 5a0fe4d | 2026-07-24 | Integrated an RGB-only reconstruction path with scan processing |
| 6063a74 | 2026-06-28 | Hardened authentication and request boundaries |
| 45300d0 | 2026-06-25 | Established durable room identity across the product |
| 0090e59 | 2026-06-27 | Shipped controlled public review links |
| 0cef40e | 2026-06-27 | Delivered the 2D utility-map review surface |
| 72b6c63 | 2026-06-24 | Closed ten field-facing iOS scan-flow gaps |

Public-safe focus: full-stack product delivery, reconstruction integration, security, sharing, web review, and field UX.

## What this proves—and what it does not

This record supports the claim that both founders made sustained, substantive engineering contributions to Hardline. It does not claim that every listed decision belonged to one person, that commit count measures impact, or that this showcase reproduces the private work.

For interview diligence, either founder can provide a private architecture walkthrough or screen-share relevant history without distributing the repository.
