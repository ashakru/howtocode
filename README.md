# How to (code)  
Useful resources for bioinformatics  

## General coding, bioinformatics and statistics  

### First steps into coding  
[Amazing collection of must-know R tutorials](https://posit.cloud/learn/recipes)  
[Basic command line introduction](https://swcarpentry.github.io/shell-novice/)   
[Command line cheat sheet](https://adibro.github.io/Data-Science-Resources/Cheat-Sheets/CL-Git/Command-Line_Cheat-Sheet.pdf)  
[EMBL Biostatistic course](https://www.ebi.ac.uk/training/online/courses/biostatistics-introduction/)  
[EMBL Overview of methods in bioinformatics](https://www.ebi.ac.uk/training/online/courses/methods-in-bioinformatics/#vf-tabs__section--overview)  
[EMBL Finding and using publicly available data](https://www.ebi.ac.uk/training/online/courses/finding-using-public-data/#vf-tabs__section--overview)    
[An Introduction to Statistical Learning](https://www.statlearning.com): Great introduction to statistics and ML with examples in R, easy to follow.  
[Starting with HPC, general tips](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1009207): Article published in PLOS Computational with usefull skills and general etiquette for using High Performance Computing (HPC)  
[Git Tutorial For Dummies](https://www.youtube.com/watch?v=mJ-qvsxPHpY)  
[Another GitHub intro](https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners)  
[Tidyverse style guide](https://style.tidyverse.org/): How to keep your code clean   
[R for Data Science](https://r4ds.hadley.nz/): classic book from Hadley Wickham on using R for general data analysis   
[ggplot2: Elegant Graphics for Data Analysis](https://ggplot2-book.org): another Wickham's classic on data visualisation   
[Machine Learning courses from Google](https://developers.google.com/machine-learning): intoduction to ML    

**Michael Love's EDX courses**  
A series of [free EDX courses](https://www.edx.org/es/bio/michael-love) (unless you want to pay for the certificate - completely useless, if you ask me).  
A full data science and genomics course path is as follows:  
1. [Statistics and R](https://www.edx.org/learn/r-programming/harvard-university-statistics-and-r)
2. [Linear models and matrix algebra](https://www.edx.org/learn/linear-algebra/harvard-university-introduction-to-linear-models-and-matrix-algebra)
3. [Statistical inference and modeling for high-throughput experiments](https://www.edx.org/learn/statistics/harvard-university-statistical-inference-and-modeling-for-high-throughput-experiments)
4. [High-Dimensional Data Analysis](https://www.edx.org/learn/data-analysis/harvard-university-high-dimensional-data-analysis)
5. [Introduction to Bioconductor](https://www.edx.org/learn/data-science/harvard-university-introduction-to-bioconductor)
6. [Case Studies in Functional Genomics](https://www.edx.org/learn/data-analysis/harvard-university-case-studies-in-functional-genomics)
7. [Advanced Bioconductor](https://www.edx.org/learn/data-analysis/harvard-university-advanced-bioconductor)

After you amass some super basic coding skills, a problem-based learning is a rewarding way forward, see [Rosalin exercises](https://rosalind.info/problems/list-view/)  
Another practical exercise would be to think about the bioinformatics behind these 2 genomic stories: [story 1](https://pubpeer.com/publications/E61AC72AE0402C6A62A84E36ED2AEA#17), [story 2](https://pubpeer.com/publications/64D40E5556E39B682E80028226D756#17)

[GATK Workshop](https://www.youtube.com/watch?v=sM9cQPWwvn4&list=PLjiXAZO27elDHGlQwfd06r7coiFtpPkvI) - a quick and friendly overview of GATK Best practices and variant calling for genomics   

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

## Workflow Management Systems

### Snakemake  
[Snakemake](https://snakemake.readthedocs.io/en/stable/) is a friendly workflow management system. 
It allows for construction of reproducible and automatic data analysis pipelines that can be easily
transferred between different working environments (cluster, cloud environment etc.). It uses Python 
based language. This is our workflow manager of choice. 

------

### Contributors 
Joanna A. Krupka  
Ilias Mountsopoulos
