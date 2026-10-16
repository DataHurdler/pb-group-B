# Syllabus — AI and LLM Prompt Engineering

Status: draft. This is the instructor's version. Participants get
[handouts/student-syllabus.md](../handouts/student-syllabus.md). The fixed
facts come from [CHARTER.md](../CHARTER.md). Where this file differs from the
charter, [CHANGES.md](../CHANGES.md) says so and gives the reason.

## Description (approved, word for word)

The quality of results produced by generative AI often depends on the quality of
the instructions it receives. Effective prompt design helps users communicate
their intent clearly, provide appropriate context, establish constraints, and
guide large language models (LLMs) toward more useful outputs.

In this hands-on course, participants will learn practical techniques for
designing, testing, and refining prompts for workplace applications.
Participants will explore how prompt structure influences AI-generated responses
and how thoughtful prompt design can improve quality, consistency, and
efficiency.

## This offering

Tailored for USSTRATCOM government employees, both civilian and military. The
workplace applications are their daily staff work: writing for busy executive
readers (BLUF emails, information papers, decision memos) and making recurring
tasks faster with reusable prompts. **Each participant works individually** on
their own laptop.

## Audience

- **Charter:** working professionals in mixed roles. No programming is assumed
  or taught.
- **This offering:** action officers, staff officers, analysts, and
  administrative staff who write, summarize, or coordinate as a routine part
  of their job.
- **Not assumed:** any prior AI use.
- **Group size:** 12–24, each working individually.

## Learning objectives (approved, word for word)

1. **LO1:** Explain how large language models use prompts and context to generate responses.
2. **LO2:** Write clear, structured prompts that produce more useful and relevant outputs.
3. **LO3:** Apply prompting techniques to improve accuracy, consistency, format, and usefulness.
4. **LO4:** Refine prompts through iterative testing and evaluation.
5. **LO5:** Use prompting strategies that improve efficiency while maintaining output quality.

Progress is checked in each lab and debrief, not by a test. There is no exam
or graded work.

## What a learner leaves with

**A tested prompt template for one recurring task from their own job, that a
colleague could use without help.** (Charter, word for word.)

This is built across the day as an individual thread:

| When | Step |
| --- | --- |
| 8:30, Module 00 | Name one recurring task, in general terms, on an index card |
| 1:00, Module 04 | Build version 1 of the template, with `[SLOTS]` and a made-up sample input |
| 2:15, Module 05 | Write criteria, test, change one thing, and retest. Then a cold test: could someone use it without asking you anything? |
| 3:45, Module 07 | Commit to using it at work within 30 days, on the command's approved tool |

## Certificate of completion

Participants receive a certificate of completion when they **attend every
module**. Up to 15 minutes' total absence is allowed with the instructor's
approval. Attendance is recorded on sign-in sheets at 8:30 and 1:00. The
certificate template is in
[instructor/certificate-template.md](../instructor/certificate-template.md).

> The certificate records attendance. Whether it counts toward any training
> record or continuing-education hours is up to the command's training office.

## Tools (charter, fixed)

- **Each learner's own laptop and a free ChatGPT account.** There are no paid
  features, no file uploads, and nothing to install. Every source text is
  pasted, and none is longer than one page.
- **The instructor** runs demos live on the projector, and projects
  volunteers' prompts during debriefs.

## Ground rules for the whole day

- **No confidential data in any prompt** (charter): no student, personnel, or
  health records. In this offering, that also means nothing from work at all.
  Free ChatGPT is a public tool, not an approved government system. Every
  source text in this repo is fabricated and labeled that way.
- **At work afterwards,** participants use only the command's approved AI
  tool, within its authorization. See
  [handouts/data-rules-card.md](../handouts/data-rules-card.md).
- **The writer owns the output.** AI drafts. A person checks every fact and
  signs.

## Scope

| In scope | Out of scope: other courses in the series cover these (charter) |
| --- | --- |
| How prompts and context shape LLM output | **Introduction to AI and Machine Learning** |
| Structured prompts; executive writing: BLUF, info papers, decision memos | **Building an AI Agent** (automation and connecting AI to other systems) |
| Testing and refining prompts against criteria | **AI Ethics and Governance** (policy and responsible-use questions beyond today's data rule) |
| Reusable templates for recurring tasks | **Data Analytics, Cleaning and Visualization in Excel** |

## Module map

| Module | Title | Objective | Lab |
| --- | --- | --- | --- |
| 00 | Welcome | — | — |
| 01 | How LLMs use prompts, and the rules of the road | LO1 | [01](../labs/01-same-prompt-two-answers.md) |
| 02 | The six slots | LO2 | [02](../labs/02-rebuild-a-vague-prompt.md) |
| 03 | Writing for executives | LO3 | [03](../labs/03-bluf-rewrite.md) |
| 04 | AI in your workflow | LO5 | [04](../labs/04-meeting-to-actions.md) |
| 05 | Test and refine | LO4 (and LO3: accuracy) | [05](../labs/05-test-and-refine.md) |
| 06 | Put it together | LO3, LO5 | [06](../labs/06-decision-memo.md) |
| 07 | Close: your 30-day plan | LO5 | — |
