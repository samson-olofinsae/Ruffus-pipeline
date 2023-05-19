# Ruffus-pipeline
Running multiple series in parallel
series a: a.fastq -> a.sam -> a.bam -> a.statistics
series b: b.fastq -> b.sam -> b.bam -> b.statistics
series c: c.fastq -> c.sam -> c.bam -> c.statistics


Explaination:
Here we have a number of DNA sequence files (*.fasta)
mapped to a genome (*.sam), and
compressed (*.bam) before being
summarised statistically (*.statistics)

Note that all of the files follow the same consistent naming scheme.
