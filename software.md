---
layout: post
title: Software
image: assets/images/floating_mortarboard_H-500pixels.jpg
nav-menu: true
special: yes
---

<section class="wrapper style5">
<div class="inner">



<h2 id="STITCH"><a href="https://github.com/rwdavies/STITCH">STITCH</a></h2>

<p>STITCH is method for reference panel free low coverage whole genome sequence imputation.  STITCH runs on a set of samples with sequencing reads in BAM format, as well as a list of positions to genotype, and outputs imputed genotypes in VCF format. STITCH works by modelling each chromosome in the set of samples as a mosaic of K unknown founders or ancestral haplotypes. STITCH employs a hidden Markov model, whose parameters are sequentially updated using expectation maximization. Both steps are handled in a read aware fashion done without using external reference haplotype sets.

<p>The method is available at <a href="https://github.com/rwdavies/STITCH">https://github.com/rwdavies/STITCH</a>.
The paper is available <a href="https://www.nature.com/articles/ng.3594">here</a></p>

<h2 id="SEW"><a href="https://github.com/Genomicsplc/SEW">SEW</a></h2>

<p>SEW is a method for reference panel free phasing using long sequencing reads. SEW runs on data from a single sample using sequencing reads in BAM format, as well as a list of positions to phase, and outputs phased genotypes, as well as metrics that are useful for subsequent variant filtration. SEW uses an EM algorithm, starting from an initial guess of the two underlying haplotypes. SEW then iteratively first calculates probabilities for each sequencing read for coming from each of the two haplotypes, and then updates the sequence of the underlying haplotypes using the sequence of the reads and the probabilities the reads came from the two haplotypes.

<p>The method is available at <a href="https://github.com/Genomicsplc/SEW">https://github.com/Genomicsplc/SEW</a>.
The paper is available <a href="https://www.nature.com/articles/s41467-019-09637-5">here</a></p>


