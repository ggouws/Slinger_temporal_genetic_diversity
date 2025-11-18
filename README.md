# Slinger_temporal_genetic_diversity
<br>

Data and metadata from a publication in which temporal genetic diversity and variation were studied in the slinger sea bream (Chrysoblephus puniceus, Sparidae) along the east coast of South Africa, with temporal sampling spanning six years. The study employed genetic data from nuclear microsatellite markers and Single Nucleotide Polymorphisms (SNPs) from reduced-representation, double-digest restriction-site associated DNA sequencing (ddRAD, specifically the quaddRAD protocol). <br>
<br>
This paper is being submitted to Fisheries Research. Links to the preprints and published article will be inserted here when these are available and if permissible. 

__Single Nucleotide Polymorphism (SNP) data__

The publication provides a more detailed overview of the application of the quaddRAD procedure, library preparation and sequencing. Information given here is primarily aimed at providing context to the data and metadata provided or accessible through this repository and other archives. Raw sequence files were generated through two Illumina MiSeq v3 150-cycle sequencing runs of two libraries. Twelve pools of samples were indexed using modified TruSeq indexes (outer barcodes) and combined into two libraries of six pools each. Each pool contained 12 samples, which were barcoded using a unique combination of modified Illumina adapters (inner barcodes). Raw sequence read files were provided demultiplexed, using the Illumina indexes (outer barcodes). PCR duplicates were identified and removed using the _clone_filter_ module of STACKS version 2.66. Data were then demultiplexed to the level of individual samples, using inner barcodes, with the STACKS module _process_radtags_. These demultiplexed read files for the individual samples have been submitted to the NCBI-SRA (Sequence Read Archive). These were subsequently used for locus reconstruction, variant calling and genotyping.

__Microsatellite data FROM CRABS - NEED TO UPDATE__ <br>
<br>
_Interbasin_crab_genotypes.xlsx_ contains the microsatellite genotype data and other information in the following fields and arrangement. <br>
<br>
Samples are in rows, with loci and metadata in columns. Each locus (diploid) is presented over two columns, with a sized (amplicon fragment size) and called allele in each. Missing data/alleles are indicated by zero (_0_). <br>
<br>
__Sample__ identifies the sample and DNA isolate. <br>
<br>
__Population__ indicates the population sample membership of the individual samples as used in the analyses; these being Orange (River), Great Fish upstream, Great Fish downstream, Sundays upstream and Sundays downstream. <br>
<br>
<br>
Sample metadata <br>
<br>
_Sample_metadata.xlsx_ contains the following information and fields: <br>
<br>
__Sample/Isolate__: The DNA extraction number and sample number by which the sample is referred to in the analyses. <br>
<br>
__Tissue sample number__ : Tissue sample from wich DNA was isolated. Tissue samples are lodged in the Biomaterials Collection of the National Research Foundation - South African Institute for Aquatic Biodiversity <br>
<br>
__Locality__: Collection/sampling locality of each sample. <br>
__Population__: Population sample to which sample was allocated for the analyses. <br>
<br>
__Longitude__: Longitude of the sampling locality. <br>
<br>
__Latitude__: Latitude of the sampling locality. <br>
<br>
__Date__: Date of sampling. <br>
<br>
__16S GenBank accession__: NCBI GenBank accession number for the 16S large subunit rRNA mtDNA sequence derived from the sample. <br>
<br>
__COI GenBank accession__: NCBI GenBank accession number for the cytochrome c oxidase subunit I (COI) mtDNA sequence derived from the sample. <br>
<br>
__Microsatellite genotypes__: Logical operator (TRUE or FALSE) as to whether the individual sample was genotyped at the eight microsatellite loci. <br>
<br>
