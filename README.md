# pilon-correct

Corrects PacBio assemblies using Illumina short-reads

##Author

Jason Kwong (@kwongjc)

##Dependencies

* pilon - [https://github.com/broadinstitute/pilon](https://github.com/broadinstitute/pilon)  
* bwa - [https://github.com/lh3/bwa](https://github.com/lh3/bwa)  
* samtools - [https://github.com/samtools/samtools](https://github.com/samtools/samtools)  

##Usage

```
$ pilon-correct -h
Name:
  pilon-correct
Corrects assemblies with Illumina reads
Author:
  Jason Kwong <jason.kwong@unimelb.edu.au>
Usage:
  pilon-correct [options] ref.fasta R1.fq.gz R2.fq.gz
Parameters:
  ref.fasta      Input genome to correct in FASTA format
Options:
  -h             Show this help
  -o PREFIX      Output prefix (default='pilon')
  -d FLOAT       Minimum evidence to call SNPs/indels (default=0.8)
  -t CPUS        Number of threads to be used (default=16)
  -v             Print version
```

##Bugs

Please submit via the [GitHub issues page](https://github.com/kwongj/pilon-correct/issues).  

##Software Licence

[GPLv3](https://github.com/kwongj/pilon-correct/blob/master/LICENSE)
