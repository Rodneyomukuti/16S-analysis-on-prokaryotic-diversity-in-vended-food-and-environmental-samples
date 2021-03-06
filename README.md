# 16S-analysis-on-prokaryotic-diversity-in-vended-food-and-environmental-samples
Sharon &amp; Rodney 16s analysis

# Project Title

Prokaryotic diversity and potentially pathogenic bacteria in vended foods and environmental samples

# Introduction

Ready-to-eat fast food vending outlets provide a cheap and readily available food. Foodborne diseases have been previously reported in Embu, Kenya, but data on the prokaryotic metagenome in vended foods is scanty. This study aimed to determine the prokaryotic diversity in fruits, vegetable salad, African sausage, chips (potato fries), fried fish, roasted beef (meat), smokies, samosa, soil, and water collected from food vendors and the surrounding environment in Embu Town and Kangaru Market.

# Methodology 

1. Sample collection - fruits, vegetable salad, African sausage, chips (potato fries), fried fish, roasted beef (meat), smokies, samosa, soil, and water
2. DNA extraction - Phenol-chloroform method
3. Amplification and library preparation - 16S rRNA gene variable region (V4-V7)
4. Sequencing (Illumina)
5. Sequence Analysis - QIIME2 
6. Statistical analysis - R (Hierarchical clustering of samples, diversity indices, rarefaction curves, and Venn diagrams)

# Results and discussions
- All samples had significant diversity of of microorganisms
- The microbes varied as depending on the sites and samples
- The highly represented was bacterial phyla (Proteobacteria, Firmicutes and Bacterioides)
- Proteobacteria in has been detected in drinking water, Fimicutes in solid food

# Our input

We were tasked to reproduce the above paper and improve on a few aspects i.e

- The quality of the images
- Finding better pallets
- Improve on the captions
- Improve on general results and discussions (if any)

# Why reproduce this paper?

- To test the methodology used
- To subject the data used to scrutiny

# Methodology

1. Quality Control of the reads
2. Bioinformatic analysis of the asequences using QIIME 2
3. Statistical analysis using R programming language

# Results
1. QC
MultiQC was performed and the results can accessed [here](https://hpc01.icipe.org/rstudio/files/sharod/data/results/multiqc/multiqc_report.html)
The reads had so many duplications and overrepresented sequences due to high adapter content 

2. QIIME
Qiime Pipeline - MBBU

Drawbacks:
Failed to create a Manifest file
Failed to read our Metadata file

3. nf-core ampliseq pipeline
nf-core ampliseq pipeline - github
Drawbacks:
Trimmed out a majority of the sequences as shown in the [multiqc report](https://hpc01.icipe.org/rstudio/files/sharod/data/results/multiqc/multiqc_report.html)

# Challenges faced

1. Poor sequence data
2. Missing details on the pipelines used

