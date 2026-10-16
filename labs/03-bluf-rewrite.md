# Lab 03 — The BLUF Rewrite

Status: draft
Module: 03 · Time: 30 min · Objective(s): LO3 · Work: pairs

## Goal

Turn a long, wordy memo into a BLUF email that a Chief of Staff could act on
in under a minute, then edit it until you'd sign it.

## You'll need

- The approved AI tool
- [The executive-writing card](../handouts/executive-writing-card.md)

## Source (fabricated for training, unclassified)

> **MEMORANDUM FOR Chief of Staff, Directorate of Support Services**
> **SUBJECT: Update on Building 12 HVAC Replacement Project**
>
> 1. This memorandum provides an update regarding the status of the Building
> 12 heating, ventilation, and air conditioning (HVAC) replacement project,
> which has been the subject of ongoing coordination between the Facilities
> Branch and the contractor over the past several weeks.
>
> 2. As you may recall, the project was originally scheduled to begin on
> 4 August and conclude on 29 August. However, owing to a supplier delay
> affecting delivery of the rooftop units, the contractor has informed
> Facilities that the start date will now move to 15 September, with
> completion projected for 10 October. Facilities has reviewed the revised
> schedule and assesses it as realistic, though further supplier delays
> cannot be ruled out.
>
> 3. During the work, floors 2 and 3 will each be without air conditioning
> for approximately two weeks, on a staggered basis. Approximately 140
> personnel work on these floors. Given forecast temperatures in late
> September, Facilities assesses that working conditions on the affected
> floors would be uncomfortable without mitigation.
>
> 4. Facilities has identified three possible courses of action: (a)
> temporarily relocate affected personnel to Building 7, which currently has
> 90 available desks; (b) authorize expanded telework for affected personnel
> during their floor's outage; or (c) rent portable cooling units, at an
> estimated cost of $18,500. Facilities recommends a combination of (a) and
> (b), since Building 7 cannot accommodate all affected personnel.
>
> 5. In order to reserve the space in Building 7, a decision is requested no
> later than 22 August. The point of contact for this matter is the Facilities
> Branch.

## Steps

### Part A — First draft (10 min)

Write one prompt using all six slots. At minimum it should:

- paste the source and say *use only these facts*
- name the reader (Chief of Staff) and what they need (a decision)
- set the format: *BLUF email, ≤120 words, subject line, first sentence states
  the decision needed and the deadline*

Save the output.

### Part B — Edit until you'd sign it (12 min)

Check the draft against the executive checklist. Fix problems **by changing
the prompt first**. Edit by hand only for the final polish.

- [ ] First sentence states the decision and the date (22 Aug)
- [ ] Recommendation stated: Building 7 relocation plus telework
- [ ] Every number matches the source: 140 personnel, 90 desks, $18,500, 15 Sep–10 Oct
- [ ] ≤120 words
- [ ] Nothing added that isn't in the source

### Part C — Same facts, different product (8 min)

Ask for a **one-page information paper** instead, with the sections Purpose,
Bottom line, Key facts (≤5 bullets), and Way ahead. What did you have to
change in the prompt besides the format?

## Done when

- [ ] A BLUF email that passes every checklist item
- [ ] A note of at least one fix made by changing the prompt

## Stretch

Write the version for a reader who has only 10 seconds: two sentences.

## Debrief questions

- What did you change after the AI was done, and why couldn't the prompt do it?
- Did the AI soften the deadline or the ask? How did you stop it?

## Instructor: answer key and pitfalls

A passing email, about 90 words:

> **Subject:** DECISION NEEDED by 22 Aug: Bldg 12 HVAC outage, staff relocation
>
> Chief of Staff, request your decision by **22 Aug** to relocate Bldg 12
> floor 2–3 staff to Bldg 7 and authorize expanded telework during the HVAC
> outage.
>
> - Supplier delay moves the work to **15 Sep–10 Oct**.
> - Floors 2 and 3 each lose A/C for about 2 weeks, staggered. That's about 140 people.
> - Bldg 7 has 90 desks, so telework covers the rest. Portable cooling is the
>   alternative, at about $18,500.
>
> Further supplier delay is possible. POC: Facilities Branch.

**Pitfalls:** the AI opens with "This email provides an update…", which isn't
BLUF. It also drops "further delays possible", which is a lost caveat (see
Module 05).
