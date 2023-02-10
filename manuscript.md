---
title: Discovering epistasis between germline mutator alleles in mice
keywords:
- markdown
- publishing
- manubot
lang: en-US
date-meta: '2023-02-10'
author-meta:
- Thomas A. Sasani
- Kelley Harris
- Aaron R. Quinlan
header-includes: |
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta property="og:type" content="article" />
  <meta name="dc.title" content="Discovering epistasis between germline mutator alleles in mice" />
  <meta name="citation_title" content="Discovering epistasis between germline mutator alleles in mice" />
  <meta property="og:title" content="Discovering epistasis between germline mutator alleles in mice" />
  <meta property="twitter:title" content="Discovering epistasis between germline mutator alleles in mice" />
  <meta name="dc.date" content="2023-02-10" />
  <meta name="citation_publication_date" content="2023-02-10" />
  <meta property="article:published_time" content="2023-02-10" />
  <meta name="dc.modified" content="2023-02-10T18:11:03+00:00" />
  <meta property="article:modified_time" content="2023-02-10T18:11:03+00:00" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="Thomas A. Sasani" />
  <meta name="citation_author_institution" content="Department of Human Genetics, University of Utah" />
  <meta name="citation_author_orcid" content="0000-0003-2317-1374" />
  <meta name="twitter:creator" content="@tomsasani" />
  <meta name="citation_author" content="Kelley Harris" />
  <meta name="citation_author_institution" content="Department of Genome Sciences, University of Washington" />
  <meta name="citation_author_orcid" content="0000-0003-0302-2523" />
  <meta name="twitter:creator" content="@Kelley__Harris" />
  <meta name="citation_author" content="Aaron R. Quinlan" />
  <meta name="citation_author_institution" content="Department of Human Genetics, University of Utah" />
  <meta name="citation_author_institution" content="Department of Biomedical Informatics, University of Utah" />
  <meta name="citation_author_orcid" content="0000-0003-1756-0859" />
  <meta name="twitter:creator" content="@aaronquinlan" />
  <link rel="canonical" href="https://quinlan-lab.github.io/mutator-epistasis-manuscript/" />
  <meta property="og:url" content="https://quinlan-lab.github.io/mutator-epistasis-manuscript/" />
  <meta property="twitter:url" content="https://quinlan-lab.github.io/mutator-epistasis-manuscript/" />
  <meta name="citation_fulltext_html_url" content="https://quinlan-lab.github.io/mutator-epistasis-manuscript/" />
  <meta name="citation_pdf_url" content="https://quinlan-lab.github.io/mutator-epistasis-manuscript/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://quinlan-lab.github.io/mutator-epistasis-manuscript/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://quinlan-lab.github.io/mutator-epistasis-manuscript/v/af281d698c7e09aa5ebd649c46e31412e86026a7/" />
  <meta name="manubot_html_url_versioned" content="https://quinlan-lab.github.io/mutator-epistasis-manuscript/v/af281d698c7e09aa5ebd649c46e31412e86026a7/" />
  <meta name="manubot_pdf_url_versioned" content="https://quinlan-lab.github.io/mutator-epistasis-manuscript/v/af281d698c7e09aa5ebd649c46e31412e86026a7/manuscript.pdf" />
  <meta property="og:type" content="article" />
  <meta property="twitter:card" content="summary_large_image" />
  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />
  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />
  <meta name="theme-color" content="#ad1457" />
  <!-- end Manubot generated metadata -->
bibliography:
- content/manual-references.json
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
manubot-clear-requests-cache: false
...






<small><em>
This manuscript
([permalink](https://quinlan-lab.github.io/mutator-epistasis-manuscript/v/af281d698c7e09aa5ebd649c46e31412e86026a7/))
was automatically generated
from [quinlan-lab/mutator-epistasis-manuscript@af281d6](https://github.com/quinlan-lab/mutator-epistasis-manuscript/tree/af281d698c7e09aa5ebd649c46e31412e86026a7)
on February 10, 2023.
</em></small>



## Authors



+ **Thomas A. Sasani**
  <br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0003-2317-1374](https://orcid.org/0000-0003-2317-1374)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [tomsasani](https://github.com/tomsasani)
    · ![Twitter icon](images/twitter.svg){.inline_icon width=16 height=16}
    [tomsasani](https://twitter.com/tomsasani)
    <br>
  <small>
     Department of Human Genetics, University of Utah
     · Funded by Grant XXXXXXXX
  </small>

+ **Kelley Harris**
  <br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0003-0302-2523](https://orcid.org/0000-0003-0302-2523)
    · ![Twitter icon](images/twitter.svg){.inline_icon width=16 height=16}
    [Kelley__Harris](https://twitter.com/Kelley__Harris)
    <br>
  <small>
     Department of Genome Sciences, University of Washington
  </small>

+ **Aaron R. Quinlan**
  ^[✉](#correspondence)^<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0003-1756-0859](https://orcid.org/0000-0003-1756-0859)
    · ![Twitter icon](images/twitter.svg){.inline_icon width=16 height=16}
    [aaronquinlan](https://twitter.com/aaronquinlan)
    <br>
  <small>
     Department of Human Genetics, University of Utah; Department of Biomedical Informatics, University of Utah
  </small>


::: {#correspondence}
✉ — Correspondence possible via [GitHub Issues](https://github.com/quinlan-lab/mutator-epistasis-manuscript/issues)
or email to
Aaron R. Quinlan \<aquinlan@genetics.utah.edu\>.


:::


## Abstract {.page_break_before}

Maintaining genome integrity in the mammalian germline is essential and enormously complex. Hundreds of proteins comprise pathways involved in DNA replication, and hundreds more are mobilized to repair DNA damage. While loss-of-function mutations in any of the genes encoding these proteins might lead to elevated mutation rates, *mutator alleles* have largely eluded detection in mammals. 

DNA replication and repair proteins often recognize particular sequence motifs or excise lesions at specific nucleotides. Thus, we might expect that the spectrum of de novo mutations -- i.e, the frequency of each individual mutation type (C>T, A>G, etc.) -- will differ between genomes that harbor either a mutator or wild-type allele at a given locus. Previously, we used quantitative trait locus (QTL) mapping to discover a mutator allele near the DNA repair gene *Mutyh* that increases the rate of *de novo* C>A germline mutation in a collection of recombinant inbred lines (RILs) known as the BXDs.

In this study, we developed a new method to detect alleles that affect the mutation spectrum in two-parent RILs. By applying this method to mutation data from the BXDs, we confirmed the activity of the germline mutator allele near *Mutyh*, and discovered an additional C>A germline mutator locus on chromosome 6 that overlaps *Ogg1*, a key partner of *Mutyh* in base-excision repair of oxidative DNA damage. 

Strikingly, BXDs with the mutator allele near *Ogg1* do not exhibit elevated rates of C>A germline mutation unless they also possess the mutator allele near *Mutyh*. However, BXDs with both alleles exhibit even higher C>A mutation rates than those with either one alone. 

To our knowledge, these new methods for analyzing mutation spectra reveal the first evidence of epistasis between mammalian germline mutator alleles, and may be applicable to mutation data from humans and other model organisms. 



## Introduction

Maintaining genome integrity in the mammalian germline is essential enormously complex. Hundreds of protein-coding genes contribute to pathways involved in DNA replication, and hundreds more are mobilized in response to damage by exogenous and endogenous mutagens [@PMID:28485537]. Despite this abundance of potential targets, *mutator alleles* that augment the germline mutation rate have largely eluded detection in mammals. 

Germline mutator alleles are difficult to detect for a number of reasons, including the fidelity of germline genome replication and the effects of selection on mutators. On average, humans are born with about 70 to 100 *de novo* germline mutations per diploid genome [@PMID:28959963; @PMID:31549960]; in mice, the number is closer to 20 or 30 [@PMID:31492841]. Moreover, in a population of sufficiently large $N_e$, we would also expect even low-effect mutator alleles to be efficiently selected against. The selection coefficient on a mutator allele is approximately $2s \Delta U$ [@PMID:27739533], where *s* is the mean selective coefficient on a new deleterious mutation and $\Delta U$ is the excess number of new deleterious mutations caused by the mutator allele; the product of $s$ and $\Delta U$ is multiplied by 2 to account for the expected number of generations for which mutator will be linked to the excess mutations it causes. Given the low germline *de novo* mutation rate in mamalian genomes and the strength of selection on a potential mutator allele, we would likely require a very large number of offspring, as well as an environment that attenuates the effects of selection, in order to detect the effects of a germline mutator allele.

In general, we would expect haplotypes that carry mutator alleles at a particular locus to carry an excess of total germline mutations, compared to those that harbor wild-type alleles. However, protein-coding genes involved in DNA replication and repair often recognize particular sequence motifs or excise lesions at specific nucleotides [@PMID:28485537]. Thus, we might also expect that the spectrum of de novo mutations -- i.e, the frequency of each individual mutation type (C>T, A>G, etc.) -- will differ between genomes that harbor either a mutator or wild-type allele at a given locus.

Previously, we discovered a germline mutator allele in mice by analyzing whole-genome sequencing data from 152 recombinant inbred lines (RILs). These RILs, known as the **B**X**D**s [@PMID:33472028], were derived from C57**B**L/6J and **D**BA/2J, two laboratory strains that exhibit significant differences in their germline mutation spectra [@PMID:30753674]. Following either F2 or advanced intercrosses of the parental strains, the BXDs were inbred by brother-sister mating for up to 180 generations, attenuating the effects of natural selection on both standing and new variation. Over the course of inbreeding, each BXD therefore accumulated hundreds or thousands of germline *de novo* mutations on a linear mosaic of the parental haplotypes that was almostly completely homozygous. Previously, we identified up to 2,000 germline de novo mutations in each line and used quantitative trait locus (QTL) mapping to identify a locus on chromosome 4 that was strongly associated with the C>A germline mutation rate [@PMID:35545679]. The QTL overlapped *Mutyh*, which encodes a protein that normally prevents C>A mutations by repairing oxidative DNA damage [@PMID:17581577], and we hypothesized that missense mutations in *Mutyh* were responsible for a 50% increase in the C>A mutation rate between BXDs with either parental haplotype at the QTL.

In this study, we developed a new method to detect alleles that affect the mutation spectrum in two-parent RILs, and applied it to previously generated mutation data from the BXDs. We assessed its power to detect candidate mutator alleles, and discovered compelling evidence of epistasis between two germline mutator alleles that augment the C>A germline mutation rate.


## Materials and Methods

### Identifying *de novo* germline mutations in the BXD RILs

The BXD resource currently comprises a total of 152 recombinant inbred lines (RILs). RILs were derived from either F2 or advanced intercross lines (AILs), and subsequently inbred by brother-sister mating for up to 180 generations [@PMID:33472028]. Previously, we analyzed whole-genome sequencing data from the BXDs and identified *de novo* germline mutations in each line [@PMID:35545679]. A detailed description of the methods used for DNA extraction, sequencing, alignment, and variant processing, as well as the characteristics of the high-quality *de novo* mutations, are available in the previous manuscript [@PMID:35545679].

Briefly, we aligned paired-end Illumina sequencing data to the GRCm38/mm10 reference genome using the 10X LongRanger software (v2.1.6; Lariat approach), called single-nucleotide variants using GATK version (v3.8-1-0-gf15c1c3ef) [@PMID:21478889], and identified mutations in each BXD that were absent from all other RILs, as well as from the C57BL/6J and DBA/2J parents. We required each private variant to be meet the following criteria: 

* genotyped as either homozygous or heterozygous for the alternate allele, with at least 90% of sequencing reads supporting the alternate allele

* supported by at least 10 sequencing reads

* Phred-scaled genotype quality of at least 20 

* must not overlap regions of the genome annotated as segmental duplications or simple repeats in GRCm38/mm10

* must occur on a parental haplotype that was inherited by at least one other BXD at the same locus, and must be homozygous for the reference allele in those BXDs

### A new approach to discover germline mutator alleles

Using the existing catalog of *de novo* germline mutations in the BXDs, we developed a new approach to discover loci that affect the germline *de novo* mutation spectrum in biparental RILs (Figure @fig:figure-one).

![**Overview of inter-haplotype distance method for discovering mutator alleles** a) A population of four haplotypes have each been genotyped at three informative markers, and each harbors a set of private *de novo* germline mutations. At each informative marker, we compute an aggregate *de novo* germline mutation spectrum in the haplotypes that carry either parental allele, and calculate the cosine distance between the two aggregate spectra. b) We repeat the process outlined in a) for every informative marker along the genome. c) To assess the significance of any cosine distance peaks in b), we perform a permuation test by shuffling the labels associated with each haplotype's mutation data and running a genome-wide distance scan. In each of $N$ permutations, we record the maximum distance encountered at any locus in the distance scan. Finally, we calculate the $1 - p$ percentile of that maximum distance distribution to obtain a genome-wide cosine distance threshold at the specified value of $p$.](images/Figure%201.svg){#fig:figure-one width=7in .white}. 

We assume that a collection of haplotypes have been genotyped at informative markers, and that *de novo* germline mutations have been identified on each haplotype.

We iterate over each informative marker and divide the haplotypes into two groups based on the parental allele that they inherited. We then compute a $k$-mer mutation spectrum using the aggregate mutation counts in each haplotype group. The $k$-mer mutation spectrum contains the frequency of every possible $k$-mer mutation type in a collection of mutations, and can be represented as a vector of size $6 \times 4^{k - 1}$ after collapsing by strand complement. For example, the $1$-mer mutation spectrum is 6-element vector that contains the frequencies of C>T, C>G, C>A, A>G, A>T, and A>C mutations.

At each locus, we compute the cosine distance between the aggregate mutation spectra of haplotypes with either parental allele. The cosine distance between two vectors $\mathbf{A}$ and $\mathbf{B}$ is defined as 

$$D_C = 1 - \frac{\mathbf{A} \cdot \mathbf{B}}{||\mathbf{A}|| \ ||\mathbf{B}||}$$

where $||\mathbf{A}||$ and $||\mathbf{B}||$ are the $L_2$ norms of $\mathbf{A}$ and $\mathbf{B}$, respectively. The cosine distance metric has a number of favorable properties for comparing mutation spectra. Since cosine distance does not take the magnitude of vectors into account, it can be used to compare two spectra with unequal total mutation counts. Additionally, by calculating the cosine distance between mutation *spectra*, we avoid the need to perform separate comparisons of mutation counts at each individual $k$-mer mutation type.

We use permutation tests to establish genome-wide cosine distance thresholds. In each of $N$ permutation trials, we randomly shuffle the per-haplotype mutation data such that haplotype labels no longer correspond to the correct mutation counts. Using the shuffled mutation data, we perform a genome-wide distance scan as described above, and record the maximum distance observed at any locus. After $N$ permutations (usually 1,000 or 10,000), we compute the $1 - p$ percentile of the maximum distance distribution, and use that percentile value as a genome-wide significance threshold (for example, at $p = 0.05$).

### Simulations to assess the power of the inter-haplotype distance approach

We performed a series of simple simulations to estimate our power to detect alleles that affect the germline mutation spectrum in biparental RILs.

First, we simulate the $k$-mer mutation spectrum in a population of $H$ haplotypes. We assume that 50% of the haplotypes are under the effects of a mutator allele, which increases the mutation rate of a particular mutation type(s) by an effect size $E$. We simulate $M$ mutations on each haplotype by taking draws from a Poisson distribution as follows:

If we are simulating the 1-mer mutation spectrum, we first define a vector of mutation probabilities:

$$\mathbf{P} = \left( 0.4, \ 0.1, \ 0.075, \ 0.075, \ 0.075, \ 0.275 \right)$$

These probabilities sum to 1 and roughly correspond to the expected frequencies of C>T, C>A, C>G, A>T, A>C, and A>G *de novo* germline mutations in mice, respectively [@PMID:31492841].

If we are simulating the 3-mer mutation spectrum, we define a vector of mutation probabilities of length 96, and assign every 3-mer mutation type a value of $\frac{\mathbf{P}_b}{16}$, where $\mathbf{P}_b$ is the probability of the “base” mutation type associated with the 3-mer mutation type. In other words, each of the NCN>NTN 3-mer mutation types would be assigned a mutation probability of $\frac{0.4}{16} = 0.025$.

To simulate the mutation spectrum on each wild-type haplotype, we define a vector of lambda values by scaling the mutation probabilities by the number of mutations we wish to simulate: 

$$\lambda = \mathbf{P}M$$

and take a Poisson draw from this vector of lambda values. 

To simulate the mutation spectrum on each mutator haplotype, we multiply the mutation probability of a particular mutation type (or multiple mutation types) $\mathbf{P}_n$ by the mutator effect size $E$. When $k = 1$, we only augment the effect size of one mutation type at a time, but when $k = 3$, we augment a fraction (25%, 50%, or 100%) of the 3-mer mutation types associated with a single “base” mutation type. Then, we define the vector of lambda values by scaling the mutation probabilities by $M$ and take a Poisson draw from that vector on each haplotype.

After generating “mutator” and “wild-type” haplotypes, we randomly shuffle the simulated haplotypes $N = 10,000$ times and compute the cosine distance between wild-type and mutator haplotypes each time. If fewer than 5% of the $N$ permutations produces a cosine distance greater than or equal to the cosine distance between the "true" wild-type and mutator haplotypes, we say that the approach succesfully identified the mutator allele. For every combination of simulation parameters ($H$, $M$, $E$, and so on) we perform 100 trials and record the number of trials in which we successfully identify the mutator allele. 

## Results

### Re-identifying the mutator allele on chromosome 4 in the BXDs

We first applied our inter-haplotype distance method to 94 BXD RILs [Methods] using the previously described *de novo* germline mutation data [@PMID:35545679]. Reassuringly, we observed a large peak in cosine distance at a locus on chromosome 4 (Figure {@fig:figure-two}A; maximum distance of X at marker ID rsYYYYY; position 116.8 Mbp in mm10 coordinates). 

![**Results of inter-haplotype distance scans in the BXD RILs.** a) Cosine distances between aggregate *de novo* mutation spectra on BXD haplotypes with either *D* (n = X) or *B* (n = Y) alleles at approximately 7,500 informative markers. Distance thresholds at $p = 0.2$ and $p = 0.05$ were calculated by performing 10,000 permutations of the BXD haplotype mutation data. b) Cosine distances between aggregate *de novo* mutation spectra on BXD haplotypes with either *D* or *B* alleles at approximately 7,500 informative markers. Only BXDs with *D* haplotypes at marker rsYYYY on chromosome 4 were included in the scan. Distance thresholds at $p = 0.2$ and $p = 0.05$ were calculated by performing 10,000 permutations of the BXD haplotype mutation data. c) Fractions of *de novo* germline mutations in BXDs with either *D* or *B* haplotypes at markers rsXXXX and rsYYYY. Total counts of each mutation type were aggregated in groups of BXDs with either of the four possible haplotype combinations, and fractions of each mutation type were calculated in each group separately. Chi-square tests of independence were used to compare counts of individual mutation types between the D-D and D-B groups of BXDs, as well as between the B-D and B-B groups. d) Fractions of *de novo* germline mutations in Sanger Mouse Genome Project (MGP) strains with either *D* or *B* haplotypes at markers rsXXXX and rsYYYY. Total counts of each mutation type were aggregated in groups of MGP strains with either of the four possible haplotype combinations, and fractions of each mutation type were calculated in each group separately. Chi-square tests of independence were used to compare counts of individual mutation types between the D-D and D-B groups of BXDs, as well as between the B-D and B-B groups.](images/Figure%202.svg "Figure 2"){#fig:figure-two width=8in .white}. 

In a previous analysis, we used quantitative trait locus (QTL) mapping to identify a nearly identical locus on chromosome 4 that was significantly associated with the C>A germline mutation rate in the BXDs [@PMID:35545679]. This locus overlaps 21 protein-coding genes that are annotated by the Gene Ontology as being involved in "DNA repair," but only one of these genes contains non-synonymous differences between the two parental strains: *Mutyh*. *Mutyh* encodes a protein involved in the base-excision repair of 8-oxoguanine (8-oxoG), a DNA lesion caused by oxidative damage, and prevents the accumulation of C>A mutations following DNA replication. As expected, C>A germline mutation rates are nearly 50% higher in BXDs that inherited *D* haplotypes at marker ID rsYYYY than in those that inherited *B* haplotypes.

### An additional germline mutator allele on chromosome 6

After confirming that the inter-haplotype distance method could recover the mutator locus overlapping *Mutyh*, we asked if our approach could identify additional mutator loci in the BXD. To account for the effects of the C>A germline mutator locus near *Mutyh*, we divided the BXD RILs into those with either *D* (n = X) or *B* (n = Y) genotypes at rsYYYYY (the peak marker on chromosome 4), and ran a genome-wide distance scan using each group separately (Figure {@fig:figure-two}B.

Using only the BXDs with *B* haplotypes at the *Mutyh* mutator locus, we did not observe any genome-wide significant peaks. But using the BXDs with *D* haplotypes at the same locus, we identified a cosine distance peak on chromosome 6 ((Figure {@fig:figure-two}B; maximum distance of X at marker rsYYYYY; position 133.2 Mbp in mm10 coordinates). We queried the region underneath this peak and discovered two genes annotated with the Gene Ontology term "DNA repair": *Setmar*, a protein with histone methyltransferase and transposase activity, and remarkably, *Ogg1*. The latter encodes a key member of the base-exision repair response to oxidative DNA damage, a pathway that also includes *Mutyh* and a related gene, *Mlh1*. Both *Setmar* and *Ogg1* harbor nonsynonymous differences between *D* and *B* haplotypes (@tbl:table-one). 

| Gene name | Amino acid change | Position in GRCm38/mm10 coordinates |
|----------|----------|----------|
| *Ogg1* | p.Ala95Thr | chr6: |
| *Setmar* | p.XY | chr6: |
| *Setmar* | p.XY | chr6: |

**Table 1**: Summary of nonsynonymous differences between *D* and *B* haplotypes in DNA repair genes at the mutator locus on chromosome 6. {#tbl:table-one}

### Evidence of epistasis between germline mutator alleles

Strikingly, BXDs with *D* alleles at both mutator loci exhibit even higher C>A germline mutation rates than those with *D* alleles at only one of the two loci. However, BXDs with *D* alleles at the mutator locus on chromosome 6 alone do not exhibit elevate elevated C>A mutation rates, suggesting that the effects of the chromosome 6 mutator locus depend on the presence of a *D* allele at the chromosome 4 locus. 


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>

