# FRiP

Compute Fraction of Reads in Peaks (FRiP) for a ChIP/ATAC seq experiment given the alignment and peak file


usage: frip.py [-h] -b BAM -e BED [-t TEMP]

options:
-h, --help            show this help message and exit

-b BAM, --bam BAM     path to BAM file (only one)

-e BED, --bed BED     path to BED file containing the peaks (only one)

-t TEMP, --temp TEMP  temporal folder (default: /tmp)


__REQUIREMENTS__
- bedtools suite
- samtools suite
