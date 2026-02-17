# Code

We've developed several freely-available, open-source software
packages and webtools for the analysis of genetic — and more recently,
sleep — data.

## [__Luna__](https://zzz.nyspi.org/luna)

Software for the analysis of sleep signal data, currently focused on
processing EEG signals from EDF files. Includes an R library (lunaR)
and is also available as a Docker image.

## [__PLINK__](https://zzz.nyspi.org/plink)

A toolset for single nucleotide polymorphism (SNP) and copy number
variant (CNV) whole-genome association studies. Includes functions for
data management, QC, summary statistics, association analysis and
IBD/ancestry inference [(Purcell et al., 2007)](http://www.ncbi.nlm.nih.gov/pubmed/17701901).

## [__GPC: Genetic Power Calculator__](https://zzz.nyspi.org/gpc)

Web service for basic power calculations for case/control and
quantitative trait family-based and population-based association
studies, and for QTL linkage studies ([Purcell et al., 2003](http://www.ncbi.nlm.nih.gov/pubmed/12499305) and [Sham et
al., 2000](http://www.ncbi.nlm.nih.gov/pubmed/10762547)).

## [__XHMM__](https://zzz.nyspi.org/xhmm)

Designed to detect copy number variants (CNV) in targetted sequencing
studies by an analysis of read depth data [(Fromer et al.,
2012)](http://www.ncbi.nlm.nih.gov/pubmed/23040492).

## [__INRICH__](https://zzz.nyspi.org/inrich)

Software for gene-set enrichment analysis for GWAS, CNV and other
genome-wide study designs, based on a genomic, interval-based
permutation scheme [(Lee et al., 2012)](http://www.ncbi.nlm.nih.gov/pubmed/22513993).

## [__BGIM__](https://zzz.nyspi.org/bgim)

An introductory online tutorial to twin analysis, this site provides a
collection of modules I created in 2001, designed to offer a gentle
introduction to some of the fundamental quantitative genetic concepts
in twin studies. In addition, some simple descriptions of other
statistical genetic concepts such as linkage disequilibrium and
maximum likelihood estimation can be found by following this the above
link.


## Redundant, unsupported software and scripts

These are provided primarily for historical reasons, contact me
directly to access.

 - [__PLINKSEQ__](https://zzz.nyspi.org/plinkseq) : Designed for the analysis of variation data from next-generation
sequencing studies (VCF-oriented), primarily exome sequencing studies.

 - __Genebook__ is designed to create simple web-based databases that provide
results from genetic studies. Think of a genebook as an interactive
version of a supplementary table in a typical journal article.

 - __famtypes__ A small utility for sanity-checking and summarizing
pedigree files

 - <b>whap</b> A tool for haplotype analysis. whap is a C/C++ program for
haplotype analysis. It can handle SNPs or multiallelic markers;
disease or quantitative traits; unrelated individuals or family-based
samples. In particular, it is possible to test nested models in a
flexible manner that enables various types of conditional analysis
(e.g. whether a particular haplotype can explain all the association
signal at a locus, or whether a particular variant has any effects
independent of the effects of correlated haplotypes). An example
application of whap is described in Curran et al. (2005).

 - <b>L-POP</b> Latent class analysis model for detecting population
stratification. L-POP is a C/C++ program to detect population
stratification in samples of unrelated individuals. It uses an
approach similar in spirit to that used in STRUCTURE, except it is
based on latent class analysis. The method has been described in
Purcell & Sham (2004).

 - __MODEL__ Online tool (currently not operational) for genetic
association analysis. This tool provides a simple interface from which
case/control and TDT analyses can be conducted, for the analysis of
one or more samples simultaneously. A number of genetic models can be
compared (e.g. multiplicative, dominant, etc); genotypic relative
risks and/or population allele frequencies can be equated across
samples or tested for heterogeneity.

 - __LdOOKUP__ a webtool for linakge-disequilibrium aware look-ups into
the PGC and other GWAS summary results.

 - __G x E in twin analysis__ Mx scripts for continuous moderator models
This link provides a collection of Mx (a freely available
model-fitting package developed by Mike Neale, that is commonly used
for modeling genetically-informative family data) scripts that
accompany Purcell (2001)

 - __DeFries-Fulker twin analysis__ Mx scripts for DF analysis in
proband-selected twin samples. This link provides a collection of Mx
scripts that accompany Purcell & Sham (2003)

</u>