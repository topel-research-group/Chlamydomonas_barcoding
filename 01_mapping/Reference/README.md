# Reference sequence composed of the following concatenated files

1. `Chlamydomonas_reinhardtii.Chlamydomonas_reinhardtii_v5.5.dna_rm.toplevel.fa.gz`
  * Contains all chromosomes and non-chromosomal supercontigs, hard-masked (strain CC-503 cw92 mt+)
2. `NC_001638.fna`
  * Mitochondrial genome (strain CW-15-2)
3. `NC_005353.fna`
  * Plastid genome (should be strain CC-503 cw92 mt+?)
4. `GU814015.fna`
  * Minus mating type (mt-) locus (strain CC-2290)

Bowtie2 index built using Bowtie2 v2.3.4.3

* **Second reference is as above, but using the unmasked `Chlamydomonas_reinhardtii.Chlamydomonas_reinhardtii_v5.5.dna.toplevel.fa.gz` instead**
