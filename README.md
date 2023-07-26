# Orchestrating Hi-C analysis with Bioconductor

This package is used to support the OHCA package demonstration at the Bioconductor Conference 2023. 

## Description

This is a package demonstration for the `OHCA` ecosystem, including the 
following packages : 

- `HiCool`
- `HiCExperiment`
- `HiContacts`
- `fourDNData`

The OHCA book is available [here](https://jserizay.com/OHCA/). 

## Pre-requisites

* Familiarity with the `tidyverse` syntax; 
* Familiarity with the `GenomicRanges` class; 
* Basic understanding of Hi-C principles

For more information on Hi-C experimental approach and principles, 
read [OHCA book first chapter](https://jserizay.com/OHCA/principles.html).

## Time outline

| Activity                     | Time |
|------------------------------|------|
| Introduction to Hi-C         | 10m  |
| OHCA ecosystem               | 10m  |
| Demonstration with real data | 20m  |
| Wrapping up                  | 5m   |

## Docker image:

To quickly use the package Docker image:

```sh
docker run -e PASSWORD=<choose_a_password_for_rstudio> -p 8787:8787 ghcr.io/js2264/ohca
```
Once running, navigate to http://localhost:8787/ and then login with `rstudio`:`yourchosenpassword`. 

