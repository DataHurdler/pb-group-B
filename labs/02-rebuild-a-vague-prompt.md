# Lab 02 — Rebuild a Vague Prompt

Status: draft
Module: 02 · Time: 35 min · Objective: LO2 · Work: individual

## Goal

Take a vague prompt to a six-slot prompt one slot at a time, and see which
slot changes the output most.

## You'll need

- Free ChatGPT on your laptop
- [The six-slots card](../handouts/six-slots-card.md)

## Source (fabricated for training, unclassified)

> **Telework update, Directorate of Support Services.** Effective 1 November,
> core hours are 0900–1500. Eligible employees may telework up to 2 days per
> week with supervisor approval. New and updated telework agreements are due
> to supervisors by 25 October. Employees with an existing agreement must
> re-sign it by the same date. Questions go to the directorate HR office.

## Steps

1. **Baseline (3 min).** New conversation:
   > Write an email about the new telework policy.

   Save the output as **v0**.
2. **Add one slot at a time (20 min).** For each step, start a new
   conversation, add one slot to the previous prompt, and save the output.
   | Version | Add this slot | Write down: what changed in the output? |
   | --- | --- | --- |
   | v1 | **Context:** paste the source and add "Use only the facts above." | |
   | v2 | **Audience:** "for all 140 directorate employees, many of whom already telework" | |
   | v3 | **Format:** "BLUF email, ≤120 words, subject line, the deadline in the first sentence, 3 bullets max" | |
   | v4 | **Constraints:** "Don't add policies or dates that aren't in the source. Plain language, no jargon" | |
   | v5 | **Example:** paste a short email you like (fabricated, never a real one from work) and add "match this tone" | |
3. **Compare (7 min).** Put v0 and v5 side by side. Which version made the
   biggest single jump?
4. **Ask it to ask you (5 min).** New conversation: paste v5 and add *"Before
   you write, ask me any questions you need answered."* What did it ask that
   none of your slots answered?

## Done when

- [ ] Six versions are saved (v0–v5)
- [ ] One slot is named as "the biggest jump", with a reason
- [ ] At least one question from step 4 is written down

## Stretch

Write the shortest prompt that still gets a v5-quality email. Which slots
can't be dropped?

## Debrief questions

- Which slot made the biggest difference, and was it the same for everyone in the room?
- Did v0 invent anything that v1 removed?

## Instructor: answer key and pitfalls

- **v0** almost always invents details: days allowed, dates, a form name. Use
  that as the lead-in to grounding.
- **v1 (Context)** usually gives the biggest jump. **v3 (Format)** comes second.
- **Pitfall:** learners keep adding to one conversation instead of starting new
  ones. Then the comparison isn't fair, because earlier turns carry over.
  Insist on a new conversation per version.
