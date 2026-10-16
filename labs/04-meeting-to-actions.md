# Lab 04 — Meeting Notes to Actions

Status: draft
Module: 04 · Time: 45 min (30 + 15) · Objective: LO5 · Work: individual

## Goal

Run a recurring task as a chain of short prompts. Then start a template for
**your own** recurring task: the one on your index card.

## You'll need

- Free ChatGPT on your laptop
- [The prompt library](../handouts/prompt-library.md), for reference
- Your index card from the welcome

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

## Part C — Version 1 of your own template (15 min, after the teaching block)

Work on the recurring task on your index card.

1. **Write a made-up sample input (4 min):** 5–10 lines that look like the
   real thing, but are invented. No real names, numbers, or content from
   work. No student, personnel, or health records.
2. **Write the template (8 min).** Start from the closest one in the prompt
   library, if any. Fill the six slots, and replace everything specific with
   `[SLOTS]`: `[READER]`, `[DEADLINE]`, `[PASTE NOTES]`, and so on. If the task
   has several steps, write one prompt per step.
3. **Run it once (3 min)** on your sample input, in a new chat. Save the
   template and the output. Module 05 tests and refines it.

## Done when

- [ ] The action table has all actions, with no invented owners
- [ ] A follow-up email and a status line are drafted from the table
- [ ] Version 1 of your own template, with `[SLOTS]`, run once on an invented sample input

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

**Part C pitfall:** learners paste real content from their task "just to
test it." Walk the room. The sample input must be invented.

**Part A–B pitfalls:** the AI assigns photo releases firmly to admin, or assigns
parking to facilities. Those are invented owners, which is the exact failure
step 1 must catch. That's the argument for checking between steps.
