# Variant effect predictor (VEP)
Containerized version of VEP. The Docker images are available on Dockerhub at https://hub.docker.com/r/matmu/vep.

## Installation using Singularity

```
singularity build vep.<version>.simg docker://matmu/vep:<version>
```

`<version>` has to be replaced by tag a representing the Ensembl version and the species + version of the reference. The latest available versions are **99-GRCh38** (VEP v99 with cache for reference GRCh38) and **99-GRh37** (VEP v99 and cache for reference GRCh37).

## Run it
