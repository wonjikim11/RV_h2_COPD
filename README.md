# Heritability estimation of COPD related phenotypes using Whole-genome sequence data

***

## Assessing the Contribution of Rare Genetic Variants to Phenotypes of Chronic Obstructive Pulmonary Disease Using Whole-Genome Sequence Data by Wonji Kim et al. (2022)

***

Code file for estimating heritability of COPD realted phenotypes using Whole-genome sequence data

### Required inputs
- Please refer to the GCTA online manual for details (https://yanglab.westlake.edu.cn/software/gcta/#Tutorial)
1. Plink binary dataset: test.bed, test.bim, test.bed
2. phenotype: test_pheno.txt (no header line; columns are family ID, individual ID and phenotypes)
3. qualitative covariates: test_covar.txt (no header line; columns are family ID, individual ID and discrete covariates)
4. quantitative covariates: test_qcovar.txtr (no header line; columns are family ID, individual ID and quantitative covariates)
