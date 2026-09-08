# HAP2 multi-omics

[![Publication DOI](https://img.shields.io/badge/Cell%20Reports%20Medicine-10.1016%2Fj.xcrm.2026.102919-blue)](https://doi.org/10.1016/j.xcrm.2026.102919)
[![Zenodo DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18768243.svg)](https://doi.org/10.5281/zenodo.18768243)

**Computational integration and longitudinal modelling of host, immune, metabolic and respiratory microbiome data in the HAP2 project.**

This repository is the public-facing computational workspace for **HAP2 multi-omics**. It is intentionally organised around the broader HAP2 project rather than a single publication, so that additional omics layers, validation analyses and modelling workflows can be added over time.

The repository currently documents the computational analyses associated with the first published HAP2 multi-omics study.

## Scientific scope

HAP2 investigates how systemic inflammation reshapes interactions between the host and the respiratory microbiome over time. The computational work integrates longitudinal measurements across multiple biological layers to identify coordinated host–microbiome states, stratify patients and test whether these states generalise across independent cohorts.

Current analytical themes include:

- longitudinal multi-omics integration;
- latent-factor modelling of heterogeneous biological and clinical data;
- respiratory microbiome analysis;
- immune-cell and metabolic state characterisation;
- cross-cohort validation;
- interpretable patient stratification and risk modelling;
- host–microbiome association and concordance analyses.

## Published study

**Sinha D, Petrier M, Martin FP, et al.**  
*Alterations of the host-lung microbiome metasystem in systemic inflammatory response syndrome is associated with secondary pneumonia.*  
**Cell Reports Medicine. 2026;7(8):102919.**  
DOI: [10.1016/j.xcrm.2026.102919](https://doi.org/10.1016/j.xcrm.2026.102919)

### Study in brief

Using longitudinal multi-omic data from patients with systemic inflammatory response syndrome (SIRS), the study identified a dynamic host–respiratory microbiome **metasystem** linking immune-cell trafficking, respiratory anaerobic bacteria and host metabolism. A coordinated metacluster characterised by altered T/B-cell trafficking, anaerobic bacteria, increased tyrosine metabolism and reduced fatty-acid biosynthesis was associated with clinically relevant differences in host–lung microbiome disruption.

The resulting multi-factor stratification distinguished moderate and severe alterations, was associated with pneumonia and mortality, and was evaluated in an independent randomised controlled trial. The analysis further suggested that response to interferon-γ may depend on the underlying host–microbiome state.

## Computational archive and data

The exact computational release and de-identified data associated with the publication are deposited on Zenodo:

**Zenodo DOI:** [10.5281/zenodo.18768243](https://doi.org/10.5281/zenodo.18768243)

The deposited computational files include:

| File | Role |
| --- | --- |
| `MEFISTO_common_features_IBIS_PrevHAP.R` | Cross-cohort longitudinal multi-omics / latent-factor analysis |
| `MEFISTO_model_figures.R` | MEFISTO model summaries and publication-oriented visualisation |
| `fft_risk_train_predict.R` | Interpretable risk-model training and external prediction |
| `microbiome_analysis.R` | Respiratory microbiome analyses |
| `corr_by_effect_metab_micro.R` | Metabolome–microbiome association analyses |
| `procrustes.R` | Cross-domain concordance / Procrustes analyses |
| `mixKernel.R` | Supporting kernel-based analysis utilities |

For direct links to each archived script and its checksum, see [`analysis/published-crm-2026/README.md`](analysis/published-crm-2026/README.md).

**No study data are duplicated in this GitHub repository.** The de-identified archive and normalised data workbook remain hosted on Zenodo. See [`data/README.md`](data/README.md).

## Repository structure

```text
HAP2-multiomics/
├── README.md
├── CITATION.cff
├── analysis/
│   ├── README.md
│   └── published-crm-2026/
│       └── README.md
└── data/
    └── README.md
```

The private working repository contains a substantially larger development history and is deliberately not mirrored here.

## Reproducibility

The Zenodo deposit is the archival source of record for the published computational release. This GitHub repository serves as the maintained, readable project interface and can evolve as further HAP2 analyses become public.

For exact files corresponding to the 2026 publication, use the Zenodo-linked release index above.

## Project direction

HAP2 is broader than the currently published analysis. Future public additions may include deeper metatranscriptomic, microbiome-functional, immune and cross-cohort modelling components while retaining this repository as the main multi-omics project entry point.

## Citation

If you use the published analysis, please cite the Cell Reports Medicine article above. For the archived computational material and de-identified data, also cite the Zenodo record:

> Sinha D. *Alterations of the host-lung microbiome metasystem in systemic inflammatory response syndrome is associated with secondary pneumonia.* Zenodo. 2026. https://doi.org/10.5281/zenodo.18768243

## Contact

**Debajyoti Sinha**  
Nantes Université · Inserm · CHU Nantes  
Computational biology · multi-omics · computational immunology
