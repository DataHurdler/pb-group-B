# Lab 05 — Test and Refine

Status: draft
Module: 05 · Time: 37 min · Objective: LO4 (and LO3: accuracy) · Work: individual

## Goal

Catch the errors in a confident AI summary, then test and refine your own
template against criteria you wrote *before* running it.

## You'll need

- Free ChatGPT on your laptop
- A pen. Part A is done on paper, with no AI
- Your template and sample input from Lab 04

## Source (fabricated for training, unclassified)

> **Quarterly Mandatory Training Status, Directorate of Support Services, Q3.**
> As of 30 June, 212 of 248 assigned personnel (85%) had completed all annual
> mandatory training. The command goal is 95% by 30 September. The largest gap
> is Cyber Awareness, at 78% (193 of 248). Records Management is at 91%, and
> Equal Opportunity at 96%. The training office attributes the Cyber Awareness
> gap mainly to the new course version released in May, which reset
> completion for 41 personnel who had finished the old version. The office
> recommends a 60-minute protected training block on 18 July for all
> personnel still incomplete. Supervisors will receive incomplete lists by
> 8 July. No funding is required.

## AI summary to check

> **BLUF:** Mandatory training completion is 85% against a 95% goal due
> 30 Sep. Cyber Awareness is the largest gap at 87%, driven by a new course
> version that reset completion for 41 personnel. The training office
> recommends a 90-minute protected training block on 18 July; supervisors
> receive incomplete lists by 8 July. The block requires $4,000 in contractor
> support. Per DoD policy, directorates below 90% must report to the Chief of
> Staff monthly.

## Part A — By hand (10 min)

Check every claim in the summary against the source. Underline each error,
and write the type: *changed number*, *invented fact*, *invented authority*,
or *lost caveat*.

## Part B — Make the AI show its work (7 min)

1. New chat: paste the source and the summary, then:
   > List every claim in the summary. For each one, quote the source sentence
   > that supports it, or write NOT IN SOURCE.
2. Did it find everything you found by hand? Did it flag anything that was
   actually correct?

## Part C — Test and refine your own template (20 min)

1. **Write 3 criteria before you run anything (4 min).** Each one must be
   something a colleague could check without asking you. For example: "the
   deadline is in the first sentence," "≤120 words," "every number appears in
   the input."
2. **Run and score (4 min).** In a new chat, run your template on your sample
   input. Score each criterion pass or fail.
3. **Change one thing, and run again (6 min).** Pick the failing criterion,
   change one thing in the template, and rerun in a new chat. Score again.
   Record what you changed and whether it helped.

   | Run | What I changed | Criterion 1 | Criterion 2 | Criterion 3 |
   | --- | --- | --- | --- | --- |
   | 1 | (version 1, from Lab 04) | | | |
   | 2 | | | | |
   | 3 | | | | |

4. **Cold test (6 min).** Open a new chat and paste **only the template**,
   with the slots unfilled, then add: *"I'm a colleague who has never seen this.
   What would you need to ask before you could use it?"* Add the answers to
   the template. If time allows, also run it on a second, different made-up
   input.

## Done when

- [ ] Part A: errors are found and typed
- [ ] Part C: 3 criteria, at least two scored runs, and one change recorded
- [ ] Your template has survived a cold test. **This is the template you take home**

## Instructor: answer key and pitfalls

**The four errors:**

| # | Summary says | Source says | Type |
| --- | --- | --- | --- |
| 1 | Cyber Awareness at 87% | 78% | changed number (transposed) |
| 2 | 90-minute block | 60-minute | changed number |
| 3 | $4,000 in contractor support | "No funding is required" | invented fact (it contradicts the source) |
| 4 | "Per DoD policy… report monthly" | Not in source | invented authority |

**Part C pitfalls:**

- **Criteria nobody else could check** ("clear," "professional"). Ask:
  *"Could a colleague score that without asking you?"*
- **Changing three things at once.** If it improves, they won't know why. One
  change per run.
- **A template that works only on the one sample.** Push for the second input,
  if there's time.

**Pitfall in Part A:** most learners find #1 and #3 and miss #4, because an
authoritative tone reads as true. Point at #4 in the debrief. It's the most
dangerous error for this audience, because a senior reader may act on it.
