## Termite Gut Urease Genes
This repository contains the gene reference package used for taxonomic classification of ureC (urease) gene sequences in [GraftM](https://github.com/geronimp/graftM), a tool developed by [Boyd et. al 2018](https://academic.oup.com/nar/article/46/10/e59/4942468) for "finding genes of interest in metagenomes, metatranscriptomes, and whole genomes."

#### Description of files:
#### 1. Urec_sequences_FINAL.fa
Fasta file containing publicly-available microbial urease AA sequences downloaded from the [Fungene](http://fungene.cme.msu.edu/) repository. Accession numbers are used as identifiers.

#### 2. Urec_taxonomy_FINAL.txt
Taxonomy (k_kingdom; p_phylum: c_class; o_order; etc.) for each corresponding sequence in a tab-delimited text file.

#### 3. Urease_graftM_package.gpkg
Resulting gene package generated with the "-create" command in GraftM using files 1 & 2 as inputs. Taxonomy for query gene sequences was then assigned by using the "-graft" command in GraftM against this compiled ureC gene package.
