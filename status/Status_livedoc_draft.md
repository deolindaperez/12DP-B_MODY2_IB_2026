# Project Status Document — Group 12DP-B · MODY2 (GCK)

Last update: 26 October 2026 (submission day). Planned dates come from the Gantt v1 (delivered 09/10, corrected 12/10). Real dates come from the commit history of this repository and from our meeting notes. Statuses: Completed, In progress, Pending, Incident.

| Task | Resp. | Plan. Start Date | Plan. Finish Date | Real Start Date | Real Finish Date | Status | Notes |
|---|---|---|---|---|---|---|---|
| 1.1 Repository set-up and structure | Deolinda | 17/09/26 | 17/09/26 | 17/09/26 | 12/10/26 | Completed | Repo created on 17/09, but the folders only got the required names (report/, status/, gantt/, references/) on 12/10, after reviewing the formal requirements. Final clean-up on 25/10 (old drafts and non-source files removed). |
| 1.2 Role and section assignment | All | 07/10/26 | 07/10/26 | 07/10/26 | 07/10/26 | Completed | Roles confirmed by all members on 07/10, as planned. Sections were re-assigned on 22/10 (see Events). |
| 1.3 Gantt chart v1 + risk analysis (delivery) | Biel | 07/10/26 | 09/10/26 | 07/10/26 | 12/10/26 | Completed | Delivered on time (09/10, 11:38). Corrected on 12/10 after the lecturer's feedback, so the task closed 1 working day late. The corrected v1 is in gantt/ (gantt-v1-delivered-corrected). |
| 2.1 Initial paper scan | All | 20/09/26 | 27/09/26 | 30/09/26 | 01/10/26 | Completed | Started 10 days late: the first weeks went into setting up the repository and understanding the project brief. Shared notes file created on 30/09. |
| 2.2 Literature search on MODY2 and GCK (PDFs in references/) | All | 07/10/26 | 14/10/26 | 08/10/26 | 25/10/26 | Completed | Most PDFs were added on 19/10 (Biel 6, Unai 2, Maeve 1). The key primary paper on our variant (Liu 2011) was only found on 21/10 and deposited on 22/10; Madeira 2024 (EMBOSS) on 24/10; the class conservation report (source of the Xenopus data) on 25/10. On 25/10 the folder was cleaned: only sources that the report cites were kept (a search-engine capture, a notes file and two redundant reviews, Matschinsky 1990 and Zhang 2023, were removed). |
| 2.3 Reference log in Mini Oxford style | Deolinda | 15/10/26 | 16/10/26 | 08/10/26 |  | In progress | A citations file exists since 08/10, but references were in mixed formats (Mini Oxford, URLs, PMIDs). The file was cleaned on 25/10 (Biel). On the morning of 26/10 the reference list of Paper.md still had only Liu 2011 and Kamata 2004: it is completed during the final review (4.6). |
| 3.1 Retrieve human GCK gene and protein | Maeve and Unai | 09/10/26 | 09/10/26 | 08/10/26 | 15/10/26 | Completed | Gene/protein questions answered on 08/10; NCBI dataset for GCK added on 15/10. |
| 3.2 Characterise the variant | Maeve and Unai | 09/10/26 | 13/10/26 | 15/10/26 | 25/10/26 | Completed | INCIDENT (solved): the first analysis (Questions.md, 15/10) described a different substitution (c.388A>G). At the tutoring on 21/10 we compared the WT and mutant FASTA files of MODY2.zip again: the real variant is c.1015G>A, p.Glu339Lys (E339K). The genomic characterisation (codon GAG>AAG, transition, missense, charge reversal) was written as a Results subsection on 25/10 (Deolinda, revised by Ariadna). 8 working days late. |
| 3.3 Select comparison species | Ari and Biel | 09/10/26 | 09/10/26 | 15/10/26 | 15/10/26 | Completed | Ovis aries (close mammal) and Xenopus laevis (distant vertebrate) retrieved on 15/10 with BLAST (NCBI RefSeq NP_001274400.1 for sheep), 4 working days later than planned. On 22/10 the group considered dropping Ovis aries for lack of time; after re-reading the brief ('at least 2 other relevant species') it was kept on 23/10. |
| 3.4 Pairwise and multiple sequence alignment | Maeve / Biel | 15/10/26 | 19/10/26 | 22/10/26 | 23/10/26 | Completed | Delayed because the team prioritised the Background draft. Done in two parts: human vs Xenopus from the conservation report generated in class (22/10; 80.6% identity, 88.4% same physicochemical group) and human vs Ovis aries with EMBOSS Needle (23/10, Biel; 96.6% identity, 98.3% similarity, 0 gaps). Residue 339 is E in the three species. The Needle output was re-uploaded to references/ on 25/10, after the data/ folder was removed. |
| 3.5 Structural analysis (PDB) | Unai | 14/10/26 | 16/10/26 | 19/10/26 | 25/10/26 | Completed | Reference structures 1V4S/1V4T identified on 19/10. On 21/10 we found an experimental structure of our mutant (PDB 3QIC), so risk R3 did not happen. The structural and kinetic analysis of E339K (Liu 2011 + class superposition) was finally written by Ariadna (24-25/10) and its method by Ariadna (25/10); Unai contributed the clinical/pregnancy text instead (25-26/10). 5 working days late. |
| 3.6 Structure superposition healthy vs variant | All (class session) | 22/10/26 | 23/10/26 | 22/10/26 | 22/10/26 | Completed | Done in the 22/10 class session: the conservation report includes the WT vs E339K superposition (global RMSD 1.48 A; 2.49 A at residue 339) and the human vs Xenopus superposition (global RMSD 8.18 A, one domain displaced as a block). Interpreted the same day with the lecturer using Liu 2011 (PDB 3QIC). |
| 4.1 Background section | Ari | 14/10/26 | 19/10/26 | 19/10/26 | 25/10/26 | Completed | Drafts written in borrador/ (19-22/10) by four members, partly in Spanish. On 24/10 Ariadna created borrador/Paper.md as the single final document. On 25/10 Maeve rewrote the MODY2/GCK background and the separate 'Physiology of wild-type glucokinase' subsection (Biel, 19-24/10) was condensed into the Background (Ariadna) to keep one introduction within the length limit. Aims of the study added at the end. |
| 4.2 Methods section | Biel | 14/10/26 | 16/10/26 | 24/10/26 | 25/10/26 | Completed | Could not be written before the analyses (3.4-3.6). Started on 24/10 by Biel (EMBOSS Needle parameters, source of the Xenopus data); completed on 25/10 by Deolinda (sequence sources, BLASTn, order of paragraphs) and Ariadna (PDB search, superposition, data taken from Liu 2011). |
| 4.3 Results section | Maeve | 20/10/26 | 26/10/26 | 24/10/26 | 25/10/26 | Completed | Three subsections: species comparison + Table 1 (Biel, 24/10), genomic characterisation of E339K (Deolinda/Ariadna, 25/10) and structural and kinetic impact (Ariadna/Maeve, 24-25/10). Headings reorganised into the BMC structure on 25/10 (Biel, Deolinda). Finished the day before the planned date. |
| 4.4 Discussion and Conclusions | Unai | 20/10/26 | 23/10/26 | 25/10/26 |  | In progress | Re-planned after Results. Discussion started by Deolinda (25/10) and rewritten by Maeve (26/10); a second version was drafted in parallel in a shared document, and both are merged during the final review. Conclusions written on 26/10. 1 working day late. |
| 4.5 Abstract and keywords | Deolinda | 26/10/26 | 26/10/26 | 24/10/26 | 25/10/26 | Completed | Started on 24/10 and finished on 25/10 ('Final revision for abstract'), one day earlier than planned; it is checked against the final Discussion during 4.6. |
| 4.6 Format and citation review | All | 26/10/26 | 26/10/26 | 26/10/26 |  | In progress | 26/10, final review before the internal deadline (18:00; Atenea closes at 22:00). Merge of the two Discussion versions, complete reference list, remaining [CITATION] marks, BMC section order and English language check. No questions are answered by the lecturers on 26/10. |
| 5.1 Live Gantt update and retrospective | Biel | 10/10/26 | 22/10/26 | 22/10/26 | 26/10/26 | Completed | The live status document was only created on 22/10 (planned from 10/10). Gantt v2, this status document and the retrospective were prepared on 22/10, updated on 24/10 and finalised on 26/10 from the commit history. |
| 5.2 Defence preparation, all sections | All | 27/10/26 | 03/11/26 |  |  | Pending | Unchanged. Every member must be able to explain every section (not only their own). |

## Events that changed the plan

| Date | Event | Consequence |
|---|---|---|
| 09/10 | Gantt v1 delivered | Feedback from the lecturer received on 12/10 → corrected Gantt v1 |
| 19/10 | Most members drafted the Background on the same day | Background progressed, analyses (WP3) were delayed |
| 19/10 | E-mail from the teaching team | Submission deadline 26/10 at 18:00 |
| 21/10 | Tutoring session (12DP-B) | Our analysis was off-track; the variant was re-checked → E339K (incident 3.2) |
| 22/10 | Meeting with the lecturer + superposition lab (conservation report, reading of Liu 2011) | WP3 superposition done; Liu 2011 becomes the core reference; tasks re-assigned to finish all analyses by 24/10 |
| 22/10 | Group chat after the session | Remaining sections split: species comparison (Biel); E339K mechanism; genomic characterisation; background theory |
| 23/10 | Re-reading of the brief | Ovis aries kept as second species (brief asks for at least 2) |
| 24/10 | Updated brief and schedule on Atenea | Official deadline 26/10 22:00 (we keep 18:00); no questions answered on 26/10 |
| 24/10 | Ariadna creates borrador/Paper.md | One single final document instead of several drafts |
| 25/10 | Online group meeting | BMC heading structure agreed; repository cleaned; references limited to cited sources; missing sources deposited (Needle output, conservation report) |
| 25/10 | data/ folder removed | Needle output moved to references/; the automatic Google Sheets export recreates data/gantt_chart_auto.csv (see R7) |
| 25-26/10 | Several members editing Paper.md and a shared document at the same time | Risk R2 happened (concurrent edits); turn-taking agreed on 26/10: announce before editing, commit, announce when done |
| 26/10 | Final review and submission | Internal deadline 18:00 |

## Risks (from the Gantt v1 risk matrix) and what happened

| ID | Risk | Happened? | Contingency applied? | Outcome |
|---|---|---|---|---|
| R1 | Superposition lab (22/10) leaves very little buffer | Yes | Partly. The planned contingency (draft Results from the alignments first) could not be applied because the alignments were also late. Instead, all remaining analyses were split among the five members on 22/10. | Results finished on 25/10, 1 working day before the deadline. |
| R2 | Merge conflicts when several members edit the same files | Yes (25-26/10) | Late. 'One file/section per person' was not possible because the final report is a single file. On 26/10 we agreed a turn-taking rule. | No work was lost, but several edits had to be repeated. Lesson: assign sections in separate files and merge at the end. |
| R3 | No experimental PDB structure for the variant | No | Not needed: PDB 3QIC is the crystal structure of E339K (Liu 2011). | We used experimental structures instead of an AlphaFold prediction. |
| R4 | Sequence retrieved does not match MODY2.zip | Yes (as a wrong variant) | Yes: MODY2.zip was used as the reference after the tutoring of 21/10. | Incident 3.2 solved; real variant c.1015G>A (E339K). |
| R5 | A member is unavailable during the final week | Partly (midterm exams) | Partly: sections were re-assigned when a member could not finish (e.g. 3.5 written by Ariadna). | All sections completed; workload became uneven (see 3.5 and 4.4). |

New risks found during the project:

| ID | Risk | Mitigation |
|---|---|---|
| R6 | Contradictory deadlines (18:00 in an e-mail, 22:00 on Atenea) | We kept the earlier one (18:00) as internal deadline. |
| R7 | Work done outside version control (shared document, automatic Google Sheets export) | Everything is moved to Paper.md by its author with their own commit before submission; the automatic export is disconnected. |
| R8 | Overlap with the midterm exams of other subjects (29/10-3/11) | Defence preparation (5.2) planned in short daily sessions; each member prepares questions on every section. |
