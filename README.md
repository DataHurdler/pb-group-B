# AI Prompt Engineering for Government Staff Work

Status: draft. Content is written; approvals and tool details are pending (see below).

A **one-day course with 6 hours of instruction**, run within an 8-hour workday,
for USSTRATCOM government employees. Participants learn to:

- **improve workflow**: turn recurring tasks into reusable AI-assisted steps
- **write for busy executive readers**: BLUF emails, one-page information
  papers, and decision memos
- **make AI part of daily work**, safely: data-handling rules, and checking
  every output before it goes up the chain

Everything is hands-on. Every source text is fabricated and unclassified.
There is no exam or graded work.

## At a glance

| | |
| --- | --- |
| Audience | Action officers, staff officers, analysts, admin staff. 12–24, in pairs |
| Day | 8:00–4:00: 360 instructional minutes (95 teaching, 265 hands-on), a 60-minute lunch, and four 15-minute breaks |
| Tool | The command's approved AI tool: `[TOOL NAME]` (to be confirmed) |
| Certificate | Certificate of completion for attending the full day |
| Student handout | [handouts/student-syllabus.md](handouts/student-syllabus.md), printable as [PDF](handouts/print/student-syllabus.pdf) |

## The day

| Time | Block | Objective |
| --- | --- | --- |
| 8:00 | Welcome and the data rule | — |
| 8:15 | How AI works, and the rules of the road | LO1 |
| 9:15 | *Break* | |
| 9:30 | The six slots | LO2 |
| 10:30 | *Break* | |
| 10:45 | Writing for executives | LO3 |
| 11:45 | *Lunch* | |
| 12:45 | AI in your workflow | LO4 |
| 1:45 | *Break* | |
| 2:00 | Verify and judge | LO5 |
| 3:00 | *Break* | |
| 3:15 | Put it together: a decision memo | all |
| 3:45 | Close: your 30-day plan | LO4 |

The full timetable is in [course/schedule.md](course/schedule.md). The
objectives and scope are in [course/syllabus.md](course/syllabus.md).

## Start here

| If you want to… | Open |
| --- | --- |
| Know what the course promises | [course/syllabus.md](course/syllabus.md) (instructor) or [handouts/student-syllabus.md](handouts/student-syllabus.md) (participants) |
| Teach a module | [modules/](modules/), one README per block, with timing, teaching points, and instructor notes |
| Run a lab | [labs/](labs/), with fabricated sources and an instructor answer key in each |
| See what participants take home | [handouts/](handouts/): student syllabus, data-rules card, six-slots card, executive-writing card, prompt library |
| Prepare | [instructor/prep-checklist.md](instructor/prep-checklist.md) |
| Run the day | [instructor/run-of-show.md](instructor/run-of-show.md) |
| Contact participants, and collect feedback | [participants/](participants/), [feedback/](feedback/) |

## Must be settled before this can run

These can't be decided from inside the repo. Each is marked `[BRACKETED]` where
it appears.

1. **Which AI tool, and what it's authorized to hold.** This sets the data
   rules card, the Lab 01 answer key, and the setup instructions. Confirm with
   the command AI or cybersecurity office.
2. **What the certificate of completion counts for.** Who signs it, and
   whether it's recorded or carries any credit, is up to the training office.
3. **Review of the materials** under the command's process for training
   content.
4. **Records guidance** on keeping AI conversations, from the records manager.

## Still to build

- Slides ([slides/README.md](slides/README.md) has the outline)
- Participant print versions of the labs, with the instructor sections removed

To re-render the student syllabus PDF after editing it:

```sh
cd handouts && quarto render student-syllabus.md --to pdf --output-dir print \
  -M geometry:"margin=0.6in" -M fontsize=10pt
```
