# Exploring the Effects of Glucogenic Amino Acids on the Multiomic Landscape of Sepsis

This repository contains the R scripts used for the omics data analysis of the article: **Glycolysis regulation via carbohydrate and glucogenic amino acid supply enhances host defense to prevent lethal neonatal sepsis.** The article is published in ***Journal***. DOI: [https://doi.org/xxxx](https://doi.org/xxxx).

[Pharmaco-Omics Lab](https://pharmomicslab.site/) maintains the repository in collaboration with the [Cellular and Molecular Pediatrics (CMP) Lab](https://ivh.ku.dk/english/research/comparative-pediatrics-and-nutrition/cellular-and-molecular-pediatrics/).

Transcriptomics data: GEO accession GSE263512 ([link](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE263512)). Metabolomics data: Available from the supplementary data of the article ([link](https://doi.org/xxxx)).

Note:

  - The transcriptomics folder contains code for data processing, differential expression analysis, and pathway analysis. The pipeline has been developed and customized mainly based on [`DESeq2`](https://www.bioconductor.org/packages/release/bioc/vignettes/DESeq2/inst/doc/DESeq2.html) [^1], [^2], and [`clusterProfiler`](https://yulab-smu.top/biomedical-knowledge-mining-book/)[^3] packages.

  - The metabolomics folder includes code associated with data integrity check, data treatment and normalization, exploratory data analysis, and differential analysis. The code has been developed and customized mainly based on [`MetaboAnalystR`](https://www.metaboanalyst.ca/docs/RTutorial.xhtml)[^4] packages.

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

**Authors**. (Year). **Glycolysis regulation via carbohydrate and glucogenic amino acid supply enhances host defense to prevent lethal neonatal sepsis.** *Journal Name*. DOI: [Link to the paper](https://doi.org/xxxx).

```bibtex
@article{yourcitationkey,
  author = {Author1, A. and Author2, B.},
  title = {Glycolysis regulation via carbohydrate and glucogenic amino acid supply enhances host defense to prevent lethal neonatal sepsis.},
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
