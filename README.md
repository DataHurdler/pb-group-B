# AI and LLM Prompt Engineering

Status: draft. Aligned to [CHARTER.md](CHARTER.md). **What changed, and
where it differs from the charter: [CHANGES.md](CHANGES.md).**

A **one-day, hands-on course**: 6 hours of instruction in an 8-hour workday.
This offering is tailored for USSTRATCOM government employees. Each learner
works **individually**, on their own laptop with a free ChatGPT account. They
learn to:

- write clear, structured prompts, and refine them through testing
- write for busy executive readers: BLUF emails, information papers, and
  decision memos
- make recurring tasks faster with reusable templates, without losing quality

Every source text is fabricated and unclassified. There is no exam or graded
work.

**Each learner leaves with:** a tested prompt template for one recurring task
from their own job, that a colleague could use without help.

## At a glance

| | |
| --- | --- |
| Audience | Working professionals in mixed roles. This offering: action officers, staff officers, analysts, admin staff. 12–24, working individually |
| Day | 8:00–4:00: 30 minutes of setup, 360 instructional minutes (95 teaching, 265 activity), a 60-minute lunch, and two 15-minute breaks |
| Tools | Learner's own laptop and a free ChatGPT account. No paid features, no uploads, nothing to install |
| Certificate | Certificate of completion for attending the full day |
| Student handout | [handouts/student-syllabus.md](handouts/student-syllabus.md), printable as [PDF](handouts/print/student-syllabus.pdf) |

## The day

| Time | Block | Objective |
| --- | --- | --- |
| 8:00 | *Arrival and setup* | |
| 8:30 | Welcome: objectives, the data rule, your own task | — |
| 8:45 | How LLMs use prompts, and the rules of the road | LO1 |
| 9:45 | *Break* | |
| 10:00 | The six slots | LO2 |
| 11:00 | Writing for executives | LO3 |
| 12:00 | *Lunch* | |
| 1:00 | AI in your workflow, and your own template | LO5 |
| 2:00 | *Break* | |
| 2:15 | Test and refine | LO4 |
| 3:15 | Put it together: a decision memo | LO3, LO5 |
| 3:45 | Close: your 30-day plan | LO5 |

The full timetable is in [course/schedule.md](course/schedule.md). The
objectives (approved, word for word) and scope are in
[course/syllabus.md](course/syllabus.md).

## Start here

| If you want to… | Open |
| --- | --- |
| Know the fixed facts | [CHARTER.md](CHARTER.md) |
| See what changed from the last version | [CHANGES.md](CHANGES.md) |
| Know what the course promises | [course/syllabus.md](course/syllabus.md) (instructor) or [handouts/student-syllabus.md](handouts/student-syllabus.md) (learners) |
| Teach a module | [modules/](modules/), one README per block in the charter's [module template](templates/module-template.md) |
| Run a lab | [labs/](labs/), with fabricated sources and an instructor answer key in each |
| See what learners take home | [handouts/](handouts/) |
| Prepare | [instructor/prep-checklist.md](instructor/prep-checklist.md) |
| Run the day | [instructor/run-of-show.md](instructor/run-of-show.md) |
| Contact learners, and collect feedback | [participants/](participants/), [feedback/](feedback/) |

## Must be settled before this can run

1. **Personal laptops with internet access in the training room.** The
   charter requires them, and a secure facility may not allow it. Settle this
   first.
2. **Personal ChatGPT use in class**, with fabricated material only, cleared
   with the command AI or cybersecurity office.
3. **The at-work approved tool and its authorization**, for the second half
   of the data rules card.
4. **What the certificate of completion counts for**, from the training office.
5. **Review of the materials** under the command's process for training content.

## Still to build

- Slides ([slides/README.md](slides/README.md) has the outline)
- Participant print versions of the labs, with the instructor sections removed

To re-render the student syllabus PDF after editing it:

```sh
cd handouts && quarto render student-syllabus.md --to pdf --output-dir print \
  -M geometry:"margin=0.6in" -M fontsize=10pt
```
