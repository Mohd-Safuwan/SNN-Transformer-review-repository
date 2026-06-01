SUPPLEMENTARY MATERIALS
SNN-TRANSFORMER HYBRIDS: A SYSTEMATIC REVIEW

Review title:
Spiking Neural Network-Transformer Hybrids: Architectures, Encoding Strategies,
Learning Mechanisms, and Open Challenges

Last updated: June 2026


OVERVIEW

This repository contains the complete data underlying the systematic literature
review named above. The materials are provided so that every figure, table, and
frequency count in the paper can be traced back to its source data, in line with
PRISMA 2020 and open-science practice.


1. REVIEW AT A GLANCE

+------------------------------+----------------------------------------------------------------------------------------+
| Item                         | Value                                                                                  |
+==============================+========================================================================================+
| Included primary studies     | 118 studies, with stable IDs P001-P118                                                 |
+------------------------------+----------------------------------------------------------------------------------------+
| Search window                | January 2021-April 2026                                                                |
+------------------------------+----------------------------------------------------------------------------------------+
| Databases searched           | IEEE Xplore; ACM Digital Library; Scopus; Web of Science; ScienceDirect                |
+------------------------------+----------------------------------------------------------------------------------------+
| Screening protocol           | PRISMA 2020: identification -> screening -> eligibility -> inclusion                   |
+------------------------------+----------------------------------------------------------------------------------------+
| Quality assessment           | Eligibility & Quality Assessment (E&QA), five criteria scored 1.0, 0.5, or 0.0;        |
|                              | inclusion threshold >= 4.0 / 5.0                                                       |
+------------------------------+----------------------------------------------------------------------------------------+
| Reviewers                    | Two independent reviewers using dual scoring                                           |
+------------------------------+----------------------------------------------------------------------------------------+
| Document types               | Peer-reviewed journal articles, conference papers, and book chapters, plus one         |
|                              | pre-specified quality-gated preprint exception                                         |
+------------------------------+----------------------------------------------------------------------------------------+
| Research questions           | RQ1-RQ5, listed in Section 3                                                           |
+------------------------------+----------------------------------------------------------------------------------------+


2. FILES IN THIS REPOSITORY

2.1 Core record

+-----------------------------------------------+--------------------------------------------------------------------------------+
| File                                          | Purpose / contents                                                             |
+===============================================+================================================================================+
| SNN-Transformer-SLR_Extraction_Table.xlsx     | Master workbook. Contains the 60-field Master Table for all 118 studies, a     |
|                                               | Master Table Description data dictionary, Databases & Years PRISMA screening   |
|                                               | counts, and the two independent E&QA reviewer score sheets.                    |
+-----------------------------------------------+--------------------------------------------------------------------------------+
| Master_Table_Full.pdf                         | Human-readable rendering of the full 60-field Master Table, presented as one   |
|                                               | card per paper.                                                                |
+-----------------------------------------------+--------------------------------------------------------------------------------+
| Master_Table_Condensed.pdf (optional)         | Quick-reference landscape view of the key fields, covering all 118 papers in a |
|                                               | compact format.                                                                |
+-----------------------------------------------+--------------------------------------------------------------------------------+


2.2 Per-research-question analysis files

Each analysis file contains three elements:
  1. the standardized extraction field for the relevant columns;
  2. the controlled vocabulary used to map free-text values to fixed categories;
  3. the frequency counts used to generate the figures and tables in the paper.

+----------------------------------------------+--------------------------------------+------------------------------------------------------+
| File                                         | Research question                    | Supports                                             |
+==============================================+======================================+======================================================+
| Section_5_2_Components.xlsx;                 | RQ2 - architectural design paradigms | Neuron-model categories, attention families,         |
| Section_5_2_SNN_Transformer_Components.xlsx  |                                      | Transformer-backbone distributions, and per-paper    |
|                                              |                                      | component breakdowns.                                |
+----------------------------------------------+--------------------------------------+------------------------------------------------------+
| Section_5_4_Interface_Mechanism.xlsx         | RQ2 - SNN/Transformer integration    | Interface-mechanism taxonomy, Q/K/V handling,        |
|                                              |                                      | membrane shortcuts, and model-scale evidence.        |
+----------------------------------------------+--------------------------------------+------------------------------------------------------+
| Section_5_3_Encoding.xlsx                    | RQ3 - spike encoding and temporal    | Encoding-strategy distribution, controlled           |
|                                              | representation                       | vocabulary, and temporal-resolution summaries.       |
+----------------------------------------------+--------------------------------------+------------------------------------------------------+
| Section_5_5_Experimental_Evidence.xlsx       | RQ5 - experimental evidence          | Standardized dataset names and counts, metric        |
|                                              |                                      | categories, baseline counts, validation splits, and  |
|                                              |                                      | statistical-validation reporting.                    |
+----------------------------------------------+--------------------------------------+------------------------------------------------------+
| Section_5_5_Software_tools__devices_and_reproducibility.xlsx | RQ5 - efficiency, hardware maturity, | Programming languages, frameworks/tools,             |
|                                              | and reproducibility                  | experimental machines/devices, hardware-deployment   |
|                                              |                                      | maturity, code availability, and reproducibility     |
|                                              |                                      | evidence.                                            |
+----------------------------------------------+--------------------------------------+------------------------------------------------------+


Additional note:
RQ1, covering publication patterns and application areas, is answered directly
from the Master Table publication-metadata columns. RQ4, covering learning
mechanisms, is answered directly from the Master Table columns for training
paradigm, training method, surrogate gradient, optimizer, and loss.


2.3 Reference document

+----------------------------+------------------------------------------------------------+
| File                       | Purpose / contents                                         |
+============================+============================================================+
| Extraction_Field_Data.pdf  | Full-text rendering of the per-paper extraction fields for |
|                            | reference.                                                 |
+----------------------------+------------------------------------------------------------+


3. RESEARCH QUESTIONS

RQ1 - What are the publication patterns and application areas of current SNN-Transformer hybrid research?
RQ2 - What architectural design paradigms are used to integrate SNNs with Transformers?
RQ3 - What spike-encoding and temporal-representation strategies are employed?
RQ4 - What learning mechanisms are used to train SNN-Transformer hybrid models?
RQ5 - What experimental evidence, efficiency evidence, hardware-deployment maturity, and remaining challenges characterize the field?


4. NOTE ON PREPRINT INCLUSION

The corpus consists of peer-reviewed journal articles, conference papers, and
book chapters.

As a pre-specified exception, one preprint was retained because it satisfied all
five E&QA criteria, meeting the same >= 4.0 / 5.0 threshold applied to every
study. The preprint was retained because it covered a frontier capability:
billion-parameter spiking language modelling, which was not otherwise
represented in the corpus.

This exception is documented in the paper's methodology and flagged in the
Master Table. Removing the exception does not alter the review's findings.


5. CONVENTIONS

+-------------------------+-----------------------------------------------------------+
| Convention              | Meaning                                                   |
+=========================+===========================================================+
| Paper IDs P001-P118     | Stable study identifiers used throughout the paper and    |
|                         | all supplementary files.                                  |
+-------------------------+-----------------------------------------------------------+
| NR                      | Not reported. This is a deliberate extraction marker, not |
|                         | missing data.                                             |
+-------------------------+-----------------------------------------------------------+
| Controlled vocabulary   | Free-text extraction values were mapped to fixed          |
|                         | categories before frequency counting. The mapping legend  |
|                         | is included in each per-RQ analysis file.                 |
+-------------------------+-----------------------------------------------------------+
| Frequency denominator   | Frequency counts use n = 118 unless a sheet states       |
|                         | otherwise.                                                |
+-------------------------+-----------------------------------------------------------+


6. CITATION

If you use these materials, please cite the associated paper. Full citation
details will be added on publication.


END OF FILE
