# Check attempted primers for 300bp Chlamy analysis

## Summary

With one exception, there are no perfect BLAST hits elsewhere in the genome outside of the desired loci
* There is a single off-target perfect hit for minus2's forward primer
* There are various imperfect hits throughout the genome, but these appear too far apart for off-target amplification

When viewed in IGV, ...
* There are a few instances of what appear to be heterozygotes (in a haploid....)
* One instance of identical-looking alleles between samples
* One instance of particularly low-looking coverage

Running assemblies to verify the results

## mt-

|            Locus             |   Forward 5'-3'   |      Reverse 5'-3'       |  Name  |                BLAST query                 |                              Unique primer BLAST?                              |                IGV?                |
|------------------------------|-------------------|--------------------------|--------|--------------------------------------------|--------------------------------------------------------------------------------|------------------------------------|
| ABCN02000738.1:308841-309144 | GTCACACTGCCCTGGTC | CACCCACCTGTGCGATA        | minus1 | GTCACACTGCCCTGGTCNTATCGCACAGGTGGGTG        | Hits 308847-309136, no other perfect hits, imperfect hits not close together   | CC-3059; odd mappers?              |
| ABCN02000738.1:308878-309178 | ACCTGGTGTCCATCCTG | GCCCGCCTTGTAAGCTG        | minus2 | ACCTGGTGTCCATCCTGNCAGCTTACAAGGCGGGC        | Hits 308878-309174, one perfect forward hit, imperfect hits not close together | CC-3059; odd mappers?              |
| ABCN02001285.1:148549-148861 | ACGCCGGATGCCATACA | TCCGGCAGCAGCTTCAT        | minus3 | ACGCCGGATGCCATACANATGAAGCTGCTGCCGGA        | Hits 148553-148844, no other perfect hits, imperfect hits not close together   | CC-2342; odd mappers?              |
* Note - minus3 didn't work

## mt+

|            Locus             |   Forward 5'-3'   |      Reverse 5'-3'       |  Name  |                BLAST query                 |                              Unique primer BLAST?                              |                IGV?                |
|------------------------------|-------------------|--------------------------|--------|--------------------------------------------|--------------------------------------------------------------------------------|------------------------------------|
| ABCN02000056.1:402423-402728 | TCGCTGCCACACTTCAC | GGTTGGTCCAGCAGTCAG       | plus2  | TCGCTGCCACACTTCACNCTGACTGCTGGACCAACC       | Hits 402425-402722, no other perfect hits, imperfect hits not close together   | CC-2937/3086; odd mappers?         |
| ABCN02000227.1:112633-112934 | CTCCACATGGCCCTTAG | CTGGTGAACCGGAATGT        | plus4  | CTCCACATGGCCCTTAGNACATTCCGGTTCACCAG        | Hits 112635-112931, no other perfect hits, imperfect hits not close together   | CC-2936/3065 identical??           |
| ABCN02000260.1:154320-154627 | CAACGCGGCTGTTGGTC | CGATCGGAGGTTTATATGCGTTTC | plus7  | CAACGCGGCTGTTGGTCNGAAACGCATATAAACCTCCGATCG | Hits 154325-154623, no other perfect hits, imperfect hits not close together   | Low cov in CC-2344, otherwise okay |
