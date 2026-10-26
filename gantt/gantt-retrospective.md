# Gantt retrospective: plan (v1) vs real development

Group 12DP-B · MODY2 (GCK) · prepared on 22/10/2026, updated on 24/10 and finalised on 26/10/2026 (submission day).

Figure `gantt-v1-vs-final.png` compares, for every task, the **planned** bar (Gantt v1, delivered 09/10 and corrected 12/10) with the **real** bar (from the commit history) and, for unfinished tasks, the **re-planned** bar. `gantt-v2-plan-vs-real.xlsx` has the same data day by day (sheet *Timeline*) and the delay of each task (sheet *Plan vs Real*).

## Delay per task (working days between planned and real/forecast finish)

| Task | Planned finish | Real / forecast finish | Delay (working days) |
|---|---|---|---|
| 1.1 Repository set-up and structure | 17/09/26 | 12/10/26 | +17 |
| 1.2 Role and section assignment | 07/10/26 | 07/10/26 | 0 |
| 1.3 Gantt chart v1 + risk analysis (delivery) | 09/10/26 | 12/10/26 | +1 |
| 2.1 Initial paper scan | 27/09/26 | 01/10/26 | +4 |
| 2.2 Literature search on MODY2 and GCK (PDFs in references/) | 14/10/26 | 25/10/26 | +7 |
| 2.3 Reference log in Mini Oxford style | 16/10/26 | 26/10/26 | +6 |
| 3.1 Retrieve human GCK gene and protein | 09/10/26 | 15/10/26 | +4 |
| 3.2 Characterise the variant | 13/10/26 | 25/10/26 | +8 |
| 3.3 Select comparison species | 09/10/26 | 15/10/26 | +4 |
| 3.4 Pairwise and multiple sequence alignment | 19/10/26 | 23/10/26 | +4 |
| 3.5 Structural analysis (PDB) | 16/10/26 | 25/10/26 | +5 |
| 3.6 Structure superposition healthy vs variant | 23/10/26 | 22/10/26 | -1 |
| 4.1 Background section | 19/10/26 | 25/10/26 | +4 |
| 4.2 Methods section | 16/10/26 | 25/10/26 | +5 |
| 4.3 Results section | 26/10/26 | 25/10/26 | 0 |
| 4.4 Discussion and Conclusions | 23/10/26 | 26/10/26 | +1 |
| 4.5 Abstract and keywords | 26/10/26 | 25/10/26 | 0 |
| 4.6 Format and citation review | 26/10/26 | 26/10/26 (forecast) | 0 |
| 5.1 Live Gantt update and retrospective | 22/10/26 | 26/10/26 | +2 |
| 5.2 Defence preparation, all sections | 03/11/26 | 03/11/26 (forecast) | 0 |

**Summary:** 14 of 20 tasks finished later than planned. The delays concentrate in WP2 (literature) and WP3 (analyses); WP4 (writing) recovered most of the delay, so the report is submitted on time.

## What went differently and why

1. **Literature started late (2.1, +10 days).** The first weeks were spent understanding the brief and setting up the repository. Literature then caught up quickly (most PDFs on 19/10).
2. **Background before analysis.** On 19/10 four members wrote Background drafts in parallel. This gave us a solid disease description, but the analyses of WP3 (alignments, structure) were postponed.
3. **Incident in the variant analysis (3.2).** Our first analysis described a different substitution. The tutoring on 21/10 made us re-check the MODY2.zip files: the real variant is **c.1015G>A, p.Glu339Lys (E339K)**, a charge-reversing change. Lesson: validate key data against the provided files before building on it (risk R4; its contingency, use MODY2.zip as reference, is what solved it).
4. **The class session of 22/10 unlocked WP3.** The conservation report and the reading of Liu 2011 with the lecturer gave us the cross-species and WT vs mutant analyses at once; the species comparison (Xenopus + Ovis aries) was written on 23-24/10.
5. **Re-assignment of tasks.** When a member could not finish a block in time, another member took it (structural analysis 3.5, Discussion 4.4). This kept the deadline but made the workload uneven; the attribution of each part is in the commit history and in the Author contributions of the report.
6. **One final document from 24/10.** Until 24/10 there were several drafts (Markdown, Word, Spanish). Creating borrador/Paper.md as the only final document made the merge possible, but also caused concurrent edits on 25-26/10 (risk R2).
7. **The live status document started late** (22/10 instead of 10/10), so part of this retrospective was reconstructed from the commit history.
8. **Commit messages.** Several early commits only have the file name as title (the description was written in the wrong field). From 24/10 most commits have a descriptive title.

## Risk register review (risk matrix of the Gantt v1)

| ID | Risk | Happened? | Contingency applied? | Outcome |
|---|---|---|---|---|
| R1 | Superposition lab (22/10) leaves very little buffer | Yes | Partly. The planned contingency (draft Results from the alignments first) could not be applied because the alignments were also late. Instead, all remaining analyses were split among the five members on 22/10. | Results finished on 25/10, 1 working day before the deadline. |
| R2 | Merge conflicts when several members edit the same files | Yes (25-26/10) | Late. 'One file/section per person' was not possible because the final report is a single file. On 26/10 we agreed a turn-taking rule. | No work was lost, but several edits had to be repeated. Lesson: assign sections in separate files and merge at the end. |
| R3 | No experimental PDB structure for the variant | No | Not needed: PDB 3QIC is the crystal structure of E339K (Liu 2011). | We used experimental structures instead of an AlphaFold prediction. |
| R4 | Sequence retrieved does not match MODY2.zip | Yes (as a wrong variant) | Yes: MODY2.zip was used as the reference after the tutoring of 21/10. | Incident 3.2 solved; real variant c.1015G>A (E339K). |
| R5 | A member is unavailable during the final week | Partly (midterm exams) | Partly: sections were re-assigned when a member could not finish (e.g. 3.5 written by Ariadna). | All sections completed; workload became uneven (see 3.5 and 4.4). |

New risks identified during the project, with their mitigation:

| ID | Risk | Mitigation |
|---|---|---|
| R6 | Contradictory deadlines (18:00 in an e-mail, 22:00 on Atenea) | We kept the earlier one (18:00) as internal deadline. |
| R7 | Work done outside version control (shared document, automatic Google Sheets export) | Everything is moved to Paper.md by its author with their own commit before submission; the automatic export is disconnected. |
| R8 | Overlap with the midterm exams of other subjects (29/10-3/11) | Defence preparation (5.2) planned in short daily sessions; each member prepares questions on every section. |

## Contingency plan until the defence (5/11)

| Critical part | Risk | Plan |
|---|---|---|
| Submission (26/10) | Unfinished merge or missing references at 18:00 | Atenea closes at 22:00: the 18:00-22:00 window is the buffer; the version on GitHub at 18:00 is submitted if the review is not finished |
| Defence (5/11) | 'Niche awareness': each member only knows their own section | Every member prepares 3 questions on each section of the others; joint rehearsal before 5/11 |
| Defence (5/11) | A member is absent | Every section has a second presenter |

## Lessons for the next project

- Keep the status document updated from day one, not only before a milestone.
- Start the analysis as soon as the data are available, in parallel with the writing.
- Check every key fact (variant, dates, deadlines) against the official files and e-mails.
- Write each section in its own file and merge at the end, or agree turns for the shared file.
- Keep all the work in the repository (no parallel documents) and make small, frequent commits with clear messages.
