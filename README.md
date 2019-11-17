
# Repository is deprecated. Please go to http://github.com/genepi/haplocheck for the latest contamination check based on mtDNA!

# Haplochecker - Detection of Contamination in mtDNA studies

This repository includes the workflow for detection of contamination based on mixtures of mtDNA haplotypes.

## Run Haplochecker

1) Install Cloudgene with the following commands

```
mkdir cloudgene
cd cloudgene
curl -s install.cloudgene.io | bash
```

2) Install the Haplochecker contamination workflow

```
./cloudgene gh mtdna/haplochecker@latest
```

3a) Start the local web service and run
```
./cloudgene server
```
Open your web browser and enter http://localhost:8082. Use `admin` and `admin1978` to login.

3b) Run on the command line 
```
./cloudgene run mtdna-haplochecker --input <bam-folder> --inType bam --output <results-folder>
```


