# seqMUMmer
Reimplementation of the original MUMmer algorithm in Seq. **MUMmer** is a whole genome aligner that uses a suffix tree data structure to efficiently find maximally unique matching (MUM) regions between two input sequences. This aligner is designed for use on highly similar genomes.

Requires the Seq programming language. Download Seq [here](https://seq-lang.org).

### Running seqMUMmer
Use the following to run: `seqc seqMUMmer.seq <reference.FASTA> <query.FASTA> <prefix> [options]`
* reference.FASTA: path to FASTA file
* query.FASTA: path to FASTA file
* prefix: string that is used in naming output files

#### Options
* -n: use for case insensitivity
* -l int: to set minimum match length
* -r: use the reverse complement of query sequence
* -mum: use to only output MUMs 
* -help: for information on running seqMUMmer
