# How to (code)  
Useful resources for bioinformatics  

## Useful R packages  

### Gene ontology, GSEA and pathway analysis 
[clusterProfiler](https://bioconductor.org/packages/release/bioc/html/clusterProfiler.html): GE, GSEA and pathway analysis in R  


### Graphics
[Paletter](https://github.com/EmilHvitfeldt/paletteer): a comprehensive collection of color palettes in R with unified interface  
[ComplexHeatmap](https://www.bioconductor.org/packages/release/bioc/html/ComplexHeatmap.html): powerful tool for creating beautiful heatmaps in R  
[Pathwork](https://patchwork.data-imaginist.com): R package to quickly compose multiple plots together (easier than `ggarrange`, but less customisable).   
[ggvenn](https://github.com/yanlinlin82/ggvenn): Venn Diagrams in R using `ggplot` syntax.  
[ggpubr](http://www.sthda.com/english/articles/24-ggpubr-publication-ready-plots/): R package to generate clean, publication ready plots with stats  
[drawCell](https://github.com/svalvaro/drawCell): R package to draw and color cell pictures from [SwissBioPic](https://www.swissbiopics.org)  

## General coding, bioinformatics and statistics  
[An Introduction to Statistical Learning](https://www.statlearning.com): Great introduction to statistics and ML with examples in R, easy to follow.  
[Starting with HPC, general tips](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1009207): Article published in PLOS Computational with usefull skills and general etiquette for using HPC  

## Workflow Management Systems

### Snakemake  
[Snakemake](https://snakemake.readthedocs.io/en/stable/) is a friendly workflow management system. 
It allows for construction of reproducible and automatic data analysis pipelines that can be easily
transferred between different working environments (cluster, cloud environment etc.). It uses Python 
based language.   

#### Tutorials  

**Snakemake & HPC**  
[Consideration for running Snakemake on HPC](https://www.sichong.site/2019/10/17/how-to-run-snakemake-pipeline-on-hpc/)

**Snakemake profiles**   
[Building simple Slurm profile](https://www.sichong.site/2020/02/25/snakemake-and-slurm-how-to-manage-workflow-with-resource-constraint-on-hpc/)  

### NextFlow

**nf-core**  
[Community project of numerous analysis pipelines built using Nextflow.](https://github.com/nf-core)  

