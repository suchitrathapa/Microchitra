
✍️ Concept note

# Metagenomics analysis of bacteria 
![image](https://user-images.githubusercontent.com/83858230/172595226-41571e7d-2e2f-4d0f-a153-76157c838d36.png)

## Background
Metagenomic approach is an easier method of gene analysis in whole samples but it mught get complex sometimes, if the microbial community is huge. This is the best way to study a certain environment in a single analysis. **Therefore, in this study we aim to analyse the aqautic environment performing metagenomic analysis to unravel the microbial diversity of those aquatic settings**.

## Methods
1. *Data acquisition and sequence analysis*
- Data will be acquired via [ENA search](https://www.ebi.ac.uk/ena/browser/) or [NCBI](https://www.ncbi.nlm.nih.gov/sra) for publically available data. 
- Sequence analysis and quality assessment will be done using `FastQC` (Simon, 2010), cutadapt[^1] and MultiQC[^2] tools.

2. *Taxonomic profiling*

- Taxonomic profiling will be done using MetaPhlan2[^3] and visualisation will be done using Krona chart.

3. *Resources for analysis*
```
-Metagenomics data analysis :  https://galaxyproject.eu/index-metagenomics.html

-Tutorial for 16S and shot gun analysis: https://training.galaxyproject.org/training-material/topics/metagenomics/tutorials/general-tutorial/tutorial.html 
```

## References
[^1]: Martin, M. (2011). Cutadapt removes adapter sequences from high-throughput sequencing reads. EMBnet.Journal, 17(1), 10–12. https://doi.org/10.14806/EJ.17.1.200 
[^2]: Truong, D. T., Franzosa, E. A., Tickle, T. L., Scholz, M., Weingart, G., Pasolli, E., Tett, A., Huttenhower, C., & Segata, N. (2015). MetaPhlAn2 for enhanced metagenomic taxonomic profiling. Nature Methods 2015 12:10, 12(10), 902–903. https://doi.org/10.1038/nmeth.3589 
[^3]: Ewels, P., Magnusson, M., Lundin, S., & Käller, M. (2016). MultiQC: summarize analysis results for multiple tools and samples in a single report. Bioinformatics, 32(19), 3047–3048. https://doi.org/10.1093/BIOINFORMATICS/BTW354 

