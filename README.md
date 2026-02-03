# scRNA-seq Analysis: Stress, Vaccination, and Ghrelin Effects on Mouse Immune Tissues

analyzing single-cell RNA sequencing data from three different experiments looking at how stress, vaccination, and hormones affect immune cells in aged mice (13-14 month old BALB/c females).

- How do stress and hormonal signals affect immune cell function and aging?

---

## Experiments

### 1. Bone Marrow - Stress Effects
- **Samples**: BM1, BM2 (2 pooled samples, 8 mice total)
- **Comparison**: Control vs. Chronic Stress (CVS)
- **Special prep**: CD11b-depleted (enriched for B cells)

### 2. Spleen - Vaccination Under Stress
- **Samples**: SV1, SV2 (2 pooled samples, 16 mice total)
- **Groups**: 
  - Control
  - Stressed
  - Vaccinated
  - Vaccinated + Stressed

### 3. Thymus - Ghrelin Treatment
- **Samples**: GT1, GT2, GT3 (3 pooled samples, 6 mice total)
- **Comparison**: Control vs. Ghrelin treatment

---

## Technology

- **Platform**: 10x Genomics Chromium (3' v3.1)
- **Multiplexing**: TotalSeq™-B Hashtag antibodies
  - 4 hashtags for BM and GT
  - 8 hashtags for SV
- **Antibodies**: CD45 + MHC-I 

---

## Tools Used

**Analysis**:
- Cell Ranger 7.1.0
- R/Seurat (demultiplexing, visualization)
- Python/Scanpy (QC, clustering)
- DoubletDetection

---

## References

Key methods papers:
- 10x Genomics: Zheng et al. 2017, Nat Commun
- Cell Hashing: Stoeckius et al. 2018, Genome Biology
- Seurat: Hao et al. 2021, Cell
- Scanpy: Wolf et al. 2018, Genome Biology

Tutorials I used:

- Seurat vignettes 
- Orchestrating Single-Cell Analysis with Bioconductor (OSCA book)
- Scanpy tutorials
---
**Group and Institution**:  Molecular Pathology Research Group, Institute of Biomedicine and Translational Medicine, University of Tartu
