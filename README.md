# Exploring the Effects of Glucogenic Amino Acids on the Multiomic Landscape of Sepsis

This repository contains additional code related to omics data analysis in the paper: **Regulation of glycolysis via carbohydrates and glucogenic amino acids supply to enhance host defense against neonatal bacterial infection.**, published in ***Journal***. DOI: [https://doi.org/xxxx](https://doi.org/xxxx).

The code is maintained by [Pharmaco-Omics Lab](https://pharmomicslab.site/) in the collaboration with [Cellular and Molecular Pediatrics (CMP) Lab](https://ivh.ku.dk/english/research/comparative-pediatrics-and-nutrition/cellular-and-molecular-pediatrics/).

Raw transcriptomics was shared in GEO at [GSE263512](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE263512). Metabolomics was shared as normalized data in the [paper's supplementary files](https://doi.org/xxxx).

## Table of Contents

- [Repository Structure](#repository-structure)
- [Contact Information](#contact-information)
- [License](#license)
- [Citation](#citation)


## Repository Structure

The repository is organized according to experiments. 

- **`Exp1/`**: <ins>Galactose versus Glucose in Sepsis Control</ins>
  - **`liver_transcriptomics/`**
- **`Exp2SE/`**
  - **`liver_transcriptomics/`**
  - **`liver_metabolomics/`**
  - **`plasma_metabolomics/`**
- **`Exp3SE/`**
  - **`liver_transcriptomics/`**
  - **`plasma_metabolomics/`**
- Note:
  - The transcriptomics folder contains code for data inspection, gene differential expression analysis, and pathway analysis. The pipeline has been adapted mainly based on the [`DESeq2`](https://www.bioconductor.org/packages/release/bioc/vignettes/DESeq2/inst/doc/DESeq2.html) [^1], [^2], and [`clusterProfiler`](https://yulab-smu.top/biomedical-knowledge-mining-book/)[^3] packages.

  - The metabolomics folder includes code associated with PCA, fold change, statistical analysis, and differential metabolites-based pathway analysis. The code has been adapted mainly based on [`MetaboAnalystR`](https://www.metaboanalyst.ca/docs/RTutorial.xhtml)[^4] packages.

## Contact Information

For questions or comments regarding this repository, please contact:

1. **Main Contributor:**
- Nguyen Tran Nam Tien
  - Email: namtien.hup(at)gmail(dot)com

2. **Contributors:** Ziyuan Wu, Nguyen Thi Hai Yen.

3. **Principal Investigators:**
- Duc Ninh Nguyen, Ph.D.
- Nguyen Phuoc Long, M.D., Ph.D.
  - Email: bsngphuoclong(at)gmail(dot)com

## License

This repository is licensed under the [MIT License](LICENSE).

## Citation

If you use any part of this repository, please cite the following paper:

**Authors**. (Year). Title. *Journal Name*. DOI: [Link to the paper](https://doi.org/xxxx).

```bibtex
@article{yourcitationkey,
  author = {Author1, A. and Author2, B.},
  title = {Title of the Paper},
  journal = {Journal Name},
  year = {Year},
  volume = {Volume},
  number = {Number},
  pages = {Page numbers},
  doi = {https://doi.org/xxxx},
}
```

[^1]: **Love, M. I., Huber, W., & Anders, S.** (2014). Moderated estimation of fold change and dispersion for RNA-seq data with DESeq2. *Genome biology*, 15, 1–21. [https://doi.org/10.1186/s13059-014-0550-8](https://doi.org/10.1186/s13059-014-0550-8).
        
[^2]: **Zhu, A., Ibrahim, J. G., & Love, M. I.** (2019). Heavy-tailed prior distributions for sequence count data: removing the noise and preserving large differences. *Bioinformatics*, 35(12), 2084–2092. [https://doi.org/10.1093/bioinformatics/bty895](https://doi.org/10.1093/bioinformatics/bty895).

[^3]: **Yu, G., Wang, L. G., Han, Y., & He, Q. Y.** (2012). clusterProfiler: an R package for comparing biological themes among gene clusters. *Omics: a journal of integrative biology*, 16(5), 284–287. [https://doi.org/10.1089/omi.2011.0118](https://doi.org/10.1089/omi.2011.0118).

[^4]: **Pang, Z., Lu, Y., Zhou, G., Hui, F., Xu, L., Viau, C., ... & Xia, J.** (2024). MetaboAnalyst 6.0: towards a unified platform for metabolomics data processing, analysis and interpretation. *Nucleic Acids Research*, gkae253. [https://doi.org/10.1093/nar/gkae253](https://doi.org/10.1093/nar/gkae253).
