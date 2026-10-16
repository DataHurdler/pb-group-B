# Lab 04 — Meeting Notes to Actions

Status: draft
Module: 04 · Time: 45 min (30 + 15) · Objective(s): LO4 · Work: pairs

## Goal

Run a recurring task as a chain of short prompts, then save the chain as a
template another pair can use cold.

## You'll need

- The approved AI tool
- [The prompt library](../handouts/prompt-library.md), for reference

## Source (fabricated for training, unclassified)

> notes — awards ceremony planning mtg 9 Oct
> present: admin chief, protocol, PA rep, facilities, budget analyst
> - venue: auditorium, 14 Mar afternoon?? protocol to confirm by 17 Oct
> - budget analyst: about $2,300 left in the morale fund, needs final
>   estimate by 31 Oct
> - PA wants photos, need photo release forms… admin maybe?
> - facilities: chairs for 200, AV check the week before
> - someone raised family parking, nobody took it
> - invitation list draft due 1 Nov from admin
> - next mtg 23 Oct 1000

## Part A — Step 1: extract (15 min)

Prompt the AI to turn the notes into a table: **Action | Owner | Due | Status**.
Include these instructions:

- Use only the notes.
- Where the owner or date is unclear, write `UNASSIGNED` or `TBD`. Don't guess.

**Check the table before going on.** Count the actions in the notes yourself.
Does the table have them all? Did it invent an owner?

## Part B — Steps 2 and 3: draft (15 min)

1. In the same conversation: *"Using only this table, draft a follow-up email
   to the attendees, ≤150 words. BLUF first: the items with no owner.
   Then the table."*
2. Then: *"Write a one-line entry for the weekly status report."*

## Part C — Templatize and swap (15 min, after the teaching block)

1. Rewrite your three prompts as one template, replacing the specifics with
   `[SLOTS]`: `[MEETING NOTES]`, `[ATTENDEES]`, `[NEXT MEETING]`, and so on.
2. Swap templates with another pair. Run theirs on the source above **without
   asking them anything**.
3. Write down every question you wanted to ask them. Give the list back to
   that pair, and they add the answers to their template.

## Done when

- [ ] The action table has all actions, with no invented owners
- [ ] A follow-up email and a status line are drafted from the table
- [ ] A template that another pair ran without asking you anything, or one you've revised after the swap

## Stretch

Add a fourth step to the chain: *"List any risks to the 14 Mar date implied
by these notes."* Is everything it lists actually in the notes?

## Instructor: answer key and pitfalls

The notes contain **7 actions**. Three have no firm owner: the final cost
estimate, photo releases (admin is only tentative), and family parking.

| Action | Owner | Due |
| --- | --- | --- |
| Confirm auditorium for 14 Mar afternoon | Protocol | 17 Oct |
| Final cost estimate to the budget analyst | TBD | 31 Oct |
| Photo release forms | UNASSIGNED (admin tentative) | TBD |
| Chairs for 200 | Facilities | TBD |
| AV check | Facilities | Week before the event |
| Family parking | UNASSIGNED | TBD |
| Invitation list draft | Admin | 1 Nov |

The next meeting (23 Oct, 1000) is a date, not an action.

**Pitfalls:** the AI assigns photo releases firmly to admin, or assigns
parking to facilities. Those are invented owners, which is the exact failure
step 1 must catch. That's the argument for checking between steps.
