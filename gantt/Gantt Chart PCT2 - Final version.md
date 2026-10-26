# Gantt Chart — Porphyria Cutanea Tarda Type 2 (PCT2) — Final version 26/10

Final schedule with the planned and real dates of each task, updated up to the final delivery on 26 October 2026. Eva and Lídia withdrew from the project, so all the tasks are assigned to Sara and Laia. Planned durations count working days only (Monday to Friday); Monday 12 October is a public holiday in Spain. The original plan is in [Gantt Chart PCT2 - Frozen version 9 Oct](Gantt%20Chart%20PCT2%20-%20Frozen%20version%209%20Oct.md), and the notes on each task and the gap analysis are in the Project Status Document.

## Project information

### General objective

The project aims to investigate how changes in gene and protein sequences and structures contribute to the molecular basis of Porphyria Cutanea Tarda Type 2 (PCT), as well as to explore how comparative analysis of these sequences provides insights into the affected biological functions.

### Specific objectives

1. Learn what PCT type 2 is and which gene and protein are involved.
2. Collect the sequences and structures we need: the 4 FASTA files, the database records.
3. Find the mutation by comparing the WT and mutant sequences, and check if it is conserved in the homologs.
4. Look at where the mutation is in the 3D structure and compare the WT and mutant proteins.
5. Write the final report on GitHub with contributions from both members.

### Milestones

| ID  | Milestone                                 | Planned date | Real date  |   Gap   |
| --- | ----------------------------------------- | :----------: | :--------: | :-----: |
| M1  | Gantt chart and risk analysis delivered   |  9 October   | 9 October  | On time |
| M2  | Disease background completed              |  19 October  | 19 October | On time |
| M3  | Sequence and structure analyses completed |  20 October  | 23 October | +3 days |
| M4  | Final report and repository delivered     |  23 October  | 26 October | +3 days |

### Project members

- **Sara Charif Karkri el Abbassi** (_Undergraduate Student in Bioinformatics_) – Project Manager, Sequence Analyst and Structural Analyst: Responsible for defining scope, timeline tracking, Gantt chart management, and repository oversight. Responsible for pairwise and multiple alignment of human vs homologs, conservation analysis and interpretation, analysing the WT structure, mapping mutations onto the structure, comparing WT (wild-type) and mutant structures, and performing structural comparisons between human proteins and their homologs.
- **Laia Núñez Palma** (_Undergraduate Student in Bioinformatics_) – Disease & Literature Specialist, Data & Database Specialist and Sequence Analyst: Responsible for the biological foundation of the project: literature search and reference management, characterisation of PCT type 2 (UROD gene, protein and heme pathway), and analysis of penetrance, inheritance and risk factors. Responsible for FASTA validation, database curation, homolog selection, and pairwise alignment of WT (wild-type) vs mutant sequences.

Eva Rodríguez García (Structural Analyst) and Lídia Riba Garcia (Sequence Analyst) withdrew from the project. Laia and Sara took over their tasks, and the Gantt chart was updated on 20/10.

## Timeline

```mermaid
---
config:
  gantt:
    leftPadding: 130
    useWidth: 1000
    numberSectionStyles: 7
  themeCSS: |
    .task0, .section0 { fill: #3987e5; }
    .task1, .section1 { fill: #d95926; }
    .task2, .section2 { fill: #199e70; }
    .task3, .section3 { fill: #c98500; }
    .task4, .section4 { fill: #9085e9; }
    .section5, .section6 { fill: none; }
    .task { stroke: none; }
    .taskText0, .taskText1, .taskText2, .taskText3, .taskText4 { fill: #ffffff; }
    .taskTextOutside0, .taskTextOutside1, .taskTextOutside2, .taskTextOutside3, .taskTextOutside4, .taskTextOutside5, .taskTextOutside6 { fill: inherit; }
    .exclude-range { fill: #8c8c8c; fill-opacity: 0.2; }
---
gantt
    accTitle: Final Gantt chart of the PCT2 project with the real dates, 5 to 26 October 2026
    dateFormat YYYY-MM-DD
    axisFormat %d %b
    tickInterval 1day
    inclusiveEndDates
    excludes weekends, 2026-10-12
    todayMarker off

    section 1 Disease background<br>and literature
    1.1 Literature search and reference collection : 2026-10-05, 2026-10-08
    1.2 Disease characterisation (PCT2, UROD) : 2026-10-09, 2026-10-13
    1.3 Penetrance and inheritance : 2026-10-13, 2026-10-15
    1.4 Risk factors : 2026-10-16, 2026-10-19

    section 2 Data retrieval<br>and database work
    2.2 Validate the provided FASTA files : 2026-10-09, 2026-10-09
    2.3 Database search and curation : 2026-10-09, 2026-10-09
    2.4 Select homologs (Bacillus subtilis + 1 more) : 2026-10-13, 2026-10-14

    section 3 Sequence analysis
    3.1 Pairwise alignment WT (wild-type) vs mutant : 2026-10-14, 2026-10-15
    3.2 Pairwise and multiple alignment – human vs homologs : 2026-10-14, 2026-10-15
    3.3 Conservation analysis and interpretation : 2026-10-16, 2026-10-21

    section 4 Structural analysis
    4.1 Analyse WT structure : 2026-10-19, 2026-10-19
    4.2 Map mutation onto structure, compare WT (wild-type) vs mutant : 2026-10-17, 2026-10-19
    4.3 Structural comparison human vs homologs : 2026-10-22, 2026-10-23

    section 5 Report writing<br>and final delivery
    5.1 Draft Background / Introduction : 2026-10-13, 2026-10-25
    5.2 Draft Methods and Results – structure : 2026-10-21, 2026-10-23
    5.3 Draft Discussion, Conclusions and Abstract : 2026-10-22, 2026-10-26
    5.4 Cross-review and format check : 2026-10-22, 2026-10-26
    5.5 Final delivery – final Gantt and gap analysis : 2026-10-21, 2026-10-26

    section Extra task
    Extra task – Gantt chart update : 2026-10-20, 2026-10-20

    section Milestones
    M1 Gantt chart and risk analysis delivered : milestone, 2026-10-09, 2026-10-09
    M2 Disease background completed : milestone, 2026-10-19, 2026-10-19
    M3 Sequence and structure analyses completed : milestone, 2026-10-23, 2026-10-23
    M4 Final report and repository delivered : milestone, 2026-10-26, 2026-10-26
```

Bars are drawn from the real start and end dates (end date included). Diamonds mark the milestones M1–M4 on their real dates. Shaded days are weekends and the 12 October holiday. Task 2.1 (17 September) and task 5.6 (planned from 27 October to 5 November) fall outside this period, and task 2.5 was cancelled, so they have no bar.

## Dates, owners and progress

| ID    | Task title                                                    | Task owner    | Planned start date | Planned end date | Real start date | Real end date | Planned duration (days) |  Predecessor  |       Status        |
| ----- | ------------------------------------------------------------- | ------------- | :----------------: | :--------------: | :-------------: | :-----------: | :---------------------: | :-----------: | :-----------------: |
| **1** | **Disease background and literature**                         |               |                    |                  |                 |               |                         |               |                     |
| 1.1   | Literature search and reference collection                    | Laia          |       05/10        |      08/10       |      05/10      |     08/10     |            4            |       -       | Completed, on time  |
| 1.2   | Disease characterisation (PCT2, UROD)                         | Laia          |       09/10        |      13/10       |      09/10      |     13/10     |            2            |      1.1      | Completed, on time  |
| 1.3   | Penetrance and inheritance                                    | Laia          |       13/10        |      15/10       |      13/10      |     15/10     |            3            |   1.1, 1.2    | Completed, on time  |
| 1.4   | Risk factors                                                  | Laia          |       16/10        |      19/10       |      16/10      |     19/10     |            2            | 1.1, 1.2, 1.3 | Completed, on time  |
| **2** | **Data retrieval and database work**                          |               |                    |                  |                 |               |                         |               |                     |
| 2.1   | Create GitHub repository                                      | Sara          |       17/09        |      17/09       |      17/09      |     17/09     |            1            |       -       | Completed, on time  |
| 2.2   | Validate the provided FASTA files                             | Laia          |       08/10        |      09/10       |      09/10      |     09/10     |            2            |       -       | Completed, on time  |
| 2.3   | Database search and curation                                  | Laia          |       09/10        |      09/10       |      09/10      |     09/10     |            1            |      2.2      | Completed, on time  |
| 2.4   | Select homologs (_Bacillus subtilis_ + 1 more)                | Laia          |       13/10        |      14/10       |      13/10      |     14/10     |            2            |      2.3      | Completed, on time  |
| 2.5   | Retrieve 3D structures (PDB)                                  | Sara          |       14/10        |      15/10       |        -        |       -       |            2            |      2.3      |      Cancelled      |
| **3** | **Sequence analysis**                                         |               |                    |                  |                 |               |                         |               |                     |
| 3.1   | Pairwise alignment WT (wild-type) vs mutant                   | Laia          |       09/10        |      13/10       |      14/10      |     15/10     |            2            |      2.2      | Completed, +2 days  |
| 3.2   | Pairwise and multiple alignment: human vs homologs            | Sara          |       14/10        |      15/10       |      14/10      |     15/10     |            2            |   2.4, 3.1    | Completed, on time  |
| 3.3   | Conservation analysis and interpretation                      | Sara          |       16/10        |      19/10       |      16/10      |     21/10     |            2            |      3.2      | Completed, +2 days  |
| **4** | **Structural analysis**                                       |               |                    |                  |                 |               |                         |               |                     |
| 4.1   | Analyse WT structure                                          | Sara          |       08/10        |      09/10       |      19/10      |     19/10     |            2            |      2.5      | Completed, +10 days |
| 4.2   | Map mutation onto structure, compare WT (wild-type) vs mutant | Sara          |       13/10        |      14/10       |      17/10      |     19/10     |            2            |   3.1, 4.1    | Completed, +5 days  |
| 4.3   | Structural comparison human vs homologs                       | Sara          |       15/10        |      19/10       |      22/10      |     23/10     |            3            |      4.2      | Completed, +4 days  |
| **5** | **Report writing and final delivery**                         |               |                    |                  |                 |               |                         |               |                     |
| 5.1   | Draft Background / Introduction                               | Sara and Laia |       13/10        |      19/10       |      13/10      |     25/10     |            5            |   1.3, 1.4    | Completed, +6 days  |
| 5.2   | Draft Methods and Results: structure                          | Sara and Laia |       13/10        |      20/10       |      21/10      |     23/10     |            6            |   3.3, 4.3    | Completed, +3 days  |
| 5.3   | Draft Discussion, Conclusions and Abstract                    | Sara and Laia |       16/10        |      22/10       |      22/10      |     26/10     |            5            |      5.2      | Completed, +4 days  |
| 5.4   | Cross-review and format check                                 | Sara and Laia |       22/10        |      23/10       |      22/10      |     26/10     |            2            |      5.3      | Completed, +3 days  |
| 5.5   | Final delivery: final Gantt and gap analysis                  | Sara and Laia |       21/10        |      23/10       |      21/10      |     26/10     |            3            |      5.4      | Completed, +3 days  |
| 5.6   | Prepare the oral defense                                      | Sara and Laia |       27/10        |      05/11       |        -        |       -       |            8            |      5.5      |       Pending       |
|       | **Extra task**                                                |               |                    |                  |                 |               |                         |               |                     |
| -     | Gantt chart update                                            | Sara          |       20/10        |      20/10       |      20/10      |     20/10     |            1            |       -       | Completed, on time  |

The delay in the Status column is the real end date minus the planned end date, in calendar days, as in the Gap Analysis of the Project Status Document. Task 2.5 was cancelled: the course instructors said it was not needed and provided a 3D structural comparison (HTML report), which tasks 4.1–4.3 used instead.

## Outputs and completion criteria

| ID    | Task title                                                    | Output                                                          | Accomplished when                                                                                                                                  |
| ----- | ------------------------------------------------------------- | --------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| **1** | **Disease background and literature**                         |                                                                 |                                                                                                                                                    |
| 1.1   | Literature search and reference collection                    | Reference list                                                  | At least 5 reliable sources are saved as PDFs and listed with a short comment on each one.                                                         |
| 1.2   | Disease characterisation (PCT2, UROD)                         | Disease and gene profile                                        | The summary explains the disease, the affected gene and protein, and their role in the heme pathway, with citations.                               |
| 1.3   | Penetrance and inheritance                                    | Inheritance and penetrance overview                             | The summary explains how the disease is inherited and why a carrier may not develop it, with citations.                                            |
| 1.4   | Risk factors                                                  | Risk factor table                                               | The table lists at least 3 risk factors, each with a short explanation and a source.                                                               |
| **2** | **Data retrieval and database work**                          |                                                                 |                                                                                                                                                    |
| 2.1   | Create GitHub repository                                      | GitHub repository                                               | The repository is created and the whole team has access to it.                                                                                     |
| 2.2   | Validate the provided FASTA files                             | Validated FASTA files                                           | All provided FASTA files are verified for sequence integrity, valid headers, and clean formatting.                                                 |
| 2.3   | Database search and curation                                  | Curated gene and protein dataset                                | Target gene and protein datasets are retrieved from UniProt/NCBI, curated, and saved in the repository.                                            |
| 2.4   | Select homologs (_Bacillus subtilis_ + 1 more)                | Homologous sequences list                                       | Homologous sequences for _Bacillus subtilis_ and a second reference (to be determined) species are identified and confirmed.                       |
| 2.5   | Retrieve 3D structures (PDB)                                  | Downloaded PDB structure files                                  | Experimental or predicted 3D PDB structure files are downloaded for wild-type and target variants.                                                 |
| **3** | **Sequence analysis**                                         |                                                                 |                                                                                                                                                    |
| 3.1   | Pairwise alignment WT (wild-type) vs mutant                   | Annotated WT vs Mutant alignment                                | The WT and mutant sequences are aligned and the mutation is identified at DNA and amino acid level and documented.                                 |
| 3.2   | Pairwise and multiple alignment: human vs homologs            | Multiple sequence alignment files                               | Human sequences are aligned with the selected homologs (_Bacillus subtilis_ + 1 more), and the alignment files are saved in the repository.        |
| 3.3   | Conservation analysis and interpretation                      | Conservation plot and summary                                   | Conserved regions and the mutated positions are identified, and their biological meaning is explained with citations.                              |
| **4** | **Structural analysis**                                       |                                                                 |                                                                                                                                                    |
| 4.1   | Analyse WT structure                                          | Annotated 3D structure report & figures                         | The WT structure is successfully analysed and the main structural features relevant to the study are identified and documented.                    |
| 4.2   | Map mutation onto structure, compare WT (wild-type) vs mutant | Structural superposition of WT and mutant                       | The mutation is correctly mapped onto the structure, and the WT and mutant structures are compared to identify relevant structural differences.    |
| 4.3   | Structural comparison human vs homologs                       | Multi-species 3D structural alignment & figures                 | The human structure is compared with the structures of selected homologs, and the main similarities and differences are identified and documented. |
| **5** | **Report writing and final delivery**                         |                                                                 |                                                                                                                                                    |
| 5.1   | Draft Background / Introduction                               | Introduction section draft in report md                         | The disease background, clinical context (PCT2, UROD), and scope are fully written in report md                                                    |
| 5.2   | Draft Methods and Results: structure                          | Methods and Results draft sections with embedded figures        | All methodology protocols, sequence alignment figures, and 3D structural models are documented in report md                                        |
| 5.3   | Draft Discussion, Conclusions and Abstract                    | Complete draft of Abstract, Discussion, and Conclusion sections | Biological implications, limitations, evolutionary insights, and summary abstract are integrated into report md                                    |
| 5.4   | Cross-review and format check                                 | review log & formatted report                                   | Markdown rendering, figure links, and citations are verified.                                                                                      |
| 5.5   | Final delivery: final Gantt and gap analysis                  | Final GitHub commit & Project Status                            | Final Gantt, gap analysis, and repository are committed and live on GitHub.                                                                        |
| 5.6   | Prepare the oral defense                                      | Oral defense                                                    | The oral defense is given on 5 November, based on the final report and the figures in the repository.                                              |
|       | **Extra task**                                                |                                                                 |                                                                                                                                                    |
| -     | Gantt chart update                                            | Updated Gantt chart                                             | The Gantt chart shows the new task owners after Eva and Lídia withdrew.                                                                            |

The second species selected in task 2.4 was _Pan troglodytes_.

## Day-by-day chart

Working days of 5–9, 13–16 and 19–23 October and Monday 26 October 2026 (Monday 12 October was a holiday); M T W R F = Monday to Friday (R = Thursday). 🟦 🟧 🟩 🟨 🟪 = real working day of phases 1 to 5 (same colours as the timeline); ■ = real working day of the extra task; ⬜ = planned day that was not worked (the task was moved or cancelled). Weekend days are not shown, and tasks 2.1 and 5.6 fall outside these weeks.

| ID    | Task title                                                    | M<br>5 | T<br>6 | W<br>7 | R<br>8 | F<br>9 | T<br>13 | W<br>14 | R<br>15 | F<br>16 | M<br>19 | T<br>20 | W<br>21 | R<br>22 | F<br>23 | M<br>26 |
| ----- | ------------------------------------------------------------- | :----: | :----: | :----: | :----: | :----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: |
| **1** | **Disease background and literature**                         |        |        |        |        |        |         |         |         |         |         |         |         |         |         |         |
| 1.1   | Literature search and reference collection                    |   🟦   |   🟦   |   🟦   |   🟦   |        |         |         |         |         |         |         |         |         |         |         |
| 1.2   | Disease characterisation (PCT2, UROD)                         |        |        |        |        |   🟦   |   🟦    |         |         |         |         |         |         |         |         |         |
| 1.3   | Penetrance and inheritance                                    |        |        |        |        |        |   🟦    |   🟦    |   🟦    |         |         |         |         |         |         |         |
| 1.4   | Risk factors                                                  |        |        |        |        |        |         |         |         |   🟦    |   🟦    |         |         |         |         |         |
| **2** | **Data retrieval and database work**                          |        |        |        |        |        |         |         |         |         |         |         |         |         |         |         |
| 2.1   | Create GitHub repository                                      |        |        |        |        |        |         |         |         |         |         |         |         |         |         |         |
| 2.2   | Validate the provided FASTA files                             |        |        |        |   ⬜   |   🟧   |         |         |         |         |         |         |         |         |         |         |
| 2.3   | Database search and curation                                  |        |        |        |        |   🟧   |         |         |         |         |         |         |         |         |         |         |
| 2.4   | Select homologs (_Bacillus subtilis_ + 1 more)                |        |        |        |        |        |   🟧    |   🟧    |         |         |         |         |         |         |         |         |
| 2.5   | Retrieve 3D structures (PDB)                                  |        |        |        |        |        |         |   ⬜    |   ⬜    |         |         |         |         |         |         |         |
| **3** | **Sequence analysis**                                         |        |        |        |        |        |         |         |         |         |         |         |         |         |         |         |
| 3.1   | Pairwise alignment WT (wild-type) vs mutant                   |        |        |        |        |   ⬜   |   ⬜    |   🟩    |   🟩    |         |         |         |         |         |         |         |
| 3.2   | Pairwise and multiple alignment: human vs homologs            |        |        |        |        |        |         |   🟩    |   🟩    |         |         |         |         |         |         |         |
| 3.3   | Conservation analysis and interpretation                      |        |        |        |        |        |         |         |         |   🟩    |   🟩    |   🟩    |   🟩    |         |         |         |
| **4** | **Structural analysis**                                       |        |        |        |        |        |         |         |         |         |         |         |         |         |         |         |
| 4.1   | Analyse WT structure                                          |        |        |        |   ⬜   |   ⬜   |         |         |         |         |   🟨    |         |         |         |         |         |
| 4.2   | Map mutation onto structure, compare WT (wild-type) vs mutant |        |        |        |        |        |   ⬜    |   ⬜    |         |         |   🟨    |         |         |         |         |         |
| 4.3   | Structural comparison human vs homologs                       |        |        |        |        |        |         |         |   ⬜    |   ⬜    |   ⬜    |         |         |   🟨    |   🟨    |         |
| **5** | **Report writing and final delivery**                         |        |        |        |        |        |         |         |         |         |         |         |         |         |         |         |
| 5.1   | Draft Background / Introduction                               |        |        |        |        |        |   🟪    |   🟪    |   🟪    |   🟪    |   🟪    |   🟪    |   🟪    |   🟪    |   🟪    |         |
| 5.2   | Draft Methods and Results: structure                          |        |        |        |        |        |   ⬜    |   ⬜    |   ⬜    |   ⬜    |   ⬜    |   ⬜    |   🟪    |   🟪    |   🟪    |         |
| 5.3   | Draft Discussion, Conclusions and Abstract                    |        |        |        |        |        |         |         |         |   ⬜    |   ⬜    |   ⬜    |   ⬜    |   🟪    |   🟪    |   🟪    |
| 5.4   | Cross-review and format check                                 |        |        |        |        |        |         |         |         |         |         |         |         |   🟪    |   🟪    |   🟪    |
| 5.5   | Final delivery: final Gantt and gap analysis                  |        |        |        |        |        |         |         |         |         |         |         |   🟪    |   🟪    |   🟪    |   🟪    |
| 5.6   | Prepare the oral defense                                      |        |        |        |        |        |         |         |         |         |         |         |         |         |         |         |
|       | **Extra task**                                                |        |        |        |        |        |         |         |         |         |         |         |         |         |         |         |
| -     | Gantt chart update                                            |        |        |        |        |        |         |         |         |         |         |    ■    |         |         |         |         |

## Risk analysis

### Score calculation

Risk = Likelihood × Impact

| Score | Category |
| :---: | :------: |
|  1–2  |   Low    |
|  3–5  |  Medium  |
|  6–9  |   High   |

### Risks

| Risk                              | Why                                                                                                             | Likelihood | Impact | Score | Category | Contingency                                                                                                                                      | Outcome                                                                                                                                          |
| --------------------------------- | --------------------------------------------------------------------------------------------------------------- | :--------: | :----: | :---: | :------: | ------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| Delays due to compressed schedule | The project has a short timeframe and several tasks depend on previous outputs.                                 |     2      |   3    |   6   |   High   | Organise the tasks so that they run in parallel and check the Gantt every week.                                                                  | Occurred: the project was delivered three days late (see the Gap Analysis in the Project Status Document). The Gantt chart was updated on 20/10. |
| Problems with GitHub              | The final report and project files depend on the repository being accessible and correctly maintained.          |     3      |   1    |   3   |  Medium  | Keep a backup copy of all the files on our computers and share a document with the project information, so that nothing is lost if GitHub fails. | Did not occur.                                                                                                                                   |
| Unreliable sources or databases   | Biological information may differ between sources or some databases may contain incomplete or outdated records. |     1      |   3    |   3   |  Medium  | Search only in scientific sources, such as PubMed and curated databases like UniProt, and check each key fact in at least two sources.           | Did not occur.                                                                                                                                   |
| Team members leaving the project  | -                                                                                                               |     1      |   3    |   3   |  Medium  | Laia and Sara took over the tasks of Eva and Lídia, and the Gantt chart was updated on 20/10.                                                    | Occurred: not foreseen in the plan (see the Gap Analysis in the Project Status Document).                                                        |
