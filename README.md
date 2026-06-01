# Supplementary Materials — SNN–Transformer Hybrids: A Systematic Review

This repository contains the complete supplementary data for the systematic literature review:

> **Spiking Neural Network–Transformer Hybrids: Architectures, Encoding Strategies, Learning Mechanisms, and Open Challenges**

The materials are provided to make every figure, table, and frequency count in the paper traceable to its source data, following **PRISMA 2020** and open-science practice.

---

## Review at a Glance

| Item | Details |
|---|---|
| Included primary studies | **118** studies, identified as `P001`–`P118` |
| Search window | **January 2021 – April 2026** |
| Databases searched | IEEE Xplore, ACM Digital Library, Scopus, Web of Science, ScienceDirect |
| Screening protocol | PRISMA 2020: identification → screening → eligibility → inclusion |
| Quality assessment | Eligibility & Quality Assessment (E&QA), using 5 criteria scored `1.0`, `0.5`, or `0.0` |
| Inclusion threshold | **≥ 4.0 / 5.0** |
| Reviewers | Two independent reviewers using dual scoring |
| Document types | Peer-reviewed journal articles, conference papers, book chapters, and one pre-specified quality-gated preprint exception |
| Research questions | RQ1–RQ5 |

---

## Repository Contents

### Core Record

| File | Description |
|---|---|
| [`SNN-Transformer-SLR_Extraction_Table.xlsx`](SNN-Transformer-SLR_Extraction_Table.xlsx) | **Master workbook** containing the 60-field Master Table for all 118 studies, the Master Table Description data dictionary, per-database PRISMA screening counts, and the two independent E&QA reviewer score sheets. |
| [`Master_Table_Full.pdf`](Master_Table_Full.pdf) | Human-readable rendering of the full 60-field Master Table, presented as one card per paper. |
| [`Master_Table_Condensed.pdf`](Master_Table_Condensed.pdf) | Optional quick-reference landscape view of key fields across all 118 papers. |
| [`Extraction_Field_Data.pdf`](Extraction_Field_Data.pdf) | Full-text rendering of the per-paper extraction fields for reference. |

---

### Per-Research-Question Analysis Files

Each analysis workbook contains:

1. the standardized extraction field for the relevant columns;
2. the controlled vocabulary used to map free-text extraction values to fixed categories;
3. the frequency counts used to generate the figures and tables in the paper.

| File | Research question | Supports |
|---|---|---|
| [`Section_5_2_Components.xlsx`](Section_5_2_Components.xlsx) | RQ2 — architectural design paradigms | Neuron-model categories, attention families, and Transformer-backbone distributions. |
| [`Section_5_2_SNN_Transformer_Components.xlsx`](Section_5_2_SNN_Transformer_Components.xlsx) | RQ2 — architectural design paradigms | Per-paper SNN and Transformer component breakdowns. |
| [`Section_5_4_Interface_Mechanism.xlsx`](Section_5_4_Interface_Mechanism.xlsx) | RQ2 — SNN–Transformer integration | Interface-mechanism taxonomy, Q/K/V handling, membrane shortcuts, and model-scale evidence. |
| [`Section_5_3_Encoding.xlsx`](Section_5_3_Encoding.xlsx) | RQ3 — spike encoding and temporal representation | Encoding-strategy distribution, controlled vocabulary, and temporal-resolution summaries. |
| [`Section_5_5_Experimental_Evidence.xlsx`](Section_5_5_Experimental_Evidence.xlsx) | RQ5 — experimental evidence | Standardized dataset names and counts, metric categories, baseline counts, validation splits, and statistical-validation reporting. |
| [`Section_5_5_Software_tools__devices_and_reproducibility.xlsx`](Section_5_5_Software_tools__devices_and_reproducibility.xlsx) | RQ5 — efficiency, hardware maturity, and reproducibility | Programming languages, frameworks/tools, experimental machines/devices, hardware-deployment maturity, code availability, and reproducibility evidence. |

---

## Research Questions

| ID | Question |
|---|---|
| **RQ1** | What are the publication patterns and application areas of current SNN–Transformer hybrid research? |
| **RQ2** | What architectural design paradigms are used to integrate SNNs with Transformers? |
| **RQ3** | What spike-encoding and temporal-representation strategies are employed? |
| **RQ4** | What learning mechanisms are used to train SNN–Transformer hybrid models? |
| **RQ5** | What experimental evidence, efficiency evidence, hardware-deployment maturity, and remaining challenges characterize the field? |

---

## How the Research Questions Are Supported

| Research question | Main data source |
|---|---|
| **RQ1** | Master Table publication metadata and application-area columns. |
| **RQ2** | `Section_5_2_Components.xlsx`, `Section_5_2_SNN_Transformer_Components.xlsx`, and `Section_5_4_Interface_Mechanism.xlsx`. |
| **RQ3** | `Section_5_3_Encoding.xlsx`. |
| **RQ4** | Master Table learning-mechanism columns, including training paradigm, training method, surrogate gradient, optimizer, and loss. |
| **RQ5** | `Section_5_5_Experimental_Evidence.xlsx` and `Section_5_5_Software_tools__devices_and_reproducibility.xlsx`. |

---

## Preprint Inclusion Note

The corpus consists mainly of peer-reviewed journal articles, conference papers, and book chapters.

As a **pre-specified exception**, one preprint was retained because it satisfied all five E&QA criteria, meeting the same **≥ 4.0 / 5.0** threshold applied to every included study. The preprint was included because it covered a frontier capability — **billion-parameter spiking language modelling** — that was not otherwise represented in the corpus.

This exception is documented in the paper methodology and flagged in the Master Table. Removing the exception does not alter the findings of the review.

---

## Data Conventions

| Convention | Meaning |
|---|---|
| `P001`–`P118` | Stable paper IDs used throughout the paper and all supplementary files. |
| `NR` | Not reported. This is a deliberate extraction marker, not missing data. |
| Controlled vocabulary | Free-text extraction values were mapped to fixed categories before frequency counting. Mapping legends are included in each per-RQ analysis workbook. |
| Frequency denominator | Frequency counts use **n = 118** unless a sheet states otherwise. |

---

## Suggested Repository Structure

```text
.
├── README.md
├── SNN-Transformer-SLR_Extraction_Table.xlsx
├── Master_Table_Full.pdf
├── Master_Table_Condensed.pdf
├── Extraction_Field_Data.pdf
├── Section_5_2_Components.xlsx
├── Section_5_2_SNN_Transformer_Components.xlsx
├── Section_5_3_Encoding.xlsx
├── Section_5_4_Interface_Mechanism.xlsx
├── Section_5_5_Experimental_Evidence.xlsx
└── Section_5_5_Software_tools__devices_and_reproducibility.xlsx
```

---

## Reuse and Citation

If you use these supplementary materials, please cite the associated paper:

> Citation details will be added after publication.

---

## License

Please add the repository license here before public release.

Suggested options:

- `CC BY 4.0` for open research data and documentation;
- `MIT` if the repository later includes reusable code;
- another license required by the journal, institution, or funder.

---

## Contact

For questions about the supplementary materials, please contact the corresponding author.

---

## Last Updated

June 2026
