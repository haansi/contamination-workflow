# Haplochecker - Detection of Contamination in mtDNA studies

This repository includes the workflow for detection of contamination based on mixtures of mtDNA haplotypes.

## Run Haplochecker

1) Install Cloudgene with the following commands

```
mkdir cloudgene
cd cloudgene
curl -s install.cloudgene.io | bash
```

2) Install the contamination workflow

```
./cloudgene gh haansi/contamination-workflow@latest
```

3) Start the local web service
```
./cloudgene server
```

4) Open your web browser and enter http://localhost:8082. Use `admin` and `admin1978` to login.



