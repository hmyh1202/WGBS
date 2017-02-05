## Trim_Fq Module of WGBS ##

**Trim_Fq** is used for trimming crop clean fastq file.

### Description: ###
-------
**Trimmomatic**(version 0.36) works with FASTQ files (using phred + 33 or phred + 64 quality scores),Files compressed using either „gzip‟ or „bzip2‟ are supported, and are identified by use of „.gz‟ or „.bz2‟ file extensions.


**USAGE:**

- Trim_Fq:

		{ {{ make -f $PWD/bin/Trim_makefile indir=$PWD Sample=WGBS Adapters=$PWD/TruSeq3-PE.fa Fq_type=33 Trim_Fq & > run.log }} }

### Link: ###
-------
More information about trimmomatic please see: 
[trimmomatic.](http://www.usadellab.org/cms/?page=trimmomatic)

### License ###
-------
- Date: 2017/02/04

- Author: Grace Bisulfite (hmyh1202)
