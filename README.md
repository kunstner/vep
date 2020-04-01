# Variant effect predictor (VEP)
Containerized version of VEP.

## Installation using Singularity

```
singularity build vep.<version>.simg docker://matmu/vep:<version>
```

The latest available versions are **99-GRCh38** (VEP v99 with cache for reference GRCh38) and **99-GRh37** (VEP v99 and cache for reference GRCh37).

## Run it