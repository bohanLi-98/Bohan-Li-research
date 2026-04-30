# Bohan Li – Research Projects

This repository serves as an index of my research projects in spatial omics and generative modeling.  
All implementations are maintained under laboratory repositories; links and my contributions are summarized below.

---

## Publications

- **Bohan Li†**, et al., Yue Deng*, Qionghai Dai*  
  *Tissue characterization at an enhanced resolution across spatial omics platforms with deep generative model*  
  Nature Communications 15, 6541 (2024)  
  https://doi.org/10.1038/s41467-024-50837-5  

- **Bohan Li**, et al., Feng Bao*, Yue Deng*  
  *Reconstructing isotropic-resolution spatial transcriptomics from serial sections by modeling tissue continuity*  
  Under review at Nature Methods  
  https://doi.org/10.1101/2025.08.15.670472  

- M. Clevenger†, et al., **Bohan Li†**, N. Chevrier*  
  *Whole-body molecular and cellular mapping of the laboratory mouse*  
  Cell (2026)  
  https://doi.org/10.1016/j.cell.2026.03.006  

---

## Projects

### 1. soScope – Cellular-resolution reconstruction from aggregated measurements  
Code: https://github.com/deng-ai-lab/soScope  

**Description**  
A generative framework that models spatial omics observations as aggregated signals from underlying cellular states, enabling reconstruction of higher-resolution molecular landscapes.

**My contributions**
- Designed the variational generative framework for spatial aggregation modeling  
- Implemented the model and training pipeline  
- Integrated multi-modal information (morphology + molecular data) into a unified probabilistic formulation  

---

### 2. isoST – Continuous modeling of spatial organization  
Code: https://github.com/deng-ai-lab/isoST  

**Description**  
A generative framework that models spatial gene expression as a continuous process across tissue depth, enabling reconstruction from sparsely sampled sections.

**My contributions**
- Developed the continuous modeling framework based on stochastic differential equations  
- Designed the learning objective and training strategy  
- Implemented reconstruction and inference pipeline for spatial transcriptomics data  

---

### 3. LABEL – Cross-scale annotation transfer for histology  
Code: https://github.com/chevrierlab/WMST-paper  

**Description**  
A framework for transferring molecular annotations from spatial omics data to large-scale histological images.

**My contributions**
- Developed the LABEL module for annotation transfer  
- Contributed to model design and integration into the whole-body analysis pipeline  
- Participated in large-scale data processing and validation  

---

## Notes

- All code is maintained in corresponding laboratory repositories  
- This page summarizes my contributions across projects for clarity  
