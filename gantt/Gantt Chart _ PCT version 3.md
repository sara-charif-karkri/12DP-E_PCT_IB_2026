# Project Overview & Team

* **Project Name:** Porphyria Cutanea Tarda Type 2 (PCT)
* **General Objective:** The project aims to investigate how changes in gene and protein sequences and structures contribute to the molecular basis of Porphyria Cutanea Tarda Type 2 (PCT), as well as to explore how comparative analysis of these sequences provides insights into the affected biological functions.
* **Specific Objectives:**
  1. Learn what PCT type 2 is and which gene and protein are involved.
  2. Collect the sequences and structures we need: the 4 FASTA files, the database records, at least 2 homologs (including *B. subtilis*) and the 3D structures.
  3. Find the mutation by comparing the WT and mutant sequences, and check if it is conserved in the homologs.
  4. Look at where the mutation is in the 3D structure and compare the WT and mutant proteins.
  5. Write the final report on GitHub with contributions from all four members.
* **Milestones:**
  * **M1:** Gantt chart and risk analysis delivered (9 October)
  * **M2:** Disease background completed (19 October)
  * **M3:** Sequence and structure analyses completed (20 October)
  * **M4:** Final report and repository delivered (23 October)
* **Project Members & Roles:**
  * **Sara Charif Karkri el Abbassi** (Undergraduate Student in Bioinformatics) – Project Manager, Data & Database Specialist and Structural Analyst: Responsible for defining scope, timeline tracking, Gantt chart management, and repository oversight. FASTA validation, database curation, homolog selection, and PDB retrieval. Responsible for analysing the WT structure, mapping mutations onto the structure, comparing WT (wild-type) and mutant structures, and performing structural comparisons between human proteins and their homologs.
  * **Laia Núñez Palma** (Undergraduate Student in Bioinformatics) – Disease & Literature Specialist, Sequence Analyst: Responsible for the biological foundation of the project: literature search and reference management, characterisation of PCT type 2 (UROD gene, protein and heme pathway), and analysis of penetrance, inheritance and risk factors.

---

# Gantt Chart Structure & Data

## Task Specifications Table

| ID | Task Title | Task Owner | Output | Planned Start Date | Planned End Date | Real Start Date | Real End Date | Duration (days) | Predecessor | Accomplished When | PCT of Task Complete |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| **1** | **Disease background and literature** | | | | | | | | | | |
| 1.1 | Literature search and reference collection | Laia | Reference list | 5/10/26 | 8/10/26 | 5/10/26 | 8/10/2026 | 4 | | At least 5 reliable sources are saved as PDFs and listed with a short comment on each one. | 100% |
| 1.2 | Disease characterisation (PCT2, UROD) | Laia | Disease and gene profile | 9/10/26 | 13/10/26 | 9/10/26 | 13/10/26 | 3 | 1.1 | The summary explains the disease, the affected gene and protein, and their role in the heme pathway, with citations. | 100% |
| 1.3 | Penetrance and inheritance | Laia | Inheritance and penetrance overview | 13/10/26 | 15/10/26 | 13/10/26 | 15/10/26 | 3 | 1.1, 1.2 | The summary explains how the disease is inherited and why a carrier may not develop it, with citations. | 100% |
| 1.4 | Risk factors | Laia | Risk factor table | 16/10/26 | 19/10/26 | 16/10/26 | 19/10/26 | 2 | 1.1, 1.2, 1.3 | The table lists at least 3 risk factors, each with a short explanation and a source. | 100% |
| **2** | **Data retrieval and database work** | | | | | | | | | | |
| 2.1 | Validate the provided FASTA files | Laia | Validated FASTA files | 8/10/26 | 9/10/26 | 9/10/26 | 9/10/2026 | 2 | | All provided FASTA files are verified for sequence integrity, valid headers, and clean formatting | 100% |
| 2.2 | Database search and curation | Laia | Curated gene and protein dataset | 9/10/26 | 12/10/26 | 9/10/26 | 9/10/26 | 2 | 2.1 | Target gene and protein datasets are retrieved from UniProt/NCBI, curated, and saved in the repository. | 100% |
| 2.3 | Select homologs (B. subtilis + 1 more) | Laia | Homologous sequences list | 13/10/26 | 14/10/26 | 13/10/26 | 14/10/26 | 2 | 2.2 | Homologous sequences for B. subtilis and a second reference (to be determined) species are identified and confirmed. | 100% |
| 2.4 | Retrieve 3D structures (PDB) | Laia | Downloaded PDB structure files | 14/10/26 | 15/10/26 | 14/10/26 | 15/10/26 | 2 | 2.2 | Experimental or predicted 3D PDB structure files are downloaded for wild-type and target variants. | 100% |
| **3** | **Sequence analysis** | | | | | | | | | | |
| 3.1 | Pairwise alignment WT (wild-type) vs mutant | Sara | Annotated WT vs Mutant alignment | 9/10/26 | 13/10/26 | 14/10/26 | 15/10/26 | 3 | 2.1 | The WT and mutant sequences are aligned and the mutation is identified at DNA and amino acid level and documented | 100% |
| 3.2 | Pairwise and multiple alignment: human vs homologs | Sara | Multiple sequence alignment files | 14/10/26 | 15/10/26 | 16/10/26 | 21/10/26 | 2 | 2.3, 3.1 | Human sequences are aligned with the selected homologs (B. subtilis + 1 more), and the alignment files are saved in the repository. | 100% |
| 3.3 | Conservation analysis and interpretation | Sara | Conservation plot and summary | 15/10/26 | 19/10/26 | 20/10/26 | 22/10/26 | 3 | 3.2 | Conserved regions and the mutated positions are identified, and their biological meaning is explained with citations | 100% |
| **4** | **Structural analysis** | | | | | | | | | | |
| 4.1 | Analyse WT structure | Sara | Annotated 3D structure report & figures | 8/10/26 | 9/10/26 | 19/10/26 | 19/10/26 | 2 | 2.4 | The WT structure is successfully analysed and the main structural features relevant to the study are identified and documented. | 100% |
| 4.2 | Map mutation onto structure, compare WT (wild-type) vs mutant | Sara | Structural superposition of WT and mutant | 13/10/26 | 14/10/26 | 17/10/2026 | 19/10/26 | 2 | 4.1 | The mutation is correctly mapped onto the structure, and the WT and mutant structures are compared to identify relevant structural differences. | 100% |
| 4.3 | Structural comparison human vs homologs | Sara | Multi-species 3D structural alignment & figures | 15/10/26 | 19/10/26 | 22/10/26 | 23/10/26 | 3 | 4.2 | The human structure is compared with the structures of selected homologs, and the main similarities and differences are identified and documented | 100% |
| **5** | **Report writing and final delivery** | | | | | | | | | | |
| 5.1 | Draft Background/Introduction | Sara and Laia | Introduction section draft in report.md | 13/10/26 | 19/10/26 | 13/10/26 | 25/10/26 | 5 | 1.4 | The disease background, clinical context (PCT2, UROD), and scope are fully written in report.md | 100% |
| 5.2 | Draft Methods and Results: structure | Sara and Laia | Methods and Results draft sections with embedded figures | 13/10/26 | 20/10/26 | 21/10/26 | 23/10/26 | 6 | 4.3 | All methodology protocols, sequence alignment figures, and 3D structural models are documented in report.md | 100% |
| 5.3 | Draft Discussion, Conclusions and Abstract | Sara and Laia | Complete draft of Abstract, Discussion, and Conclusion sections | 16/10/26 | 22/10/26 | 22/10/2026 | 26/10/2026 | 5 | 5.2 | Biological implications, limitations, evolutionary insights, and summary abstract are integrated into report.md | 100% |
| 5.4 | Cross-review and format check | Sara and Laia | Review log & formatted report | 22/10/26 | 23/10/26 | 23/10/2026 | 26/10/2026 | 2 | 5.3 | Markdown rendering, figure links, and citations are verified. | 100% |
| 5.5 | Final delivery: final Gantt and gap analysis | Sara and Laia | Final GitHub commit & Project Status | 21/10/26 | 23/10/26 | 22/10/2026 | 26/10/2026 | 3 | 5.4 | Final Gantt, gap analysis, and repository are committed and live on GitHub. | 100% |

---

# Risk Analysis

## Scoring Reference
* **1–2:** Low
* **3–5:** Medium
* **6–9:** High
* **Formula:** $\text{Score} = \text{Likelihood} \times \text{Impact}$

| Risk | Why | Likelihood | Impact | Score | Category | Contingency |
| --- | --- | :---: | :---: | :---: | :---: | --- |
| **Delays due to compressed schedule** | The project has a short timeframe and several tasks depend on previous outputs. | 2 | 3 | 6 | High | Organise the tasks so that they run in parallel and check the Gantt every week. |
| **Problems with GitHub** | The final report and project files depend on the repository being accessible and correctly maintained. | 3 | 1 | 3 | Medium | Keep a backup copy of all the files on our computers and share a document with the project information, so that nothing is lost if GitHub fails. |
| **Unreliable sources or databases** | Biological information may differ between sources or some databases may contain incomplete or outdated records. | 1 | 3 | 3 | Medium | Search only in scientific sources, such as PubMed and curated databases like UniProt, and check each key fact in at least two sources. |
| **Citations are not correct** | The report uses information from multiple scientific sources, increasing the possibility of missing or inconsistent references. | 2 | 3 | 6 | High | Review all the citations with a citation website before the final delivery, and check that every reference in the text appears in the reference list. |