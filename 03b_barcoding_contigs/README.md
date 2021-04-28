# Checking barcoding at the contig level, rather than the scaffold level

## All-samples barcodes

No barcodes found when looking at *all* samples

## Mating type-specific barcodes

**Navigation links**

|      Analysis    |                                              Results file                                              |                                              Alleles directory                                              |
|------------------|--------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------|
| mt+ 500bp window | [Chlamy_p21_w500_ContigLevel_mt_plus.txt](mt_plus_only/[Chlamy_p21_w500_ContigLevel_mt_plus.txt)       | [Chlamy_p21_w500_ContigLevel_mt_plus_alleles](mt_plus_only/Chlamy_p21_w500_ContigLevel_mt_plus_alleles/)    |
| mt- 500bp window | [Chlamy_p21_w500_ContigLevel_mt_minus.txt](mt_minus_only/Chlamy_p21_w500_ContigLevel_mt_minus.txt)     | [Chlamy_p21_w500_ContigLevel_mt_minus_alleles](mt_minus_only/Chlamy_p21_w500_ContigLevel_mt_minus_alleles/) |
| mt+ 300bp window | [Chlamy_p21_w300_ContigLevel_mt_plus.txt](w300/mt_plus_only/Chlamy_p21_w300_ContigLevel_mt_plus.txt)   | [Chlamy_p21_w300_ContigLevel_mt_plus_alleles](w300/mt_plus_only/Chlamy_p21_w300_ContigLevel_mt_plus_alleles/)|
| mt- 300bp window | [Chlamy_p21_w300_ContigLevel_mt_minus.txt](w300/mt_minus_only/Chlamy_p21_w300_ContigLevel_mt_minus.txt)| [Chlamy_p21_w300_ContigLevel_mt_minus_alleles](w300/mt_minus_only/Chlamy_p21_w300_ContigLevel_mt_minus_alleles/)|
| mt+ 150bp window (WIP) | [Chlamy_p21_w150_ContigLevel_mt_plus.txt](w150/mt_plus_only/Chlamy_p21_w150_ContigLevel_mt_plus.txt)   | [Chlamy_p21_w150_ContigLevel_mt_plus_alleles](w150/mt_plus_only/Chlamy_p21_w150_ContigLevel_mt_plus_alleles/)|
| mt- 150bp window (WIP) | [Chlamy_p21_w150_ContigLevel_mt_minus.txt](w150/mt_minus_only/Chlamy_p21_w150_ContigLevel_mt_minus.txt)| [Chlamy_p21_w150_ContigLevel_mt_minus_alleles](w150/mt_minus_only/Chlamy_p21_w150_ContigLevel_mt_minus_alleles/)|


### 500bp window

Note - some samples appear identical in IGV when viewed at chromosome level; investigate at contig level

All proteins on NCBI's annotation appear to be labelled as hypothetical, at least on chromosome 1...
* Where are the functional annotations?
* [JBrowse on JGI's website](https://phytozome.jgi.doe.gov/jbrowse/index.html?data=genomes%2FCreinhardtii)

#### [Mating type +](mt_plus_only)

|         Contig locus         | Equivalent chromosome locus |                    Coding region?                    |                                                    Notes                                                     |
|------------------------------|-----------------------------|------------------------------------------------------|--------------------------------------------------------------------------------------------------------------|
| ABCN02000227.1:112400-112910 |    Chr 3:5075744-5076254    | CHLRE_03g181100v5 (hypothetical protein)             | CC-2936 and CC-3065 look identical in IGV...; CC-3076 identical to reference at this locus!                  |
| ABCN02000227.1:112433-112934 |    Chr 3:5075777-5076278    | CHLRE_03g181100v5 (hypothetical protein)             | CC-2936 and CC-3065 look identical in IGV...; CC-3076 identical to reference at this locus!                  |
| ABCN02000839.1:58898-59425   |    Chr 11:58898-59425       | CHLRE_11g467528v5 (calcium channel)                  | CC-2936 and CC-3065 look identical in IGV...; CC-3076 differs from reference by one SNP                      |
| ABCN02000839.1:58963-59474   |    Chr 11:58963-59474       | CHLRE_11g467528v5 (calcium channel)                  | CC-2936 and CC-3065 look identical in IGV...; CC-3076 identical to reference at this locus                   |

#### [Mating type -](mt_minus_only)

|         Contig locus         | Equivalent chromosome locus |                    Coding region?                    |                                                     Notes                                                     |
|------------------------------|-----------------------------|------------------------------------------------------|---------------------------------------------------------------------------------------------------------------|
| ABCN02000738.1:308776-309285 |    Chr 9:3429613-3430122    | CHLRE_09g389134v5 (unknown function (DUF563))        | Looks okay                                                                                                    |
| ABCN02000819.1:276657-277160 |    Chr 10:3895585-3896088   | CHLRE_10g447800v5 (60kDa SS-A/Ro ribonucleoprotein?) | Looks okay; CC-2938 identical to reference at this locus! Imperfect BLAST hits to other loci, conserved_1 BLASTs perfectly elsewhere in the genome |

### 300bp window

#### [Mating type +](w300/mt_plus_only)

|         Contig locus         | Equivalent chromosome locus |                    Coding region?                    |                                                    Notes                                                      |
|------------------------------|-----------------------------|------------------------------------------------------|---------------------------------------------------------------------------------------------------------------|
| ABCN02000056.1:149358-149686 |    Chr 1:5482222-5482550    | CHLRE_01g038600v5 (chloroplast glycerolipid omega-3-fatty acid desaturase) | Looks okay; CC-3065 identical to reference at this locus!                                                     |
| ABCN02000056.1:149442-149751 |    Chr 1:5482306-5482615    | CHLRE_01g038600v5 (chloroplast glycerolipid omega-3-fatty acid desaturase) | Looks okay; CC-3065 identical to reference at this locus!                                                     |
| ABCN02000056.1:402423-402728 |    Chr 1:5735287-5735592    | CHLRE_01g040900v5 (unknown function)                 | Looks okay; CC-3076 identical to reference at this locus! Also, imperfect match from contig to scaffold...    |
| ABCN02000221.1:10820-11124   |    Chr 3:3981328-3981632    | CHLRE_03g171850v5 (unknown function)                 | Looks okay                                                                                                    |
| ABCN02000227.1:105621-105923 |    Chr 3:5068965-5069267    | CHLRE_03g181050v5 (unknown function)                 | Looks okay; CC-3076 identical to reference at this locus!                                                     |
| ABCN02000227.1:112600-112901 |    Chr 3:5075944-5076245    | CHLRE_03g181100v5 (hypothetical protein)             | CC-2936 and CC-3065 look identical in IGV...; CC-3076 identical to reference at this locus!                   |
| ABCN02000227.1:112633-112934 |    Chr 3:5075977-5076278    | CHLRE_03g181100v5 (hypothetical protein)             | CC-2936 and CC-3065 look identical in IGV...; CC-3076 identical to reference at this locus!                   |
| ABCN02000235.1:244568-244879 |    Chr 3:6202804-6203115    | CHLRE_03g192350v5 (Kelch motif?)                     | Looks okay; CC-3076 identical to reference at this locus! Also, IGV displays a variant in conserved region 2 of CC-2343... |
| ABCN02000260.1:154320-154627 |    Chr 3:7273555-7273862    | CHLRE_03g207250v5 (putative glutamine synthetase)    | Looks okay; CC-3086 identical to reference at this locus!                                                     |
| ABCN02000506.1:40914-41230   |    Chr 6:7174112-7174428    | CHLRE_06g297800v5 (hypothetical protein)             | Looks okay; CC-3071 identical to reference at this locus!                                                     |
| ABCN02000839.1:59098-59403   |    Chr 11:59098-59403       | CHLRE_11g467528v5 (calcium channel)                  | CC-2936 and CC-3065 look identical in IGV...; CC-3076 identical to reference at this locus!                   |
| ABCN02000839.1:59130-59458   |    Chr 11:59130-59458       | CHLRE_11g467528v5 (calcium channel)                  | CC-2936 and CC-3065 look identical in IGV...; CC-3076 identical to reference at this locus!                   |
| ABCN02000839.1:59181-59493   |    Chr 11:59181-59493       | CHLRE_11g467528v5 (calcium channel)                  | CC-2936 and CC-3065 look identical in IGV...; CC-3076 identical to reference at this locus!                   |
| ABCN02001352.1:135258-135558 |    Chr 17:1192804-1193104   | CHLRE_17g704850v5 (adenine phosphoribosyltransferase) | Looks okay; CC-3065 identical to reference at this locus!                                                     |
| ABCN02001352.1:135282-135635 |    Chr 17:1192828-1193181   | CHLRE_17g704850v5 (adenine phosphoribosyltransferase) | Looks okay; CC-3065 identical to reference at this locus!                                                     |

#### [Mating type -](w300/mt_minus_only)

|         Contig locus         | Equivalent chromosome locus |                    Coding region?                    |                                                    Notes                                                      |
|------------------------------|-----------------------------|------------------------------------------------------|---------------------------------------------------------------------------------------------------------------|
| ABCN02000136.1:276755-277086 |    Chr 2:5974497-5974828    | CHLRE_02g112150v5 (phospholipase B?)                 | Looks okay; CC-2938 identical to reference at this locus!                                                     |
| ABCN02000738.1:308841-309144 |    Chr 9:3429678-3429981    | CHLRE_09g389134v5 (unknown function (DUF563))        | Looks okay                                                                                                    |
| ABCN02000738.1:308878-309178 |    Chr 9:3429715-3430015    | CHLRE_09g389134v5 (unknown function (DUF563))        | Looks okay                                                                                                    |
| ABCN02000819.1:276767-277068 |    Chr 10:3895695-3895996   | CHLRE_10g447800v5 (60kDa SS-A/Ro ribonucleoprotein?) | Looks okay; CC-2938 identical to reference at this locus! But, a couple of imperfect BLAST hits to other loci |
| ABCN02001069.1:76226-76544   |    Chr 13:4163058-4163376   | CHLRE_13g592050v5 (allantoinase)                     | Looks okay                                                                                                    |
| ABCN02001285.1:148549-148861 |    Chr 16:2930253-2930565   | CHLRE_16g664050v5 (GRAM domain? DUF4782?)            | CC-3059 doesn't look right, almost like a hetero deletion! Also, imperfect match from contig to scaffold...   |
| ABCN02001352.1:142906-143216 |    Chr 17:1200452-1200762   | CHLRE_17g704950v5 (unknown function)                 | Looks okay                                                                                                    |

### 150bp window

#### [Mating type +](w150/mt_plus_only)

WORK IN PROGRESS

#### [Mating type -](w150/mt_minus_only)

WORK IN PROGRESS
