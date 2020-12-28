# blastn-seq

Implementation of nucleotide-nucleotide BLAST (basic local alignment search tool) using [Seq](https://seq-lang.org/). Read more in the [project paper](blastn-seq.pdf).

### Example invocation
Query sequence as a FASTA file: ```seqc -d blast.seq test_sequences/cov_partial.fa test_sequences/cov_complete.fa``` <br/>
Or as a string sequence: ```seqc -d blast.seq CGGCCCCAAGGTTTACCCAATAATACTGCGTCTT test_sequences/cov_complete.fa```
