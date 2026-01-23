# TRGT Workshop
This repository is designed to be launched as [GitHub Codespace](https://docs.github.com/en/codespaces) which serves as a demonstration environment for [PacBio's](https://www.pacb.com/) [Tandem Repeat Genotyper (TRGT) software](https://github.com/PacificBiosciences/trgt).

TRGT takes advantage of PacBio HiFi reads, which are long, accurate, and include 5mC methylation calls at all CpG sites by default.
It gentoypes user-specified tandem repeat locations in mapped HiFi reads and outputs its findings in standard formats.
The results can also be visualised. 

The whole TRGT workflow is demonstrated: raw HiFi reads are mapped against the GRCh38 chromosome 19 assembly, analysed with TRGT, then visualised.

The codespace includes the following software installed via micromamba:
- [pbmm2](https://github.com/PacificBiosciences/pbmm2)
- [samtools](https://github.com/samtools/samtools)
- [bcftools](https://github.com/samtools/bcftools)
- [trgt](https://github.com/PacificBiosciences/trgt)

To instantiate your own codespace using this repository, you'll need to be signed in to a GitHub account.
1. Go to [codespaces](https://github.com/codespaces) in GitHub and select 'New Codespace'
2. In the 'select a repository' dropdown search for the name of this repository - `sholt6/trgt-tutorial`
3. You may like to change Machine Type from 2-core to 4-core
4. Click 'Create Codespace'

Note that the codespace will take a few minutes to set up, and will be automatically deleted after a few days of inactivity.
