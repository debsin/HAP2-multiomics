# Published CRM 2026 computational release

This directory indexes the **exact R scripts deposited on Zenodo** for the Cell Reports Medicine publication:

**Sinha D, Petrier M, Martin FP, et al.**  
*Alterations of the host-lung microbiome metasystem in systemic inflammatory response syndrome is associated with secondary pneumonia.*  
**Cell Reports Medicine. 2026;7(8):102919.**  
DOI: https://doi.org/10.1016/j.xcrm.2026.102919

Archival computational release: https://doi.org/10.5281/zenodo.18768243

## Deposited scripts

| Script | Purpose | Zenodo file | MD5 |
| --- | --- | --- | --- |
| `MEFISTO_common_features_IBIS_PrevHAP.R` | Cross-cohort longitudinal multi-omics / latent-factor analysis | [Download](https://zenodo.org/records/18768243/files/MEFISTO_common_features_IBIS_PrevHAP.R?download=1) | `b165655729ccf489f190890394bfdb4b` |
| `MEFISTO_model_figures.R` | MEFISTO model summaries and figures | [Download](https://zenodo.org/records/18768243/files/MEFISTO_model_figures.R?download=1) | `6d3be25d157ff3c2c673ce314bef9c9a` |
| `fft_risk_train_predict.R` | Interpretable risk-model training and external prediction | [Download](https://zenodo.org/records/18768243/files/fft_risk_train_predict.R?download=1) | `7a461f5ab0157f92072424cf58e0ecbb` |
| `microbiome_analysis.R` | Respiratory microbiome analyses | [Download](https://zenodo.org/records/18768243/files/microbiome_analysis.R?download=1) | `0669e8e824e5e02cc3ed615df02a3efe` |
| `corr_by_effect_metab_micro.R` | Metabolome–microbiome association analyses | [Download](https://zenodo.org/records/18768243/files/corr_by_effect_metab_micro.R?download=1) | `2f71ee16c4d385e87d78a5696633d1d4` |
| `procrustes.R` | Cross-domain concordance / Procrustes analyses | [Download](https://zenodo.org/records/18768243/files/procrustes.R?download=1) | `6452882626706d9193167d8484a0421c` |
| `mixKernel.R` | Supporting kernel-based utilities | [Download](https://zenodo.org/records/18768243/files/mixKernel.R?download=1) | `9cd0231b672a6bf0d2f2f52cb58ff082` |

## Why the code is linked rather than duplicated here

The private HAP development repository has continued to evolve after the archived publication release. Some current working scripts differ materially from the deposited files. Linking the exact Zenodo artifacts prevents ambiguity about which code corresponds to the published analysis.

Future public HAP2 analyses can be added directly to this GitHub repository once they are curated for release.

## Data policy

No study data are mirrored in this GitHub repository. The de-identified archive and normalised workbook remain on Zenodo under the publication record.
