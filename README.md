
This repository contains linked-read data simulated using the pipeline in this repository:

> https://github.com/olavurmortensen/linkedsim

This data was generated by running the `linkedsim` pipeline as follows:

```
export RESOURCES=/path/to/resources
nextflow /path/to/linkedsim/main.nf -resume
```

Which produces this output file structure (output from `tree outs/`):

```
outs/
├── sample1
│   ├── sample1_S1_L001_R1_001.fastq.gz
│   └── sample1_S1_L001_R2_001.fastq.gz
├── sample2
│   ├── sample2_S1_L001_R1_001.fastq.gz
│   └── sample2_S1_L001_R2_001.fastq.gz
└── sample3
    ├── sample3_S1_L001_R1_001.fastq.gz
    └── sample3_S1_L001_R2_001.fastq.gz

3 directories, 6 files
```
