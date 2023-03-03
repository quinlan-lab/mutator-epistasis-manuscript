---
title: Discovering epistasis between germline mutator alleles in mice
keywords:
- markdown
- publishing
- manubot
lang: en-US
date-meta: '2023-03-03'
author-meta:
- Thomas A. Sasani
- Aaron R. Quinlan
- Kelley Harris
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
  <meta name="dc.date" content="2023-03-03" />
  <meta name="citation_publication_date" content="2023-03-03" />
  <meta property="article:published_time" content="2023-03-03" />
  <meta name="dc.modified" content="2023-03-03T15:50:52+00:00" />
  <meta property="article:modified_time" content="2023-03-03T15:50:52+00:00" />
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
  <meta name="citation_author" content="Aaron R. Quinlan" />
  <meta name="citation_author_institution" content="Department of Human Genetics, University of Utah" />
  <meta name="citation_author_institution" content="Department of Biomedical Informatics, University of Utah" />
  <meta name="citation_author_orcid" content="0000-0003-1756-0859" />
  <meta name="twitter:creator" content="@aaronquinlan" />
  <meta name="citation_author" content="Kelley Harris" />
  <meta name="citation_author_institution" content="Department of Genome Sciences, University of Washington" />
  <meta name="citation_author_orcid" content="0000-0003-0302-2523" />
  <meta name="twitter:creator" content="@Kelley__Harris" />
  <link rel="canonical" href="https://quinlan-lab.github.io/mutator-epistasis-manuscript/" />
  <meta property="og:url" content="https://quinlan-lab.github.io/mutator-epistasis-manuscript/" />
  <meta property="twitter:url" content="https://quinlan-lab.github.io/mutator-epistasis-manuscript/" />
  <meta name="citation_fulltext_html_url" content="https://quinlan-lab.github.io/mutator-epistasis-manuscript/" />
  <meta name="citation_pdf_url" content="https://quinlan-lab.github.io/mutator-epistasis-manuscript/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://quinlan-lab.github.io/mutator-epistasis-manuscript/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://quinlan-lab.github.io/mutator-epistasis-manuscript/v/dfeda833e1497b73562cfd736cc081f9e26fae28/" />
  <meta name="manubot_html_url_versioned" content="https://quinlan-lab.github.io/mutator-epistasis-manuscript/v/dfeda833e1497b73562cfd736cc081f9e26fae28/" />
  <meta name="manubot_pdf_url_versioned" content="https://quinlan-lab.github.io/mutator-epistasis-manuscript/v/dfeda833e1497b73562cfd736cc081f9e26fae28/manuscript.pdf" />
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
([permalink](https://quinlan-lab.github.io/mutator-epistasis-manuscript/v/dfeda833e1497b73562cfd736cc081f9e26fae28/))
was automatically generated
from [quinlan-lab/mutator-epistasis-manuscript@dfeda83](https://github.com/quinlan-lab/mutator-epistasis-manuscript/tree/dfeda833e1497b73562cfd736cc081f9e26fae28)
on March 3, 2023.
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

+ **Kelley Harris**
  ^[✉](#correspondence)^<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0003-0302-2523](https://orcid.org/0000-0003-0302-2523)
    · ![Twitter icon](images/twitter.svg){.inline_icon width=16 height=16}
    [Kelley__Harris](https://twitter.com/Kelley__Harris)
    <br>
  <small>
     Department of Genome Sciences, University of Washington
  </small>


::: {#correspondence}
✉ — Correspondence possible via [GitHub Issues](https://github.com/quinlan-lab/mutator-epistasis-manuscript/issues)
or email to
Aaron R. Quinlan \<aquinlan@genetics.utah.edu\>, 
Kelley Harris \<harriske@uw.edu\>.


:::


## Abstract {.page_break_before}

Maintaining genome integrity in the mammalian germline is essential and enormously complex. Hundreds of proteins comprise pathways involved in DNA replication, and hundreds more are mobilized to repair DNA damage [@PMID:28485537]. While loss-of-function mutations in any of the genes encoding these proteins might lead to elevated mutation rates, *mutator alleles* have largely eluded detection in mammals. 

DNA replication and repair proteins often recognize particular sequence motifs or excise lesions at specific nucleotides. Thus, we might expect that the spectrum of de novo mutations &mdash; i.e, the frequency of each individual mutation type (C>T, A>G, etc.) &mdash; will differ between genomes that harbor either a mutator or wild-type allele at a given locus. Previously, we used quantitative trait locus (QTL) mapping to discover a mutator allele near the DNA repair gene *Mutyh* that increases the rate of *de novo* C>A germline mutation in a collection of recombinant inbred lines (RILs) known as the BXDs [@PMID:35545679;@PMID:33472028].

In this study, we developed a new method to detect alleles that affect the mutation spectrum in biparental RILs. By applying this method to mutation data from the BXDs, we confirmed the activity of the germline mutator locus near *Mutyh*, and discovered an additional C>A germline mutator locus on chromosome 6 that overlaps *Ogg1* and *Mbd4*, two DNA glycosylases involved in base-excision repair [@PMID:17581577;@PMID:10097147]. Strikingly, BXDs with mutator alleles on chromosome 6 only exhibit elevated rates of C>A germline mutation if they also possess mutator alleles near *Mutyh*, and BXDs with both alleles exhibit even higher C>A mutation rates than those with either one alone. 

To our knowledge, these new methods for analyzing mutation spectra reveal the first evidence of epistasis between mammalian germline mutator alleles, and may be applicable to mutation data from humans and other model organisms. 



## Introduction

The germline mutation rate is a fundamental parameter in population genetics, and reflects the complex interplay between DNA replication and repair pathways, exogenous sources of DNA damage, and life-history traits. *Mutator alleles* may explain some of the within- and between-species variation in germline mutation rates [@PMID:32619789], but have proven challenging to identify in mammalian genomes. 

<!--In microorganisms like *Escherichia coli*, mutator alleles have emerged during experimental evolution [@PMID:], and human cancer genomes often harbor deleterious mutator alleles as well [@PMID:27197248].-->

Germline mutator alleles are difficult to detect for a number of reasons, including the fidelity of germline genome replication and the effects of selection on mutators. On average, humans are born with 30 to 50 single-nucleotide *de novo* germline mutations per haploid genome [@PMID:28959963;@PMID:31549960]; in mice, that number is closer to 10 or 15 [@PMID:31492841]. Due to the low baseline germline mutation rate in many mammals, it can be challenging to ascertain sequencing data from enough haplotypes to reliably detect those with significantly elevated *de novo* mutation counts. Moreover, in a population of sufficiently large $N_e$ (effective population size), large-effect mutator alleles may be efficiently purged by negative selection. The estimated selection coefficient on a mutator allele is approximately $2s \Delta U$ [@PMID:27739533], where $s$ is the mean selective coefficient on a new deleterious mutation and $\Delta U$ is the excess number of deleterious mutations caused by the mutator allele; the product of $s$ and $\Delta U$ is multiplied by $2$ to account for the average number of generations for which mutator is linked to the excess mutations it causes. 

Compared to haplotypes that harbor wild-type alleles at a particular locus, those with mutator alleles will likely carry an excess of total germline mutations. Indeed, candidate germline mutator loci have been discovered in human genomes by identifying haplotypes with significantly more derived alleles than the population mean [@PMID:28095480]. However, protein-coding genes involved in DNA replication and repair often recognize particular sequence motifs or excise lesions at specific nucleotides [@PMID:32619789]. Thus, we might also expect the spectrum of de novo mutations &mdash; that is, the frequency of each individual mutation type (C>T, A>G, etc.) &mdash; to differ between genomes that carry either a mutator or wild-type allele at a given locus.

In 2022, we discovered a germline mutator allele in mice by analyzing whole-genome sequencing data from 152 recombinant inbred lines (RILs). Commonly known as the <ins>B</ins>X<ins>D</ins>s [@PMID:33472028], these RILs were derived from either F2 or advanced intercrosses of C57<ins>B</ins>L/6J and <ins>D</ins>BA/2J, two laboratory strains that exhibit significant differences in their germline mutation spectra [@PMID:30753674]. Since the BXD RILs were maintained via brother-sister mating for up to 180 generations and housed in a controlled laboratory environment, they were an ideal population for mutator allele discovery. Each line accumulated hundreds or thousands of germline mutations on a nearly-homozygous linear mosaic of parental <ins>B</ins> and <ins>D</ins> haplotypes, while the effects of negative selection on new and standing variation were attenuated by strict inbreeding [@doi:10.1146/annurev.ecolsys.39.110707.173437]. In a previous study, we used quantitative trait locus (QTL) mapping to identify a locus on chromosome 4 that was strongly associated with the C>A germline mutation rate in the BXDs [@PMID:35545679]. The QTL overlapped *Mutyh*, which encodes a protein that normally prevents C>A mutations by repairing oxidative DNA damage [@PMID:17581577], and we hypothesized that missense mutations in *Mutyh* were responsible for a 50% increase in the C>A mutation rate between BXDs with either parental haplotype at the QTL [@PMID:35545679].

In this study, we developed a new method to detect alleles that affect the mutation spectrum in biparental RILs and applied it to *de novo* germline mutation data from the BXDs. We assessed its power to detect candidate mutator alleles, re-identified the mutator near *Mutyh*, and discovered compelling evidence of epistasis between two germline mutator alleles that augment the C>A germline mutation rate.


## Results

### Benchmarking the inter-haplotype distance method using simulations

We developed a statistical method, termed "inter-haplotype distance," to detect loci that are associated with the mutation spectrum in biparental RILs(Materials and Methods). To assess its power for detecting mutator alleles, we first tested the approach using simulated data (Materials and Methods). We find that power is primarily limited by the initial mutation rate of the $k$-mer mutation type affected by the mutator allele and the total number of *de novo* germline mutations used to detect it (that is, the product of the number of haplotypes and the mean number of mutations per haplotype) (Figure {@fig:simulations}). For example, given 50 haplotypes with an average of 500 *de novo* germline mutations each, our method has approximately 60% power detect a mutator allele that increases the C>T *de novo* mutation rate by 10%. However, the method only has about 30% power to detect a mutator of identical effect size that affects the C>G mutation rate, since C>G mutations are expected to make up a smaller fraction of all *de novo* germline mutations to begin with. These simulations also demonstrate that our method is well-powered to detect large-effect mutator alleles (e.g., those that increase the mutation rate of a specific $k$-mer by 50%), even with a relatively small number of mutations per haplotype (Figure {@fig:simulations}).

![**Simulations to assess the power of the inter-haplotype distance method.** We simulated *de novo* germline mutations on a toy population of haplotypes, such that 50% of haplotypes were affected by a mutator allele that increased the mutation rate of the specified $k$-mer by the specified effect size (an effect size of 1.5 indicates a 50% increase in the mutation rate). Colors of the lines indicate the number of simulated mutations on each haplotype (before augmenting the mutation rate with a mutator allele). Given a specific combination of parameters, the y-axis denotes the fraction of 100 simulations in which the simulated mutator allele could be detected at a p-value of 0.05. Shaded areas indicate the standard deviation of that fraction across 100 simulations.](images/sims.png){#fig:simulations width=7in} 

### Re-identifying the mutator allele on chromosome 4 in the BXDs

We applied our inter-haplotype distance method to 93 BXD RILs (Materials and Methods) with a total of 62,993 *de novo* germline mutations [@PMID:35545679]. Reassuringly, using 1-mer mutation spectra, we observed a large $\chi^{2}$ statistic peak at a locus on chromosome 4 (Figure {@fig:distance-results}A; maximum adjusted $\chi^2$ statistic of 352.7 at marker ID `rs52263933`; position 116.75 Mbp in GRCm38/mm10 coordinates). We observed the same peak on chromosome 4 using the 3-mer mutation spectrum, as well (Figure @fig:distance-3mer).

![**Results of inter-haplotype distance scans in the BXD RILs.** **a)** Adjusted $\chi^{2}$ statistics between aggregate 1-mer *de novo* mutation spectra on BXD haplotypes (n = 93 haplotypes; 62,993 total mutations) with either *D* or *B* alleles at 7,320 informative markers. $\chi^2$ statistic threshold at p = 0.05 was calculated by performing 10,000 permutations of the BXD haplotype mutation data, and is shown as a dotted grey line. **b)** Adjusted $\chi^{2}$ statistics between aggregate 1-mer *de novo* mutation spectra on BXD haplotypes with *D* alleles at `rs52263933` (n = 55 haplotypes; 40,913 total mutations) and either *D* or *B* alleles at 7,320 informative markers. $\chi^2$ statistic threshold at p = 0.05 was calculated by performing 10,000 permutations of the BXD haplotype mutation data, and is shown as a dotted grey line. **c)** Fractions of *de novo* germline mutations in BXDs with either *D* or *B* genotypes at markers `rs52263933` and `rs31001331`, stratified by mutation type. **d)** Fractions of *de novo* germline mutations in Sanger Mouse Genome Project (MGP) strains with either *D* or *B* genotypes at markers `rs52263933` and `rs31001331`, stratified by mutation type.](images/Figure%202.png){#fig:distance-results width=7in} 

In a previous analysis, we used quantitative trait locus (QTL) mapping to identify a nearly identical locus on chromosome 4 that was significantly associated with the C>A germline mutation rate in the BXDs [@PMID:35545679]. This locus overlapped 21 protein-coding genes that are annotated by the Gene Ontology as being involved in "DNA repair," but only one of these genes contained non-synonymous differences between the two parental strains: *Mutyh*. *Mutyh* encodes a protein involved in the base-excision repair of 8-oxoguanine (8-oxoG), a DNA lesion caused by oxidative damage, and prevents the accumulation of C>A mutations [@PMID:28551381;@PMID:28127763;@PMID:17581577]. C>A germline mutation rates are nearly 50% higher in BXDs that inherited *D* genotypes at marker ID `rs52263933` than in those that inherited *B* genotypes [@PMID:35545679].

### An additional germline mutator allele on chromosome 6

After confirming that the inter-haplotype distance method could recover the mutator locus overlapping *Mutyh*, we asked if our approach could identify additional mutator loci in the BXD. To account for the effects of the large-effect C>A germline mutator locus near *Mutyh*, we divided the BXD RILs into those with either *D* (n = 55) or *B* (n = 38) genotypes at `rs52263933` (the marker at which we observed the highest adjusted $\chi^{2}$ statistic on chromosome 4), and ran a genome-wide distance scan using each group separately (Figure {@fig:distance-results}B.

Using only the BXDs with *B* genotypes at the *Mutyh* mutator locus, we did not observe any genome-wide significant peaks. But using the BXDs with *D* genotypes at the same locus, we identified a $\chi^{2}$ statistic peak on chromosome 6 (Figure {@fig:distance-results}B; maximum adjusted $\chi^2$ statistic of 81.0 at marker `rs31001331`; position 114.05 Mbp in GRCm38/mm10 coordinates). We identified the same peak using the 3-mer mutation spectra (Figure @fig:distance-3mer). We queried the region underneath this peak (+/- 5 Mbp) and discovered 16 protein-coding genes that harbored nonsynonymous differences between C57BL/6J and DBA/2J. Two of these genes were also annotated with the Gene Ontology term "DNA repair": *Ogg1* and *Mbd4*. *Ogg1* encodes a key member of the base-excision repair response to oxidative DNA damage (a pathway that also includes *Mutyh*), and *Mbd4* encodes a protein that is involved in the repair of G:T mismatches at methylated CpG sites that have undergone spontaneous deamination. Each of these genes harbors a single fixed nonsynonymous difference between the C57BL/6J and DBA/2J parental strains (Table @tbl:nonsyn-diffs). 

| Gene name | Ensembl transcript name | Amino acid change | Position in GRCm38/mm10 coordinates | SIFT prediction | 
| - | - | - | - | - |
| *Ogg1* | `ENSMUST00000032406` | p.Thr95Ala | chr6:113328510 | `0.84` (tolerant/benign) | 
| *Mbd4* | `ENSMUST00000032469` | p.Asp129Asn | chr6:115849644 | `0.02` (intolerant/deleterious) | 

Table: Nonsynonymous mutations in DNA repair genes near the chr6 peak {#tbl:nonsyn-diffs}

We also considered the possibility that expression quantitative trait loci (eQTLs), rather than nonsynonymous mutations, could contribute to the C>A mutator phenotype associated to the locus on chromosome 6. Using GeneNetwork [@PMID:27933521] we mapped cis-eQTLs for *Ogg1* and *Mbd4* in a number of tissues, including hematopoetic stem cells, kidney, and spleen. BXD genotypes near the $\chi^{2}$ statistic peak on chromosome 6 were significantly associated with *Ogg1* expression in some (but not all) tissues, and *D* genotypes were nearly always associated with decreased gene expression (Table @tbl:eqtl-results). We discovered one significant cis-eQTL for *Mbd4* in spleen at which *D* alleles were associated with increased expression. We also queried a previously published collection of eQTLs derived from Diversity Outbred (DO) mouse embryonic stem cell expression data [@PMID:32795400], but did not find any significant eQTLs for either *Ogg1* or *Mbd4*.

Finally, we queried the structural variants identified in a population of inbred laboratory strains sequenced by the Sanger Mouse Genomes Project (MGP) [@PMID:21921910] and found 93 deletions within the implicated interval on chromosome 6. Of these, five overlapped the exonic sequences of three protein-coding genes: *Tmem72*, *Tmcc1*, and *Gm20387*. None of these genes has a previously annotated role in DNA binding, repair or replication, or in a pathway that would likely affect germline mutation rates.

### Evidence of epistasis between germline mutator alleles

Next, we more precisely characterized the effects of the chromosome 4 and 6 mutator alleles on mutation spectra in the BXDs. We observed that C>A germline mutation fractions in BXDs with *D* alleles at both mutator loci were higher than in BXDs with *D* alleles at either locus alone (Figure {@fig:distance-results}C). However, compared to BXDs with *B* alleles at the chromosome 6 mutator locus, those with *D* alleles did not exhibit higher C>A mutation fractions, indicating that the effects of the chromosome 6 mutator locus depend on the presence of a *D* allele at the chromosome 4 locus (Figure {@fig:distance-results}C). To more formally test for epistasis, we fit a linear model predicting counts of C>A mutations in each strain as a function of genotypes at `rs52263933` and `rs31001331` (the peak markers at the chr4 and chr6 mutator loci, respectively) (Materials and Methods). A model that included an interaction term between genotypes at the two markers fit the data significantly better (p = 0.00098) than a model including only additive effects of the two markers.

To explore the effects of the two mutator loci in other inbred laboratory mice, we also compared the germline mutation spectra of Sanger Mouse Genomes Project (MGP) strains. Dumont [@PMID:30753674] previously identified private germline mutations in 29 inbred laboratory strains; these private variants likely represent recent *de novo* germline mutations (Figure {@fig:distance-results}D). Only two of the MGP strains possess *D* genotypes at both the chromosome 4 and chromosome 6 mutator loci: DBA/1J and DBA/2J. As before, we tested for epistasis in the MGP strains by fitting two linear models predicting C>A mutation counts as a function of genotypes at `rs52263933` and `rs31001331`. A model incorporating an interaction term between genotypes at these loci did not fit the data significantly better than a model with additive effects alone (p = 0.174). Thus, we are unable to confirm the signal of epistasis observed in the BXDs, but this may be due to the smaller number of MGP strains with *de novo* germline mutation data.

### Only one of the candidate mutator alleles is present in wild mice 

To determine whether the candidate mutator alleles on chromosome 6 were segregating in natural populations, we queried previously published sequencing data generated from 67 wild-derived mice [@PMID:27622383]. These data include three subspecies of *Mus musculus*, as well as the outgroup *Mus spretus*. We found that the *D* allele of *Ogg1* was segregating at approximately 25% frequency in *Mus musculus domesticus*, the species from which C57BL/6J and DBA/2J derive the majority of their genomes [@PMID:17660819], and was fixed in *Mus musculus musculus*, *Mus musculus castaneus*, and the outgroup *Mus spretus*. However, the *D* allele of *Mbd4* was not present in any of the wild mice.



## Discussion

### Epistasis between germline mutator alleles

To our knowledge, these results reveal evidence of epistasis between mammalian germline mutator alleles for the first time. BXDs with *D* alleles at the mutator locus on chromosome 6 only exhibit elevated C>A mutation rates if they also carry *D* alleles at the previously-identified [@PMID:35545679] mutator locus on chromosome 4. And BXDs with *D* alleles at both loci have significantly higher C>A germline mutation rates than lines with *D* alleles at only one mutator locus alone (Figure {@fig:distance-results}C). This raises the exciting possibility that epistasis between mutator alleles has contributed to the evolution of germline mutation rates and spectra in mammalian genomes.

Importantly, we note that we observed epistasis between germline mutator alleles in an unnatural population; the BXDs were inbred by brother-sister mating in a highly controlled laboratory environment that attenuated the effects of natural selection on all but the most deleterious alleles [@doi:10.1146/annurev.ecolsys.39.110707.173437]. Large-effect mutator alleles (and epistasis between them) may be much less common in natural, outbreeding mammalian populations. However, our results demonstrate that germline mutation rates in recombinant inbred populations are highly plastic, and that RILs represent an ideal system in which to discover germline mutators.

<!-- However, we found the *D* allele in *Ogg1* to be at nearly 25% frequency in *Mus musculus domesticus*, the strain from which C57BL/6J and DBA/2J derive most of their genomes [@PMID:17660819]. Since the *D* mutator haplotype on chromosome 6 does not appear to increase the C>A germline mutation rate on its own (even in a homozygous state), we hypothesize that similar alleles may be at intermediate or high frequency in other natural populations.  -->

### Causal variants underlying the mutator allele

Two protein-coding DNA repair genes overlap the C>A mutator locus on chromosome 6 and also contain nonsynonymous fixed differences between the C57BL/6J and DBA/2J founder strains: *Ogg1*, a glycosylase that excises the oxidative DNA lesion 8-oxoguanine (8-oxoG) [@PMID:17581577], and *Mbd4*, a glycosylase that can bind to methylated CpG sites and remove mispaired thymine nucleotides opposite spontaneously deaminated CpGs. 

Both missense mutations and loss-of-heterozygosity in *Ogg1* have been associated with initiation and progression of various types of human cancer [@PMID:22829015;@PMID:10987279;@PMID:9662341]. Unrepaired 8-oxoG lesions can also lead to C>A mutations, and copy-number losses of either *Ogg1* or *Mutyh* are linked to elevated rates of spontaneous C>A mutation in human neuroblastoma [@doi:10.1073/pnas.2007898118]. Although *Ogg1* is a member of the same base-excision repair pathway as *Mutyh* (the protein-coding gene we previously implicated as harboring mutator alleles at the locus on chromosome 4), a number of lines of evidence suggest that the p.Asp129Asn missense mutation in *Mbd4* is the more compelling candidate mutator allele on chromosome 6. 

For example, the *Ogg1* p.Thr95Ala mutation is not predicted to be deleterious by *in silico* software tools and does not occur at a highly conserved amino acid. The *Mbd4* p.Asp129Asn mutation, on the other hand, occurs at an amino acid residue that is well-conserved across mammalian species, is predicted to be deleterious in the murine MBD4 protein sequence by SIFT (Table @tbl:nonsyn-diffs), and overlaps the methyl-CpG binding domain of *Mbd4*. A missense mutation that affects the homologous amino acid in humans (p.Asp142Gly in GRCh38/hg38) is also present on a single haplotype in the Genome Aggregation Database (gnomAD) [@PMID:32461654], and is predicted by SIFT and Polyphen [@PMID:20354512] to be "deleterious" and "probably_damaging" in human genomes, respectively. 

One of the key roles of *Mbd4* is to excise thymine nucleotides at G:T mispairs, which arise due to the spontaneous deamination of methylated CpGs. As a result, loss-of-function mutations in *Mbd4* often lead to increased rates of CpG>TpG mutation [@PMID:12130785]. Although loss-of-function (LOF) mutations in *Mbd4* are not known to cause C>A mutator phenotypes in mammalian cells, *Mbd4* is involved in numerous cellular processes, some of which are facilitated through its physical interactions with the mismatch repair (MMR) gene *Mlh1* [@PMID:10097147;@PMID:26503472]. Perhaps most intriguingly, LOF mutations in *Mbd4* can exacerbate the effects of exogenous DNA damage agents. Mouse embryonic fibroblasts that harbor homozygous LOF mutations in *Mbd4* fail to undergo apoptosis following treatment with a number of chemotherapeutics and mutagenic compounds [@PMID:14614141]. Although most of these exogenous mutagens cause DNA damage that is normally repaired by MMR machinery, murine intestinal cells with biallelic LOF mutations in *Mbd4* also show a reduced apoptotic response to gamma irradiation, which is repaired independently of *Mlh1* [@PMID:14562041]. Homozygous LOF mutations in *Mbd4* also lead to accelerated intestinal tumor formation in mice that harbor an *Apc* allele that predisposes them to intestinal neoplasia [@PMID:12130785]. Finally, mice with biallelic truncations of the *Mbd4* coding sequence exhibit modestly increased mutation rates in colon cancer cell lines, including increased C>A mutation rates in certain cell types [@PMID:17285135].

Given these various lines of evidence, we believe that *Mbd4* is the most likely candidate gene to explain the additional C>A mutator phenotype in the BXDs, but we are unable to conclusively determine that the p.Asp129Asn missense mutation is the causal allele. We previously hypothesized that *Mutyh* missense mutations on *D* haplotypes were responsible for the large-effect C>A mutator phenotype we observed in the BXDs [@PMID:35545679]. However, using high-quality long-read assemblies of inbred laboratory strains, another group recently identified a ~5 kbp mobile element insertion (MEI) within the first intron of *Mutyh* [@doi:10.1101/2022.09.26.509577] that is present on *D* haplotypes and absent from *B* haplotypes. The MEI is associated with significantly reduced expression of *Mutyh* in embryonic stem cells from laboratory strains, and may therefore underlie the previous C>A germline mutator phenotype in the BXDs. In light of this new evidence, we cannot discount the possibility that large structural variants or eQTLs associated with decreased expression of either *Ogg1* or *Mbd4* (Table @tbl:eqtl-results) are responsible for the C>A mutator phenotype we observed in this study.

### Mechanism of epistasis between *Mutyh* and *Mbd4* mutator alleles

<!-- *Mutyh* and *Ogg1* are key members of the base-excision repair (BER) response  to 7,8-dihydro-8oxo-deoxyguanine (8-oxoG), one of the most common products of DNA damage by reactive oxygen species [@PMID:17581577;@PMID:28963982]. *Mutyh* and *Ogg1* fulfill two distinct roles in the BER response to 8-oxoG. If a cell is not actively undergoing DNA replication, *Ogg1* can excise the 8-oxoG lesion, leaving behind an unpaired cytosine on the opposite strand [@PMID:28963982]. Then, additional BER proteins can incorporate an unmodified guanine and restore the appropriate G:C base-pair. However, if the 8-oxoG lesion is not repaired prior to a single round of DNA replication, DNA polymerases will often misincorporate adenines (via Hoogsteen base-pairing) opposite the 8-oxoG lesion. In this case, *Mutyh* can excise the mispaired adenine and enable *Ogg1* (along with other members of the BER pathway) to correct the lesion [@doi:10.1073/pnas.2007898118]. -->

Although both *Mutyh* and *Mbd4* are DNA glycosylases that participate in base-excision repair, they operate on distinct DNA lesions: *Mutyh* excises adenines paired with 8-oxoguanine, while *Mdb4* excises thymines opposite spontaneously deaminated CpGs. However, given the role of *Mbd4* in suppressing DNA damage-induced apoptosis [@PMID:14614141;@PMID:14562041], we hypothesize that in the BXD RILs, *D* alleles in *Mutyh* and *Mbd4* exhibit epistasis through the following mechanism.

In the absence of other defects in the DNA repair response, *D* alleles at *Mbd4* appear to have little or no detectable effect on *de novo* mutation rates (Figure {@fig:distance-results}C). Although loss-of-function mutations in *Mbd4* are expected to increase CpG>TpG mutation rates [@PMID:12130785], it is possible that the p.Asp129Asn missense mutation is not sufficient to cause such a phenotype in the BXDs. As we demonstrated in this and a previous manuscript, *D* alleles at *Mutyh* alone lead to significantly increased C>A mutation rates (Figure {@fig:distance-results}C) [@PMID:35545679]. In response to an accumulation of C>A mutations, a fraction of spermatagonial stem cells with *D* alleles at *Mutyh* may undergo apoptosis to prevent further unrepaired DNA damage. However, if those germline cells harbor *D* alleles at both *Mutyh* and *Mbd4*, they may be unable to arrest the cell cycle and complete apoptosis, allowing the effects of the *D* alleles at *Mutyh* to exacerbate C>A mutation rates even further.

<!-- Given the distinct roles of *Mutyh* and *Ogg1* in the BER pathway, it seems plausible that mutator alleles in both protein-coding genes could together exhibit non-additive effects on C>A mutation rates. However, even in cells with functional copies of *Mutyh*, repair of 8-oxoG likely requires the activity of *Ogg1*. It is therefore somewhat surprising that the *D* haplotype at *Ogg1*, which further augments the effects of the *Mutyh* mutator haplotype on C>A mutation rates, has no apparent effect on its own. One possibility is that *D* haplotype overlapping *Ogg1* does, in fact, lead to elevated C>A mutation rates, but that we are underpowered to detect its effect in this study. Notably, copy-number-loss of *Ogg1* in human neuroblastoma causes a much more modest increase in C>A mutation rates than copy-number-loss of *Mutyh* [@doi:10.1073/pnas.2007898118]. -->

### Discovering mutator alleles in other systems

Numerous lines of evidence suggest that mutator alleles contribute to variation in mutation rates and spectra across the tree of life. In two natural isolates of *Saccharomyces cerevisiae*, nonsynonymous variation in *OGG1* causes a substantial increase in the C>A *de novo* mutation rate [@PMID:34523420]. Recent analyses have suggested that mutator alleles and/or environmental mutagens have shaped mutation rate evolution both in human genomes [@doi:https://doi.org/10.1101/2022.06.17.496622] and more broadly during great ape evolution [@PMID:33983415]. The heritability of paternal *de novo* mutation counts in the human germline has also been estimated to be between 10 and 20%, demonstrating a contribution of genetic factors to germline mutation rates [@doi:https://doi.org/10.1101/2022.12.17.520885]). However, mutator discovery remains challenging in mammalian genomes.

What conditions must be met in order to detect a germline mutator allele? Presumably, one must have access to many haplotypes, each with a reasonably large number of *de novo* germline mutations that remain linked to the mutator allele(s) that caused them. Recently, thousands of human pedigrees have been sequenced in an effort to precisely estimate the rate of human *de novo* germline mutation [@PMID:31549960;@PMID:28959963]. Selection on germline mutator alleles will likely prevent large-effect mutators from reaching high allele frequencies; however, if multiple mutators are active in a particular population, it becomes much more likely that a subset will be detectable by sequencing a sufficient number of human trios [@PMID:35666194]. Current estimates of power to detect germline mutators in human pedigrees generally assume that mutators affect all mutation types equally, and that methods for mutator discovery will rely on identifying haplotypes with excess total mutation counts [@PMID:35666194]. However, our results in the BXD suggest that germline mutators often exert their effects on a small number of $k$-mer mutation types, and may be far more amenable to detection by analyzing mutation spectra instead.


### Using germline mutation spectra to identify mutator alleles

Germline mutation spectra are a rich source of information about the demographic history of populations, as well as the activity of both exogenous and endogenous sources of mutation throughout time. For example, by analyzing the $3$-mer mutation spectrum in a collection of human genomes, Harris and Pritchard [@PMID:28440220] discovered a "pulse" of TCC>TTC mutation activity in European populations that likely occurred between 15,000 and 2,000 years ago, and perhaps began even earlier [@PMID:34016747]).

Within somatic tissues, mutation spectra can also be used to uncover the mutational processes active in particular populations of cells [@PMID:23945592]. New computational methods have been developed to extract "mutational signatures" from large databases of somatic mutations in cancer [@PMID:36388765]. These signatures, which describe the relative frequency of each $3$-mer mutation type, can often be precisely attributed to chemotherapeutic agents, exposures to environmental mutagens, or loss-of-function mutations in genes encoding DNA repair or replication proteins [@PMID:23945592;@PMID:31740835;@PMID:27811275]. 

Although a germline mutator allele should increase the absolute count of mutations on a linked haplotype, our results demonstrate that its effects can be more easily detectable by examining mutation *spectra* instead. For example, *D* alleles at the mutator locus on chromosome 6 augment the C>A mutation rate by a factor of approximately 1.2 (Figure {@fig:distance-results}). Since C>A mutations comprise approximately 10% of all germline mutations to begin with, *D* alleles only increase the overall germline mutation rate by about 2%. Given the depth of information that can be encoded in the mutation spectrum, we expect that mutation spectra can be further exploited to discover genetic modifiers of the mutation rate in other study systems, as well. 

## Materials and Methods

### Identifying *de novo* germline mutations in the BXD RILs

The BXD resource currently comprises a total of 152 recombinant inbred lines (RILs). RILs were derived from either F2 or advanced intercrosses, and subsequently inbred by brother-sister mating for up to 180 generations [@PMID:33472028]. BXDs were generated in distinct breeding "epochs," which were each initiated with a distinct cross of C57BL/6J and DBA/2J parents; epochs 1, 2, 4, and 6 were derived from F2 crosses, while epochs 3 and 5 were derived from advanced intercrosses [@PMID:33472028]. Previously, we analyzed whole-genome sequencing data from the BXDs and identified candidate *de novo* germline mutations in each line [@PMID:35545679]. A detailed description of the methods used for DNA extraction, sequencing, alignment, and variant processing, as well as the characteristics of the *de novo* mutations, are available in a previous manuscript [@PMID:35545679].

Briefly, we identified private single-nucleotide mutations in each BXD that were absent from all other RILs, as well as from the C57BL/6J and DBA/2J parents. We required each private variant to be meet the following criteria: 

* genotyped as either homozygous or heterozygous for the alternate allele, with at least 90% of sequencing reads supporting the alternate allele

* supported by at least 10 sequencing reads

* Phred-scaled genotype quality of at least 20 

* must not overlap regions of the genome annotated as segmental duplications or simple repeats in GRCm38/mm10

* must occur on a parental haplotype that was inherited by at least one other BXD at the same locus; these other BXDs must be homozygous for the reference allele at the variant site

### A new approach to discover germline mutator alleles

#### Calculating inter-haplotype distance

Using the existing catalog of *de novo* germline mutations in the BXDs, we developed a new approach to discover loci that affect the germline *de novo* mutation spectrum in biparental RILs (Figure @fig:toy-diagram).

![**Overview of inter-haplotype distance method for discovering mutator alleles.** **a)** A population of four haplotypes has been genotyped at three informative markers; each haplotype also harbors private *de novo* germline mutations. At each informative marker, we compute an aggregate *de novo* germline mutation spectrum in the haplotypes that carry either parental allele, and calculate the $\chi^{2}$ statistic between the two aggregate spectra. **b)** We repeat the process outlined in a) for every informative marker along the genome. **c)** To assess the significance of any $\chi^{2}$ statistic peaks in b), we perform a permutation test by shuffling the labels associated with each haplotype's mutation data and running a genome-wide scan. In each of $N$ permutations, we record the maximum $\chi^2$ statistic encountered at any locus in the distance scan. Finally, we calculate the $1 - p$ percentile of the distribution of those maximum statistics to obtain a genome-wide $\chi^{2}$ statistic threshold at the specified value of $p$.](images/Figure%201.png){#fig:toy-diagram width=7in} 

We assume that a collection of haplotypes has been genotyped at informative markers, and that *de novo* germline mutations have been identified on each haplotype.

At each informative marker, we divide haplotypes into two groups based on the parental allele that they inherited. We then compute a $k$-mer mutation spectrum using the aggregate mutation counts in each haplotype group. The $k$-mer mutation spectrum contains the frequency of every possible $k$-mer mutation type in a collection of mutations, and can be represented as a vector of size $6 \times 4^{k - 1}$ after collapsing by strand complement. For example, the 1-mer mutation spectrum is 6-element vector that contains the frequencies of C>T, C>G, C>A, A>G, A>T, and A>C mutations. In practice, we expanded the 1-mer mutation spectrum to include C>T transitions at CpG nucleotides, since CpG>TpG *de novo* mutations are often caused by a distinct mechanism (spontaneous deamination of methylated cytosine) [@PMID:19488047].

At each marker, we then calculate the $\chi^{2}$ statistic between the aggregate mutation spectra of haplotypes with either parental allele. Larger values of the $\chi^{2}$ statistic suggest more dissimilarity between the two aggregate mutation spectra.

Inspired by methods from QTL mapping [@PMID:7851788], we use permutation tests to establish genome-wide $\chi^{2}$ statistic thresholds. In each of $N$ permutation trials, we randomly shuffle the per-haplotype mutation data such that haplotype labels no longer correspond to the correct mutation counts. Using the shuffled mutation data, we perform a genome-wide scan as described above, and record the maximum $\chi^2$ statistic observed at any locus. After $N$ permutations (usually 10,000), we compute the $1 - p$ percentile of the distribution of maximum statistics, and use that percentile value as a genome-wide significance threshold (for example, at $p = 0.05$).

#### Accounting for relatedness between strains 

We expect each BXD RIL to derive approximately 50% of its genome from C57BL/6J and 50% from DBA/2J. As a result, every pair of RILs will likely be identical-by-descent (IBD) at a fraction of genotyped markers. Pairs of more genetically similar BXDs may also have more similar mutation spectra, potentially due to shared polygenic effects on the mutation process. Therefore, at a given marker, if the BXD RILs that inherited *D* haplotypes are more genetically dissimilar from the RILs that inherited *B* haplotypes (considering all loci throughout the genome), we might expect the aggregate mutation spectra in the two groups to also be more dissimilar. 

We implemented a simple approach to account for these potential issues of relatedness. At each marker $g_i$, we divide BXD haplotypes into two groups based on the parental allele they inherited. As before, we first compute the aggregate mutation spectrum in each group of haplotypes and calculate the $\chi^{2}$ statistic between the two aggregate spectra ($\chi^{2}_{i}$). Then, within each group of haplotypes, we calculate the allele frequency of the *D* allele at every marker along the genome to obtain a vector of length $n$, where $n$ is the number of genotyped markers. To quantify the genetic similarity between the two groups of haplotypes, we calculate the Pearson correlation coefficient $r_i$ between the two vectors of marker-wide *D* allele frequencies. 

Thus, at every marker $g_i$ along the genome, we divide BXD haplotypes into two groups and compute two metrics: $\chi^{2}_{i}$ (the $\chi^2$ statistic between the two groups' aggregate spectra) and $r_i$ (the correlation between genome-wide *D* allele frequencies in the two groups). To control for the potential effects of genetic similarity on $\chi^{2}$ statistics, we regress $\left(\chi^2_{1}, \chi^2_{2}, \ldots \chi^2_{n} \right)$ on $\left( r_1, r_2, \ldots r_n \right)$ for all $n$ markers and fit an ordinary least-squares regression model. We then use the residuals from the fitted model as the "adjusted" $\chi^{2}$ statistic values for each marker. If genome-wide genetic similarity between haplotypes perfectly predicts $\chi^{2}$ statistics at each marker, these residuals will all be 0 (or very close to 0). If genome-wide genetic similarity has no predictive power, the residuals will simply represent the difference between the observed $\chi^{2}$ statistic at a single marker and the marker-wide mean of $\chi^{2}$ statistics.

#### Implementation and source code

The inter-haplotype distance method was implemented in Python, and relies heavily on the following Python libraries: `numpy`, `pandas`, `matplotlib`, `scikit-learn`, `pandera`, `seaborn`, and `numba` [@doi:10.1038/s41586-020-2649-2;@doi:10.5281/zenodo.3509134;@doi:10.1109/MCSE.2007.55;@url:https://jmlr.csail.mit.edu/papers/v12/pedregosa11a.html;@doi:10.25080/Majora-342d178e-010;@doi:10.21105/joss.03021;@doi:10.1145/2833157.2833162].

Additional documentation is available on GitHub [@url:https://github.com/quinlan-lab/proj-mutator-mapping], along with a reproducible Snakemake [@doi:10.12688/f1000research.29032.1] workflow for running the method from start to finish using the BXDs (including downloading the mutation data, downloading genotypes, and running a genome-wide distance scan).

### Simulations to assess the power of the inter-haplotype distance approach

We performed a series of simple simulations to estimate our power to detect alleles that affect the germline mutation spectrum in biparental RILs using the inter-haplotype distance method.

First, we simulate the $k$-mer mutation spectrum in a population of $h$ haplotypes. We assume that exactly $\frac{h}{2}$ of the haplotypes are under the effects of a mutator allele that increases the mutation rate of a particular mutation type(s) by an effect size $e$. We simulate $m$ mutations on each haplotype as follows:

We first define a vector of $1$-mer mutation probabilities:

$$P = \left( 0.29, \ 0.17, \ 0.12, \ 0.075, \ 0.1, \ 0.075, \ 0.17 \right)$$

These probabilities sum to 1 and correspond to the expected frequencies of C>T, CpG>TpG, C>A, C>G, A>T, A>C, and A>G *de novo* germline mutations in mice, respectively [@PMID:31492841].

If we are simulating the $3$-mer mutation spectrum, we modify the vector of mutation probabilities $P$ to be length 96, and assign every 3-mer mutation type a value of $\frac{P_c}{16}$, where $P_c$ is the probability of the "central" mutation type associated with the 3-mer mutation type. In other words, each of the 16 possible N<ins>C</ins>N>N<ins>T</ins>N 3-mer mutation types would be assigned a mutation probability of $\frac{P_c}{16} = \frac{0.46}{16} = 0.02875$.

To simulate the mutation spectrum on the *wild-type* haplotypes, we define a matrix $C$ of size $(\frac{h}{2}, n)$, where $n = \left( 6 \times 4^{k - 1} \right) + 1$ (i.e., the number of $k$-mer mutation types being simulated). First, we generate a vector of lambda values by scaling the mutation probabilities by the number of mutations we wish to simulate:

$$\lambda = Pm$$

Then, we populate the matrix $C$ by taking a single Poisson draw from the vector of $\lambda$ values for each mutation type on each haplotype. Thus, for every row $i$ in the matrix (i.e., for every haplotype), we perform the following for mutation type $j$:

$$C_{i, j} = \mathrm {Pois}(\lambda_{j})$$

To simulate the mutation spectrum on the $\frac{h}{2}$ *mutator* haplotypes, we define a new matrix $C^{\prime}$ of size $(\frac{h}{2}, n)$ as defined above. We then multiply the lambda value of a particular mutation type (or multiple mutation types) by the mutator effect size $e$ to obtain $\lambda^{\prime}$. Then, for every row $i$ in the matrix:

$$C^{\prime}_{i, j} = \mathrm {Pois}(\lambda^{\prime}_{j})$$

When $k = 1$, we only augment the effect size of one mutation type at a time, but when $k = 3$, we augment a fraction (25%, 50%, or 100%) of the $3$-mer mutation types associated with a single "central" mutation type. 

After generating mutator and wild-type haplotypes, we compute the aggregate mutation spectrum in either group by summing the columns of $C$ and $C^{\prime}$. We then calculate the $\chi^{2}$ statistic between the two aggregate spectra, which we call the "focal" distance $D_f$. To determine whether $D_f$ is greater than what we'd expect by chance, we perform a permutation test.

First, we concatenate the matrices of wild-type and mutator haplotype spectra:

$$A = \begin{bmatrix}
C \\
C^{\prime}
\end{bmatrix}$$

Then, in each of $N = 1,000$ trials, we randomly permute the rows of $A$. In every permutation, we consider the row indices from $\left[0, \frac{h}{2} \right)$ to correspond to the wild-type haplotypes, and the row indices from $\left[ \frac{h}{2}, h \right)$ to correspond to the mutator haplotypes. We then compute the $\chi^{2}$ statistic between the aggregate spectra of the wild-type and mutator haplotypes. If fewer than 5% of the $N$ permutations produces a $\chi^{2}$ statistic greater than or equal to $D_f$, we say that the approach successfully identified the mutator allele. For every combination of simulation parameters ($h$, $m$, $e$, and so on) we perform 100 trials and record the number of trials in which we successfully identify the mutator allele. 

### Applying the inter-haplotype distance method to the BXDs

We downloaded previously-generated BXD *de novo* germline mutation data from the GitHub repository associated with our previous manuscript, which was also archived at Zenodo [@url:https://github.com/tomsasani/bxd_mutator_manuscript;@doi:10.5281/zenodo.5941048;@PMID:35545679], and downloaded a CSV file of BXD genotypes at 7,320 informative markers from GeneNetwork [@url:http://gn1.genenetwork.org/dbdoc/BXDGeno.html;@PMID:27933521]. We also downloaded relevant metadata about each BXD RIL from the manuscript describing the updated BXD resource [@PMID:33472028]. 

As in our previous manuscript [@PMID:35545679], we included mutation data from a subset of the 152 BXDs in our inter-haplotype distance scans. We removed any BXDs that had been inbred for fewer than 20 generations, as it takes approximately 20 generations of strict brother-sister mating for an RIL genome to become >98% homozygous [@url:https://link.springer.com/book/10.1007/978-1-349-04904-2]. As a result, any potential mutator allele would almost certainly be either fixed or lost after 20 generations. If fixed, the allele would remain linked to any excess mutations it causes for the duration of subsequent inbreeding, and its effects would be detectable using our methods. Additionally, a strain only meets the canonical definition of "inbred" if it has been subject to brother-sister mating for at least 20 generations [@url:www.informatics.jax.org/mgihome/nomen/strains.shtml]. We also removed the BXD68 RIL from our genome-wide scans, since we previously discovered a hyper-mutator phenotype in that strain; the C>A germline mutation rate in BXD68 is over 5 times the population mean, likely due to a private deleterious nonsynonymous mutation in *Mutyh* [@PMID:35545679]. In total, we included 93 BXD RILs in our genome-wide scans.

We used Snakemake [@PMID:34035898] to write a reproducible workflow for running the inter-haplotype distance method on the BXD dataset, which has been deposited in the GitHub repository associated with this manuscript [@url:https://github.com/quinlan-lab/proj-mutator-mapping].

### Identifying candidate mutator alleles overlapping the chromosome 6 peak

We investigated the region implicated by our inter-haplotype distance approach on chromosome 6 by subsetting the joint-genotyped BXD VCF file (European Nucleotide Archive accession **PRJEB45429** [@url:https://www.ebi.ac.uk/ena/browser/view/PRJEB45429]) using `bcftools` [@PMID:33590861]. We defined the candidate interval surrounding the $\chi^{2}$ statistic peak on chromosome 6 as +/- 5 Mbp from the genotype marker with the largest adjusted $\chi^{2}$ statistic value (`rs31001331`). To predict the functional impacts of both single-nucleotide variants and indels on splicing, protein structure, etc., we annotated variants in the BXD VCF using the following `snpEff` [@PMID:22728672] command: 

```
 java -Xmx16g -jar /path/to/snpeff/jarfile GRCm38.75 /path/to/bxd/vcf > /path/to/uncompressed/output/vcf
```

and used `cyvcf2` [@PMID:28165109] to iterate over the annotated VCF file in order to identify nonsynonymous fixed differences between the parental C57BL/6J and DBA/2J strains.

### Comparing mutation spectra between Mouse Genomes Project strains

We downloaded mutation data from a previously published analysis [@PMID:30753674] (Supplementary File 1, Excel Table S3) that identified strain-private mutations in 29 strains that were originally whole-genome sequenced as part of the Sanger Mouse Genomes (MGP) project [@PMID:21921910]. When comparing counts of each mutation type between MGP strains that harbored either *D* or *B* alleles at the chromosome 4 or chromosome 6 mutator loci, we adjusted mutation counts by the number of callable A, T, C, or G nucleotides in each strain as described previously [@PMID:35545679].

### Querying GeneNetwork for evidence of eQTLs at the mutator locus

We used the online GeneNetwork resource [@PMID:27933521], which contains array- and RNA-seq-derived expression measurements in a wide variety of tissues from numerous datasets, to find *cis*-eQTLs for the DNA repair genes we implicated under the $\chi^{2}$ statistic peak on chromosome 6. On the GeneNetwork homepage (genenetwork.org), we selected the "BXD Family" **Group** and used the **Type** dropdown menu to select each of the specific expression datasets described in Table @tbl:eqtl-provenance. In the **Get Any** text box, we then entered the listed gene name and clicked **Search**. After selecting the appropriate trait ID on the next page, we used the **Mapping Tools** dropdown to run Haley-Knott regression [@PMID:16718932] with the following parameters: WGS-based marker genotypes, 1,000 permutations for LOD threshold calculations, and controlling for BXD genotypes at the `rs32497085` marker.

The exact names of the expression datasets we used for each tissue are shown in Table @tbl:eqtl-provenance below:

| Tissue name | Complete name of GeneNetwork expression data | GeneNetwork trait ID |
| - | - | - | 
| Kidney | `Mouse kidney M430v2 Sex Balanced (Aug06) RMA` | `1448815_at` |
| Gastrointestinal | `UTHSC Mouse BXD Gastrointestinal Affy MoGene 1.0 ST Gene Level (Apr14) RMA` | `10540639` |
| Hematopoetic stem cells | `UMCG Stem Cells ILM6v1.1 (Apr09) transformed` | `ILM1940279` | 
| Hematopoetic progenitor cells | `UMCG Progenitor Cells ILM6v1.1 (Apr09) transformed` | `ILM1940279` | 
| Spleen | `UTHSC Affy MoGene 1.0 ST Spleen (Dec10) RMA` | `10540639` | 
| Liver | `UTHSC BXD Liver RNA-Seq Avg (Oct19) TPM Log2` | `ENSMUST00000032406` | 
| Heart | `NHLBI BXD All Ages Heart RNA-Seq (Nov20) TMP Log2 **` | `ENSMUSG00000030271` | 
| Eye | `UTHSC BXD All Ages Eye RNA-Seq (Nov20) TPM Log2 **` | `ENSMUSG00000030271` | 

Table: Names of gene expression datasets used for each tissue type on GeneNetwork {#tbl:eqtl-provenance}

### Calculating the frequencies of candidate mutator alleles in wild mice 

To determine the frequencies of the *Ogg1* p.Thr95Ala and *Mbd4* p.Asp129Asn mutations in other populations of mice, we queried a VCF file containing genome-wide variation in 67 wild-derived mice from four species of *Mus* [@PMID:27622383]. We calculated the allele frequency of each nonsynonymous mutation in each of the four species or subspecies (*Mus musculus domesticus*, *Mus musculus musculus*, *Mus musculus castaneus*, and *Mus spretus*), including genotypes that met the following criteria:

* supported by at least 10 sequencing reads 

* Phred-scaled genotype quality of at least 20

### Testing for epistasis between the two mutator loci

To test for the presence of epistasis between the mutator loci on chromosome 4 and chromosome 6, we modeled C>A mutation rates in the BXDs as a function of genotypes at either locus. Specifically, we tested for statistical interaction between genotypes by fitting a generalized linear model in the R statistical language as follows:

```R
m1 <- glm(Count ~ offset(log(ADJ_AGE)) + Genotype_A * Genotype_B, data = data, family=poisson())
```

In this model, `Count` is the count of C>A *de novo* mutations observed in each BXD RIL. `ADJ_AGE` is the product of the number of "callable" cytosine nucleotides in each RIL (i.e., the total number of cytosines covered by at least 10 sequencing reads in the RIL) and the number of generations for which the RIL was inbred. We included the logarithm of `ADJ_AGE` as an "offset" in order to model the response variable as a rate rather than an absolute count; the BXDs differ in both their durations of inbreeding and the proportions of their genomes that were sequenced to sufficient depth, which influences the number of mutations we observe in each RIL. The `Genotype_A` and `Genotype_B` terms represent the genotypes of BXDs at markers `rs52263933` and `rs31001331` (the markers with peak $\chi^{2}$ statistics on chromosomes 4 and 6 in the two inter-haplotype distance scans). Since each BXD is inbred for at least 20 generations, we considered genotypes at either locus to be binary ("B" or "D"). Using analysis of variance (ANOVA), we then compared the model including an interaction effect to a model including only additive effects:

```R
m2 <- glm(Count ~ offset(log(ADJ_AGE)) + Genotype_A + Genotype_B, data = data, family=poisson())
```

```R
anova(m1, m2, test="Chisq")
```

We tested for epistasis in the Sanger Mouse Genomes Project (MGP) strains using a nearly-identical approach. In this analysis, we fit two models as follows:

```R
m1 <- glm(Count ~ offset(log(CALLABLE_C)) + Genotype_A * Genotype_B, data = data, family=poisson())

m2 <- glm(Count ~ offset(log(CALLABLE_C)) + Genotype_A + Genotype_B, data = data, family=poisson())
```

where `Count` is the count of strain-private C>A mutations observed in each MGP strain [@PMID:30753674]. The `CALLABLE_C` term represents the total number of cytosine and guanine nucleotides that were accessible for mutation calling in each strain, and the `Genotype_A` and `Genotype_B` terms represent MGP genotypes at `rs52263933` and `rs31001331`. We compared the two models using ANOVA as described above.

Since each BXD derives approximately 50% of its genome from C57BL/6J and 50% from DBA/2J, we performed an additional test for epistasis that accounted for kinship between the BXD RILs. Using the `lmekin` method from the `coxme` package [@url:https://cran.r-project.org/web/packages/coxme/index.html] in the R statistical language, we fit a mixed effects model predicting C>A mutation fractions as a function of genotypes at both `rs52263933` and `rs31001331`, and included a pairwise kinship matrix as a random effect.

```R
m = lmekin(Fraction ~ Genotype_A * Genotype_B + (1|sample), data = data, varlist = kinship_matrix)
```

The rows and columns of the kinship matrix were labeled with the `sample` name of each BXD, such that the `(1|sample)` term in the model captured the random effect of kinship. We calculated the `kinship_matrix` using the `calc_kinship` method from `R/qtl2` [@PMID:30591514] as follows:

```R
# read in the JSON-formatted file that directs R/qtl2 to sample 
# genotypes, phenotypes, and covariates if applicable
bxd <- read_cross2("path/to/bxd.json")

# subset cross2 object to BXDs with C>A fractions in `data`
bxd <- bxd[data$sample, ]

# insert pseudomarkers into the genotype map
gmap <- insert_pseudomarkers(bxd$gmap, step = 0.2, stepwidth = "max")

# calculate QTL genotype probabilities
pr <- calc_genoprob(bxd, gmap, error_prob = 0.002, map_function = "c-f")

# calculate kinship between strains using all chromosomes
k <- calc_kinship(pr, "overall")

kinship_matrix = as.matrix(k)
```






## Supplementary information

### Using cosine distance instead of $\chi^2$ statistics for comparing mutation spectra

We also explored the use of cosine distance as an alternative to the $\chi^{2}$ statistic for comparing mutation spectra in our inter-haplotype distance scans. The cosine distance between two vectors $\mathbf{A}$ and $\mathbf{B}$ is defined as 

$$D_C = 1 - \frac{\mathbf{A} \cdot \mathbf{B}}{||\mathbf{A}|| \ ||\mathbf{B}||}$$

where $||\mathbf{A}||$ and $||\mathbf{B}||$ are the $L^2$ (or Euclidean) norms of $\mathbf{A}$ and $\mathbf{B}$, respectively. The cosine distance metric has a number of favorable properties for comparing mutation spectra. Since cosine distance does not take the magnitude of vectors into account, it can be used to compare two spectra with unequal total mutation counts (even if those total counts are relatively small). Additionally, by calculating the cosine distance between mutation *spectra*, we avoid the need to perform separate comparisons of mutation counts at each individual $k$-mer mutation type. 

In practice, we found that the $\chi^2$ statistic was more sensitive for detecting loci associated with differences in mutation spectra. However, we provide the ability to use cosine distance in our method, as well, since the $\chi^2$ statistic may not behave as expected in certain situations (e.g., if the counts of mutations in each $k$-mer type are small).

### Using 3-mer mutation spectra to perform the inter-haplotype distance scans

![**Results of inter-haplotype distance scans in the BXD RILs using 3-mer mutation spectra.** **a)** Adjusted $\chi^{2}$ statistics between aggregate 3-mer *de novo* mutation spectra on BXD haplotypes (n = 93 haplotypes; 62,993 total mutations) with either *D* or *B* alleles at 7,320 informative markers. Distance threshold at $p = 0.05$ was calculated by performing 10,000 permutations of the BXD haplotype mutation data, and is shown as a dotted grey line. **b)** Adjusted $\chi^{2}$ statistics between aggregate 3-mer *de novo* mutation spectra on BXD haplotypes with *D* alleles at `rs52263933` (n = 55 haplotypes; 40,913 total mutations) and either *D* or *B* alleles at 7,320 informative markers. Distance threshold at $p = 0.05$ was calculated by performing 10,000 permutations of the BXD haplotype mutation data, and is shown as a dotted grey line.](images/Figure%20S2.png){#fig:distance-3mer width=7in} 

### Mapping cis-eQTLs for *Ogg1* and *Mbd4* in GeneNetwork

| Gene name | Tissue name | # BXDs with expression data |  Top significant marker | LRS at top significant marker | Significant LRS threshold | Additive effect of D allele on expression |
| - | - | - | - | - | - |
| Ogg1 | Kidney | 53 | `rsm10000004188` | 52.25 | 17.82 | -0.186 |
| Ogg1 | Gastrointestinal | 46 | `rsm10000003441` | 23.39 | 16.09 | -0.074 |
| Ogg1 | Hematopoetic stem cells | 22 | - | - | 16.45 | - | 
| Ogg1 | Hematopoetic progenitor cells | 23 | - | - | 18.52 | - | 
| Ogg1 | Spleen | 79 | `rsm10000003418` | - | 17.51 | - | 
| Ogg1 | Liver | 50 | `rsm10000004188` | 53.54 | 18.77 | -0.156 | 
| Ogg1 | Heart | 73 | - | - | 16.22 | - |
| Ogg1 | Eye | 87 | `rsm10000004194` | 23.05 | 16.96 | 0.088 |  
| Mbd4 | Kidney | 53 | - | - | 18.48 | - |
| Mbd4 | Gastrointestinal | 46 | - | - | 15.97 | - |
| Mbd4 | Hematopoetic stem cells | 22 | - | - | 18.12 | - | 
| Mbd4 | Hematopoetic progenitor cells | 23 | - | - | 18.55 | - | 
| Mbd4 | Spleen | 79 | `rsm10000004199` | 21.42 | 16.99 | 0.069 | 
| Mbd4 | Liver | 50 | - | - | 16.15 | - | 
| Mbd4 |Heart | 73 | - | - | 17.17 | - |
| Mbd4 | Eye | 87 | - | - | 16.63 | - |  

Table: Presence or absence of cis-eQTLs for *Ogg1* and *Mbd4* in various tissues identified using GeneNetwork. {#tbl:eqtl-results}

## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>

