# KJV 1611–1769 Semantic Stability Study

Reproducibility package for a human-in-the-loop embedding study of semantic stability and textual drift between the King James Version 1611 and 1769 editions.

## Study Overview

This repository supports the study *Semantic Stability in the King James Bible: Comparing the 1611 and 1769 Editions*. The study evaluates 31,102 structurally aligned shared-canon text units using `mxbai-embed-large` embeddings, cosine distance, robust thresholding, Monte Carlo permutation baselines, and human-in-the-loop annotation.

The repository provides the generated study outputs, figures, architecture documents, notebook materials, and reproducibility metadata used to audit and reproduce the reported manuscript findings.

## Repository Contents

```text
architecture/    Polished study design and methodology artifacts
data/            Machine-readable InterLink study outputs
figures/         Final figures used in the manuscript
manifest/        Study run manifest and output manifest files
manuscript/      Final manuscript DOCX/PDF when available
notebooks/       Validation, figure generation, table-data, EDA, and paper-note notebook(s)
```

## Data Organization

```text
data/coverage/      Corpus coverage, alignment records, exceptions, and scope registry files
data/drift/         Drift pairs, drift indices, and representation sensitivity outputs
data/thresholds/    Threshold summaries, drift labels, and ranked outlier outputs
data/permutation/   Null-model, stability-gap, and statistical diagnostic outputs
data/hitl/          Annotation, category-count, enrichment, and interpretability outputs
data/exclusive/     KJV 1611 exclusive corpus inventory
```

## Manuscript Tables

Manuscript tables were constructed directly in Microsoft Word from the released machine-readable study outputs. Separate table CSV files are not included. The supporting source artifacts for each table are available in the relevant `data/` subdirectories.

## Reproducibility Notes

The proprietary InterLink Research Platform source code is not included in this repository. Released notebooks and generated outputs are provided to support independent inspection of the reported analyses, reproduction of manuscript figures, and verification of empirical results.

The archived release DOI and version tag should be used when citing the final study package.

## Citation

DOI: forthcoming  
Release tag: forthcoming

## License

This repository uses a dual-license structure.

Code and notebooks are licensed under the MIT License. See `LICENSE`.

Research artifacts, generated study outputs, figures, architecture documentation, manifest files, and manuscript materials are licensed under Creative Commons Attribution 4.0 International (CC BY 4.0). See `LICENSE-DATA.md`.

The proprietary InterLink Research Platform source code is not included in this repository and is not released under either license.
