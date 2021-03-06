
# Example data

The example data in `raw.zip` was generated by randomly permuting and renaming
original data. Example CNV data a re-labeled version of the [IGV SEG
example](https://www.broadinstitute.org/software/igv/sites/cancerinformatics.org.igv/files/linked_files/example.seg).
These data are intended for testing and pipeline development.

- version 1 (2015-08-10): original
- version 1.1 (2015-08-12): Added GO, MSIG, CPDB example data
- version 1.2 (2015-08-14): Added CNV data

| directory               | description
|------------------------ | -----------------------------------------------------------------
| `drug_response`         | 10 cell lines x 5 compounds
| `rnaseq_expression`     | 10 cell lines x 100 genes
| `exome_variants`        | 10 cell lines x 10% of filtered variants
| `gene_ontology`         | GO terms for the 100 genes from RNA-seq example data
| `msig_db`               | MSIG database entries for the 100 genes from RNA-seq example data
| `consensus_pathway_db`  | Consensus Pathway database entries for the 100 genes from RNA-seq example data
| `cnv`                   | Copy number variation, in SEG format, for 10 cell lines


`raw.zip` tree:

```
raw
├── [4.0K]  cnv
│   ├── [5.3K]  LineA_1_cnv.seg
│   ├── [7.0K]  LineB_2_cnv.seg
│   ├── [9.1K]  LineC_3_cnv.seg
│   ├── [5.6K]  LineD_4_cnv.seg
│   ├── [5.3K]  LineE_5_cnv.seg
│   ├── [7.1K]  LineF_6_cnv.seg
│   ├── [7.1K]  LineG_7_cnv.seg
│   ├── [3.6K]  LineH_8_cnv.seg
│   ├── [6.4K]  LineI_9_cnv.seg
│   └── [8.0K]  LineJ_10_cnv.seg
├── [4.0K]  consensus_pathway_db
│   └── [438K]  CPDB_pathways_genes.tab
├── [4.0K]  drug_response
│   ├── [2.5K]  s-tum-LineA_1-x1-1.csv
│   ├── [2.4K]  s-tum-LineB_2-x1-1.csv
│   ├── [2.4K]  s-tum-LineC_3-x1-1.csv
│   ├── [2.5K]  s-tum-LineD_4-x1-1.csv
│   ├── [2.5K]  s-tum-LineE_5-x1-1.csv
│   ├── [2.5K]  s-tum-LineF_6-x1-1.csv
│   ├── [2.5K]  s-tum-LineG_7-x1-1.csv
│   ├── [2.5K]  s-tum-LineH_8-x1-1.csv
│   ├── [2.5K]  s-tum-LineI_9-x1-1.csv
│   └── [2.5K]  s-tum-LineJ_10-x1-1.csv
├── [4.0K]  exome_variants
│   ├── [7.6K]  LineA_1_exome_variants.txt
│   ├── [6.2K]  LineB_2_exome_variants.txt
│   ├── [ 12K]  LineC_3_exome_variants.txt
│   ├── [ 11K]  LineD_4_exome_variants.txt
│   ├── [5.4K]  LineE_5_exome_variants.txt
│   ├── [8.8K]  LineF_6_exome_variants.txt
│   ├── [7.3K]  LineG_7_exome_variants.txt
│   ├── [9.9K]  LineH_8_exome_variants.txt
│   ├── [8.5K]  LineI_9_exome_variants.txt
│   └── [7.0K]  LineJ_10_exome_variants.txt
├── [4.0K]  gene_ontology
│   └── [ 17K]  ensembl_go_mapping.tab
├── [4.0K]  metadata
│   ├── [ 406]  sample_ids_drug_response.csv
│   ├── [ 457]  sample_ids_exome_variants.csv
│   └── [ 366]  sample_ids_rnaseq_expression.csv
├── [4.0K]  msig_db
│   └── [ 72K]  c2.cp.v5.0.entrez.gmt
└── [4.0K]  rnaseq_expression
    ├── [1.8K]  LineA_1_counts.csv
    ├── [1.9K]  LineB_2_counts.csv
    ├── [1.8K]  LineC_3_counts.csv
    ├── [1.8K]  LineD_4_counts.csv
    ├── [1.9K]  LineE_5_counts.csv
    ├── [1.8K]  LineF_6_counts.csv
    ├── [1.8K]  LineG_7_counts.csv
    ├── [1.8K]  LineH_8_counts.csv
    ├── [1.8K]  LineI_9_counts.csv
    └── [1.9K]  LineJ_10_counts.csv

8 directories, 46 files
```
