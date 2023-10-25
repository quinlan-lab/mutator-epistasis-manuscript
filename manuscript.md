---
title: Epistasis between mutator alleles contributes to germline mutation rate variability in laboratory mice
keywords:
- markdown
- publishing
- manubot
lang: en-US
date-meta: '2023-10-25'
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
  <meta name="dc.title" content="Epistasis between mutator alleles contributes to germline mutation rate variability in laboratory mice" />
  <meta name="citation_title" content="Epistasis between mutator alleles contributes to germline mutation rate variability in laboratory mice" />
  <meta property="og:title" content="Epistasis between mutator alleles contributes to germline mutation rate variability in laboratory mice" />
  <meta property="twitter:title" content="Epistasis between mutator alleles contributes to germline mutation rate variability in laboratory mice" />
  <meta name="dc.date" content="2023-10-25" />
  <meta name="citation_publication_date" content="2023-10-25" />
  <meta property="article:published_time" content="2023-10-25" />
  <meta name="dc.modified" content="2023-10-25T18:33:01+00:00" />
  <meta property="article:modified_time" content="2023-10-25T18:33:01+00:00" />
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
  <link rel="alternate" type="text/html" href="https://quinlan-lab.github.io/mutator-epistasis-manuscript/v/bc944e2344c193b9928ba531ff25ee40619d1f2a/" />
  <meta name="manubot_html_url_versioned" content="https://quinlan-lab.github.io/mutator-epistasis-manuscript/v/bc944e2344c193b9928ba531ff25ee40619d1f2a/" />
  <meta name="manubot_pdf_url_versioned" content="https://quinlan-lab.github.io/mutator-epistasis-manuscript/v/bc944e2344c193b9928ba531ff25ee40619d1f2a/manuscript.pdf" />
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
([permalink](https://quinlan-lab.github.io/mutator-epistasis-manuscript/v/bc944e2344c193b9928ba531ff25ee40619d1f2a/))
was automatically generated
from [quinlan-lab/mutator-epistasis-manuscript@bc944e2](https://github.com/quinlan-lab/mutator-epistasis-manuscript/tree/bc944e2344c193b9928ba531ff25ee40619d1f2a)
on October 25, 2023.
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
     · Funded by NIH/NHGRI R01HG012252
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
     · Funded by NIH/NIGMS R35GM133428; Burroughs Wellcome Career Award at the Scientific Interface; Searle Scholarship; Pew Scholarship; Sloan Fellowship; Allen Discovery Center for Cell Lineage Tracing
  </small>


::: {#correspondence}
✉ — Correspondence possible via [GitHub Issues](https://github.com/quinlan-lab/mutator-epistasis-manuscript/issues)
or email to
Aaron R. Quinlan \<aquinlan@genetics.utah.edu\>, 
Kelley Harris \<harriske@uw.edu\>.


:::


## Abstract {.page_break_before}

Maintaining germline genome integrity is essential and enormously complex. 
Hundreds of proteins are involved in DNA replication and proofreading, and hundreds more are mobilized to repair DNA damage [@PMID:28485537]. 
While loss-of-function mutations in any of the genes encoding these proteins might lead to elevated mutation rates, *mutator alleles* have largely eluded detection in mammals. 

DNA replication and repair proteins often recognize particular sequence motifs or excise lesions at specific nucleotides. 
Thus, we might expect that the spectrum of *de novo* mutations &mdash; that is, the frequency of each individual mutation type (C>T, A>G, etc.) &mdash; will differ between genomes that harbor either a mutator or wild-type allele at a given locus. 
Previously, we used quantitative trait locus mapping to discover candidate mutator alleles in the DNA repair gene *Mutyh* that increased the C>A germline mutation rate in a family of inbred mice known as the BXDs [@PMID:35545679;@PMID:33472028].

In this study we developed a new method, called "aggregate mutation spectrum distance," to detect alleles associated with mutation spectrum variation. 
By applying this approach to mutation data from the BXDs, we confirmed the presence of the germline mutator locus near *Mutyh* and discovered an additional C>A mutator locus on chromosome 6 that overlaps *Ogg1*, a DNA glycosylase involved in the same base-excision repair network as *Mutyh* [@PMID:17581577].
The effect of a chromosome 6 mutator allele depended on the presence of a mutator allele near *Mutyh*, and BXDs with mutator alleles at both loci had even greater numbers of C>A mutations than those with mutator alleles at either locus alone. 
Our new methods for analyzing mutation spectra reveal evidence of epistasis between germline mutator alleles, and may be applicable to mutation data from humans and other model organisms. 



## Introduction

Germline mutation rates reflect the complex interplay between DNA proofreading and repair pathways, exogenous sources of DNA damage, and life-history traits. 
For example, parental age is an important determinant of mutation rate variability; in many mammalian species, the number of germline *de novo* mutations observed in offspring increases as a function of paternal and maternal age [@PMID:28959963;@PMID:31549960;@PMID:35771663;@PMID:32804933;@PMID:31492841].
Rates of germline mutation accumulation are also variable across human families [@PMID:26656846;@PMID:31549960], likely due to either genetic variation or differences in environmental exposures.
Although numerous protein-coding genes contribute to the maintenance of genome integrity, genetic variants that increase germline mutation rates, known as *mutator alleles*, have proven difficult to discover in mammals.

The dearth of observed germline mutators in mammalian genomes is not necessarily surprising, since alleles that lead to elevated germline mutation rates would likely have deleterious consequences and be purged by negative selection if their effect sizes are large [@PMID:27739533].
Moreover, germline mutation rates are relatively low, and direct mutation rate measurements require whole-genome sequencing data from both parents and their offspring.
As a result, large-scale association studies &mdash; which have been used to map the contributions of common genetic variants to many complex traits &mdash; are not currently well-powered to investigate the polygenic architecture of germline mutation rates [@PMID:31964835].  

Despite these challenges, less traditional strategies have been used to identify a small number of mutator alleles in humans, macaques [@doi:10.1101/2023.03.27.534460], and mice. 
By focusing on families with rare genetic diseases, a recent study discovered two mutator alleles that led to significantly elevated rates of *de novo* germline mutation in human genomes [@PMID:35545669]. 
Other groups have observed mutator phenotypes in the germlines and somatic tissues of adults who carry cancer-predisposing inherited mutations in the POLE/POLD1 exonucleases [@PMID:34594041;@PMID:37336879].
Candidate mutator loci were also found by identifying human haplotypes from the Thousand Genomes Project with excess counts of derived alleles in genomic windows [@PMID:28095480].

In mice, a germline mutator allele was recently discovered by sequencing a large family of inbred mice [@PMID:35545679].
Commonly known as the <u>B</u>X<u>D</u>s, these recombinant inbred lines (RILs) were derived from either F2 or advanced intercrosses of C57<u>B</u>L/6J and <u>D</u>BA/2J, two laboratory strains that exhibit significant differences in their germline mutation spectra [@PMID:33472028;@PMID:30753674]. 
The BXDs were maintained via brother-sister mating for up to 180 generations, and each BXD therefore accumulated hundreds or thousands of germline mutations on a nearly-homozygous linear mosaic of parental <u>B</u> and <u>D</u> haplotypes. 
Due to their husbandry in a controlled laboratory setting, the BXDs were largely free from confounding by environmental heterogeneity, and the effects of selection on *de novo* mutations were attenuated by strict inbreeding [@doi:10.1146/annurev.ecolsys.39.110707.173437]. 

In this previous study, whole-genome sequencing data from the BXD family were used to map a quantitative trait locus (QTL) for the C>A mutation rate [@PMID:35545679].
Germline C>A mutation rates were nearly 50% higher in mice with *D* haplotypes at the QTL, likely due to genetic variation in the DNA glycosylase *Mutyh* that reduced the efficacy of oxidative DNA damage repair.
Pathogenic variants of *Mutyh* also appear to act as mutators in normal human germline and somatic tissues [@PMID:35803914;@PMID:30753674].
Importantly, the QTL did not reach genome-wide significance in a scan for variation in overall germline mutation rates, which were only modestly higher in BXDs with *D* alleles, demonstrating the utility of mutation spectrum analysis for mutator allele discovery.
Close examination of the mutation spectrum is likely to be broadly useful for detecting mutator alleles, as genes involved in DNA proofreading and repair often recognize particular sequence motifs or excise specific types of DNA lesions [@PMID:32619789].
Mutation spectra are usually defined in terms of $k$-mer nucleotide context; the 1-mer mutation spectrum, for example, consists of 6 mutation types after collapsing by strand complement (C>T, C>A, C>G, A>T, A>C, A>G), while the 3-mer mutation spectrum contains 96 (each of the 1-mer mutations partitioned by trinucleotide context).

Although mutation spectrum analysis can enable the discovery of mutator alleles that affect the rates of specific mutation types, early implementations of this strategy have suffered from a few drawbacks. 
For example, performing association tests on the rates or fractions of every $k$-mer mutation type can quickly incur a substantial multiple testing burden.
Since germline mutation rates are generally quite low, estimates of $k$-mer mutation type frequencies from individual samples can also be noisy and imprecise.
Moreover, inbreeding duration can vary considerably across samples in populations of RILs; for example, some BXDs were inbred for only 20 generations, while others were inbred for nearly 200.
As a result, the variance of individual $k$-mer mutation rate estimates in those populations will be much higher than if all samples were inbred for the same duration.
We were therefore motivated to develop a statistical method that could overcome the sparsity of *de novo* mutation spectra, eliminate the need to test each $k$-mer mutation type separately, and enable sensitive detection of alleles that influence the germline mutation spectrum.

Here, we present a new mutation spectrum association test, called "aggregate mutation spectrum distance," that minimizes multiple testing burdens and mitigates the challenges of sparsity in *de novo* mutation datasets. 
We leverage this method to re-analyze germline mutation data from the BXD family and find compelling evidence for a second mutator allele that was not detected using previous approaches. 
The new allele appears to interact epistatically with the mutator that was previously discovered in the BXDs, further augmenting the C>A germline mutation rate in a subset of inbred mice. 
Our observation of epistasis suggests that mild DNA repair deficiencies can compound one another, as mutator alleles chip away at the redundant systems that collectively maintain germline integrity. 


## Results

### A novel method for detecting mutator alleles

We developed a statistical method, termed "aggregate mutation spectrum distance" (AMSD), to detect loci that are associated with mutation spectrum variation in recombinant inbred lines (RILs) (Figure {@fig:distance-method}; *Materials and Methods*). 
Our approach leverages the fact that mutator alleles often leave behind distinct and detectable impressions on the *mutation spectrum*, even if they increase the overall mutation rate by a relatively small amount.
Given a population of haplotypes, we assume that each has been genotyped at the same collection of biallelic loci and that each harbors *de novo* mutations which have been partitioned by $k$-mer context (Figure @fig:distance-method).
At every locus, we calculate a cosine distance between the aggregate mutation spectra of haplotypes that inherited either parental allele.
Using permutation tests, we then identify loci at which those distances are larger than what we'd expect by random chance.
To account for polygenic effects on the mutation process that might be shared between BXDs, we also regress the cosine distance at each marker against the genetic similarity between haplotype groups, and assess significance using the fitted residuals (which we call the "adjusted" cosine distances) (*Materials and Methods*).

Using simulated data, we find that our method's power is primarily limited by the initial mutation rate of the $k$-mer mutation type affected by a mutator allele and the total number of *de novo* mutations used to detect it (Figure {@fig:simulations}). 
Given 100 haplotypes with an average of 500 *de novo* germline mutations each, AMSD has approximately 90% power to detect a mutator allele that increases the C>A *de novo* mutation rate by as little as 20%. 
However, the approach has less than 20% power to detect a mutator of identical effect size that augments the C>G mutation rate, since C>G mutations are expected to make up a smaller fraction of all *de novo* germline mutations to begin with. 
Simulations also demonstrate that our approach is well-powered to detect large-effect mutator alleles (e.g., those that increase the mutation rate of a specific $k$-mer by 50%), even with a relatively small number of mutations per haplotype (Figure {@fig:simulations}).
Both AMSD and traditional quantitative trait locus (QTL) mapping have similar power to detect alleles that augment the rates of individual 1-mer mutation types (Figure {@fig:ihd_vs_qtl_power}), but AMSD has a number of potential advantages for mutator allele discovery.
For example, we find that AMSD is better-powered than QTL mapping when the number of simulated *de novo* mutations is allowed to vary (by a factor of 20) across haplotypes (Figure {@fig:ihd_vs_qtl_power_variable_counts}) and when mutator allele frequencies are less than 50% (Figure {@fig:ihd_vs_qtl_power_variable_afs}).
However, we also caution that many of the parameters used in our simulations are specific to the BXD mice (e.g., numbers of haplotypes, average numbers of mutations, expected allele frequencies at markers), and do not necessarily reflect the power of AMSD on other populations. 

![
**Overview of aggregate mutation spectrum distance method for discovering mutator alleles.** 
**a)** A population of four haplotypes has been genotyped at three informative markers ($g_1$ through $g_3$); each haplotype also harbors unique *de novo* germline mutations.
In practice, *de novo* mutations are partitioned by $k$-mer context; for simplicity in this toy example, *de novo* mutations are simply classified into two possible mutation types (grey squares represent C>(A/T/G) mutations, while grey triangles represent A>(C/T/G) mutations).
**b)** At each informative marker $g_n$, we calculate the total number of each mutation type observed on haplotypes that carry either parental allele (i.e., the aggregate mutation spectrum) using all genome-wide *de novo* mutations. 
For example, haplotypes with *A* (orange) genotypes at $g_1$ carry a total of three "triangle" mutations and five "square" mutations, and haplotypes with *B* (green) genotypes carry a total of six triangle and two square mutations.
We then calculate the cosine distance between the two aggregate mutation spectra, which we call the "aggregate mutation spectrum distance." 
Cosine distance can be defined as $1 - \cos(\theta)$, where $\theta$ is the angle between two vectors; in this case, the two vectors are the two aggregate spectra.
We repeat this process for every informative marker $g_n$. 
**c)** To assess the significance of any distance peaks in b), we perform permutation tests. 
In each of $N$ permutations, we shuffle the haplotype labels associated with the *de novo* mutation data, run a genome-wide distance scan, and record the maximum cosine distance encountered at any locus in the scan. 
Finally, we calculate the $1 - p$ percentile of the distribution of those maximum distances to obtain a genome-wide cosine distance threshold at the specified value of $p$.
](images/fig-distance-method.png){#fig:distance-method width=7.5in} 

### Re-identifying a mutator allele on chromosome 4 in the BXDs

We applied our aggregate mutation spectrum distance method to 117 BXDs (*Materials and Methods*) with a total of 65,552 *de novo* germline mutations [@PMID:35545679]. 
Using mutation data that were partitioned by 1-mer nucleotide context, we discovered a locus on chromosome 4 that was significantly associated with mutation spectrum variation (Figure {@fig:distance-results}a; maximum adjusted cosine distance of 1.20e-2 at marker ID `rs27509845`; position 118.28 Mbp in GRCm38/mm10 coordinates; 90% bootstrap confidence interval from 114.79 - 118.75 Mbp). 

![
**Results of aggregate mutation spectrum distance scans in the BXDs.** 
**a)** Adjusted cosine distances between aggregate 1-mer *de novo* mutation spectra on BXD haplotypes (n = 117 haplotypes; 65,552 total mutations) with either *D* or *B* alleles at 7,128 informative markers. 
Cosine distance threshold at p = 0.05 was calculated by performing 10,000 permutations of the BXD mutation data, and is shown as a dotted grey line. 
**b)** Adjusted cosine distances between aggregate 1-mer *de novo* mutation spectra on BXD haplotypes with *D* alleles at `rs27509845` (n = 66 haplotypes; 42,171 total mutations) and either *D* or *B* alleles at 7,063 informative markers. 
Cosine distance threshold at p = 0.05 was calculated by performing 10,000 permutations of the BXD mutation data, and is shown as a dotted grey line.
**c)** Adjusted cosine distances between aggregate 1-mer *de novo* mutation spectra on BXD haplotypes with *B* alleles at `rs27509845` (n = 44 haplotypes; 22,645 total mutations) and either *D* or *B* alleles at 7,063 informative markers. 
Cosine distance threshold at p = 0.05 was calculated by performing 10,000 permutations of the BXD mutation data, and is shown as a dotted grey line.
](images/fig-distance-results.png){#fig:distance-results width=7.5in} 

Using quantitative trait locus (QTL) mapping, we previously identified a nearly-identical locus on chromosome 4 that was significantly associated with the C>A germline mutation rate in the BXDs [@PMID:35545679]. 
This locus overlapped 21 protein-coding genes that were annotated by the Gene Ontology as being involved in "DNA repair," but only one of those genes contained nonsynonymous differences between the two parental strains: *Mutyh*. 
*Mutyh* encodes a protein involved in the base-excision repair of 8-oxoguanine (8-oxoG), a DNA lesion caused by oxidative damage, and prevents the accumulation of C>A mutations [@PMID:28551381;@PMID:28127763;@PMID:17581577]. 
C>A germline mutation fractions are nearly 50% higher in BXDs that inherit *D* genotypes at marker ID `rs27509845` (the marker at which we observed the highest adjusted cosine distance on chromosome 4) than in those that inherit *B* genotypes (Figure @fig:spectra-comparison) [@PMID:35545679].

### An additional germline mutator allele on chromosome 6

After confirming that AMSD could recover the mutator locus overlapping *Mutyh*, we tested its ability to identify additional mutator loci in the BXDs.
To eliminate potential confounding of the mutation spectrum landscape by the large-effect mutator locus on chromosome 4, we performed AMSD scans that were conditional on the presence of either *D* or *B* alleles at `rs27509845`. 
We also hypothesized that such conditioning might reveal epistatic interactions between alleles at the chromosome 4 locus and mutator alleles elsewhere in the genome.
Specifically, we divided the BXDs into those with either *D* (n = 66) or *B* (n = 44) genotypes at `rs27509845` (n = 7 BXDs were heterozygous) and ran an aggregate mutation spectrum distance scan using each group separately (Figure {@fig:distance-results}b-c). 
We excluded the BXD68 RIL from these scans, since we previously found that BXD68 harbors a strain-private C>A mutator allele of even larger effect [@PMID:35545679].

Using the BXDs with *D* genotypes at `rs27509845`, we identified a locus on chromosome 6 that was significantly associated with mutation spectrum variation (Figure {@fig:distance-results}b; maximum adjusted cosine distance of 3.69e-3 at marker `rs46276051`; position 111.27 Mbp in GRCm38/mm10 coordinates; 90% bootstrap confidence interval from 95.01 - 114.02 Mbp).
This signal was specific to BXDs with *D* genotypes at the `rs27509845` locus, as we did not observe any new mutator loci after performing an AMSD scan using BXDs with *B* genotypes at `rs27509845` (Figure {@fig:distance-results}c).
The peak markers on chromosome 4 and 6 did not exhibit strong linkage disequilibrium ($R^2$ = 4e-5).
We also performed QTL scans for the fractions of each 1-mer mutation type using the same mutation data, but none produced a genome-wide significant log-odds score at any locus (Figure {@fig:qtl-scans}; *Materials and Methods*).

We queried the region surrounding the top marker on chromosome 6 (+/- the 90% bootstrap confidence interval) and discovered 64 protein-coding genes, of which four were annotated with a Gene Ontology (GO) [@PMID:10802651;@PMID:33290552] term related to "DNA repair": *Fancd2*, *Ogg1*, *Setmar*, and *Rad18*.
None of the remaining genes were annotated with a cellular function that would obviously contribute to a germline mutator phenotype; however, many of these GO annotations are imperfect and/or incomplete. 
Although we focus our analysis on DNA repair genes, it remains possible that other genes within the confidence interval could underlie the C>A mutator phenotype we identified in the BXDs.

Of the annotated DNA repair genes within the confidence interval, two harbored nonsynonymous differences between the parental C57BL/6J and DBA/2J strains (Table @tbl:nonsyn-diffs).
*Ogg1* encodes a key member of the base-excision repair response to oxidative DNA damage (a pathway that also includes *Mutyh*), and in mice *Setmar* encodes a SET domain-containing histone methyltransferase; both *Ogg1* and *Setmar* are expressed in mouse gonadal cells.
Because the bootstrap can exhibit poor coverage in QTL mapping studies [@PMID:16783000], we also scanned an interval +/- 5 Mbp from the peak AMSD marker on chromosome 6 for additional candidate genes. 
Although the choice of a 10 Mbp interval is somewhat arbitrary, the interval does contain a plausible candidate: *Mbd4*, a protein-coding gene involved in base excision repair that also harbors a non-synonymous difference between the BXD parental strains (Table @tbl:nonsyn-diffs).

| Gene name | Ensembl transcript name | Nucleotide change | Amino acid change | Position in GRCm38/mm10 coordinates | PhyloP conservation score | SIFT prediction | 
| - | - | - | - | - | - | - | 
| *Setmar* | ENSMUST00000049246 | C>T | p.Leu103Phe | chr6:108,075,853 | 0.422 | 0.0 (intolerant/deleterious) |
| *Setmar* | ENSMUST00000049246 | T>G | p.Ser273Arg | chr6:108,076,365 | -0.355 | 0.3 (tolerant/benign) |
| *Ogg1* | ENSMUST00000032406 | A>G | p.Thr95Ala | chr6:113,328,510 | -0.016 | 0.84 (tolerant/benign) | 
| *Mbd4* | ENSMUST00000032469 | C>T | p.Asp129Asn | chr6:115,849,644 | 2.28 | 0.02 (intolerant/deleterious) |

Table: Nonsynonymous mutations in DNA repair genes near the chr6 peak {#tbl:nonsyn-diffs}

We also considered the possibility that expression quantitative trait loci (eQTLs), rather than nonsynonymous mutations, could contribute to the C>A mutator phenotype associated with the locus on chromosome 6. 
Using GeneNetwork [@PMID:27933521] we mapped eQTLs for the five aforementioned DNA repair genes (as well as *Mbd4*) in a number of tissues, though we did not have access to expression data from germline cells. 
Notably, *D* alleles near the cosine distance peak on chromosome 6 were significantly associated with decreased *Ogg1* expression in kidney, liver, hippocampus, and gastrointestinal tissues (Table @tbl:eqtl-results). 
Although these cis-eQTLs are challenging to interpret (given their tissue specificity and our lack of access to germline expression data), the presence of strong-effect cis-eQTLs for *Ogg1* suggests that the C>A mutator phenotype observed in the BXDs may be mediated by regulatory, rather than protein-altering, variants.

Finally, we queried a dataset of structural variants (SVs) identified via high-quality, long-read assembly of inbred laboratory mouse strains [@doi:10.1016/j.xgen.2023.100291] and found 176 large insertions or deletions (>100 bp) within the 90% bootstrap confidence interval around the cosine distance peak on chromosome 6; none overlapped the exonic sequences of protein-coding genes.

<!-- , though none of the genes has a previously annotated role in DNA repair or replication, or in a pathway that would likely affect germline mutation rates. -->

One protein-coding gene involved in DNA repair (*Rad18*) harbored an intronic deletion within the interval on chromosome 6 (chr6:112,629,618-112,636,619); however, additional experimental evidence will be needed to probe the functional impact of this structural variant.

### Evidence of epistasis between germline mutator alleles

Next, we more precisely characterized the effects of the chromosome 4 and 6 mutator alleles on mutation spectra in the BXDs. 
To pinpoint the mutation type(s) that underlied the significant cosine distance peak on chromosome 6, we compared the aggregate counts of each 1-mer mutation type (plus CpG>TpG) on BXD haplotypes with *D* genotypes at `rs27509845` and either *D* or *B* genotypes at `rs46276051`.
We found that C>A mutations were significantly enriched on BXD haplotypes with *D* genotypes at the chromosome 6 mutator locus, relative to those with *B* genotypes ($\chi^2$ statistic = 85.36, p = 2.48e-20).
On average, C>A germline mutation fractions were significantly higher in BXDs with *D* alleles at both mutator loci than in BXDs with *D* alleles at either locus alone (Figure {@fig:spectra-comparison}a and @fig:spectra-comparison-all). 
Among BXDs with *B* alleles at the locus overlapping *Mutyh*, those with *D* alleles on chromosome 6 did not exhibit significantly elevated C>A mutation fractions (Figure {@fig:spectra-comparison}a). 
After controlling for inbreeding duration, we observed that C>A *de novo* mutation counts were always highest in BXDs with *D* alleles at both mutator loci (Figure {@fig:spectra-comparison}b).
After 100 generations of inbreeding, BXDs with *D* alleles at both mutator loci were predicted to have 238.9 C>A mutations (95% CI: 231.4 - 246.4), about 20% more than the 199.0 mutations (95% CI: 193.3 - 204.7) predicted in those with *D* and *B* alleles at the chromosome 4 and chromosome 6 loci, respectively (Figure {@fig:spectra-comparison}b).

We also used SigProfilerExtractor [@PMID:36388765] to assign the germline mutations in each BXD to single-base substitution (SBS) mutation signatures from the COSMIC catalog [@PMID:30371878].
Mutation signatures often reflect specific exogenous or endogenous sources of DNA damage, and the proportions of mutations attributable to particular SBS signatures can suggest a genetic or environmental etiology.
The SBS1, SBS5, and SBS30 mutation signatures were active in nearly all BXDs, regardless of genotypes at the chromosome 4 and 6 mutator loci (Figure {@fig:spectra-comparison}c).
However, the SBS18 signature, which is dominated by C>A mutations and likely reflects unrepaired DNA damage from reactive oxygen species, was almost exclusively active in mice with *D* alleles at the chromosome 4 locus; the highest SBS18 activity was observed in mice with *D* alleles at both mutator loci (Figure {@fig:spectra-comparison}c).
SBS18 activity was lowest in mice with *D* alleles at the chromosome 6 mutator locus alone (Figure {@fig:spectra-comparison}c), further demonstrating that *D* alleles at this locus are not sufficient to cause a mutator phenotype.

To more formally test for statistical epistasis, we fit a generalized (Poisson) linear model predicting counts of C>A mutations in each BXD as a function of genotypes at `rs27509845` and `rs46276051` (the markers with the largest adjusted cosine distance at the two mutator loci); the model also accounted for differences in inbreeding duration and sequencing coverage between the BXDs (*Materials and Methods*). 
A model that included an interaction term between genotypes at the two markers fit the data significantly better than a model including only additive effects (p = 7.92e-7; *Materials and Methods*), indicating that the combined effects of *D* genotypes at both loci exceeded the sum of marginal effects of *D* genotypes at either locus alone.

![
**BXD mutation spectra are affected by alleles at both mutator loci.** 
**a)** C>A *de novo* germline mutation fractions in BXDs with either *D* or *B* genotypes at markers `rs27509845` (chr4 peak) and `rs46276051` (chr6 peak). Distributions of C>A mutation fractions were compared with two-sided Mann-Whitney U-tests; annotated p-values are uncorrected. `B-B` vs. `B-D` comparison: U-statistic = 149.0, p = 7.58e-2; `B-D` vs `D-D` comparison: U-statistic = 21.0, p = 2.61e-8; `D-B` vs `D-D` comparison: U-statistic = 232.5, p = 6.99e-5.
**b)** The count of C>A *de novo* germline mutations in each BXD was plotted against the number of generations for which it was inbred. 
Lines represent predicted C>A counts in each haplotype group from a generalized linear model (Poisson family, identity link), and shading around each line represents the 95% confidence interval.
**c)** Germline mutations in each BXD were assigned to COSMIC SBS mutation signatures using SigProfilerExtractor [@PMID:36388765]. After grouping BXDs by their genotypes at `rs27509845` and `rs46276051`, we calculated the fraction of mutations in each group that was attributed to each signature. The proposed etiologies of each mutation signature are: SBS1 (spontaneous deamination of methylated cytosine nucleotides at CpG contexts), SBS5 (unknown, clock-like signature), SBS18 (damage by reactive oxygen species, related to SBS36 and defective base-excision repair due to loss-of-function mutations in MUTYH), and SBS30 (defective base-excision repair due to NTHL1 mutations).
](images/fig-spectra-comparison.png){#fig:spectra-comparison width=7.5in} 

To explore the effects of the two mutator loci in other inbred laboratory mice, we also compared the germline mutation spectra of Sanger Mouse Genomes Project (MGP) strains [@PMID:21921910]. 
Dumont [@PMID:30753674] previously identified germline mutations that were private to each of the 29 MGP strains; these private variants likely represent recent *de novo* mutations (Figure {@fig:spectra-comparison-mgp}). 
Only two of the MGP strains possess *D* genotypes at both the chromosome 4 and chromosome 6 mutator loci: DBA/1J and DBA/2J. 
As before, we tested for epistasis in the MGP strains by fitting two linear models predicting C>A mutation counts as a function of genotypes at the two mutator loci. 
A model incorporating an interaction term did not fit the MGP data significantly better than a model with additive effects alone (p = 0.806), so we are unable to confirm the signal of epistasis; however, this may be due to the smaller number of MGP strains with *de novo* germline mutation data.

### Some of the candidate mutator alleles are segregating in wild mice 

To determine whether the candidate mutator alleles on chromosome 6 were segregating in natural populations, we queried previously published sequencing data generated from 67 wild-derived mice [@PMID:27622383]. 
These data include three subspecies of *Mus musculus*, as well as the outgroup *Mus spretus*. 
We found that the *Ogg1* *D* allele was segregating at an allele frequency of 0.259 in *Mus musculus domesticus*, the species from which C57BL/6J and DBA/2J derive the majority of their genomes [@PMID:17660819], and was fixed in *Mus musculus musculus*, *Mus musculus castaneus*, and the outgroup *Mus spretus* (Figure @fig:wild-afs).
The *Setmar* p.Ser273Arg *D* allele was also present at an allele frequency of 0.37 in *Mus musculus domesticus*, while *D* alleles at the *Setmar* p.Leu103Phe variant were not observed in any wild *Mus musculus domesticus* animals.
*D* alleles at the *Mbd4* p.Asp129Asn variant were also absent from all wild mouse populations (Figure @fig:wild-afs).


## Discussion

### Epistasis between germline mutator alleles

We have identified a locus on chromosome 6 that amplifies a C>A germline mutator phenotype in the BXDs, a family of inbred mice derived from the laboratory strains DBA/2J and C57BL/6J. 
DBA/2J (*D*) alleles at this locus have no significant effect on C>A mutation rates in mice that also harbor "wild-type" C57BL/6J (*B*) alleles at a previously discovered mutator locus on chromosome 4 [@PMID:35545679].
However, mice with *D* alleles at *both* loci have even higher mutation rates than those with *D* alleles at the chromosome 4 mutator locus alone (Figure @fig:spectra-comparison). 
Epistatic interactions between mutator alleles have been previously documented in yeast [@PMID:16492773] and in human cell lines [@PMID:35859169], but never to our knowledge in a whole-animal context. 

Importantly, we discovered epistasis between germline mutator alleles in an unnatural population of model organisms that have been inbred by brother-sister mating in a highly controlled laboratory environment [@PMID:33472028]. 
This breeding setup has likely attenuated the effects of natural selection on all but the most deleterious alleles [@doi:10.1146/annurev.ecolsys.39.110707.173437], and may have facilitated the fixation of large-effect mutator alleles that would be less common in wild mice. 
Without fine-mapping the chromosome 6 mutator allele, however, we are unable to trace its origin to either a captive breeding colony of laboratory mice or a wild, outbreeding *Mus musculus* population. 
If the mutator allele on chromosome 6 has even a weak deleterious fitness, there might be a greater likelihood that it arose in captivity. 
Indeed, if purifying selection is required to keep mutation rates low, mutational pressure might cause mutation rates to rise in just a few generations of relaxed selection. 
This dynamic may explain the recent discovery of a large-effect mutator allele in a rhesus macaque research colony [@doi:10.1101/2023.03.27.534460], as well as the observation that domesticated animals tend to have higher mutation rates than those in the wild [@PMID:36859541].
Ultimately, although we have not conclusively fine-mapped the chromosome 6 mutator locus to a causal variant, we argue that nonsynonymous or regulatory variants in the DNA glycosylase *Ogg1* are the best candidates. 


### Protein-coding genes that may underlie the chromosome 6 mutator locus

Five protein-coding genes involved in DNA repair overlap the C>A mutator locus on chromosome 6: *Ogg1*, a glycosylase that excises the oxidative DNA lesion 8-oxoguanine (8-oxoG) [@PMID:17581577], *Setmar*, a histone methyltransferase involved in non-homologous end joining (NHEJ) of double-stranded breaks (DSBs) [@PMID:21187428;@PMID:16332963], *Fancd2*, and *Rad18*.
One other DNA repair gene, *Mbd4*, lies just outside of the 90% bootstrap confidence interval on chromosome 6 (but within a 10 Mbp interval around the peak AMSD marker).
We are unable to conclusively determine that one or more of these genes harbors a causal variant underlying the observed C>A mutator phenotype, but we believe that *Ogg1* is the most plausible candidate.
*Ogg1* is a member of the same base-excision repair pathway as *Mutyh* (the gene that likely underlies the chromosome 4 mutator locus), contains a nonsynonymous fixed difference between the C57BL/6J and DBA/2J parental strains, and appears to be regulated by cis-eQTLs across a number of tissues within the BXD cohort.

The C57BL/6J and DBA/2J *Setmar* coding sequences differ by two missense variants (Table @tbl:nonsyn-diffs), one of which is predicted to be deleterious by *in silico* tools.
The primate *SETMAR* ortholog is involved in NHEJ of double-strand breaks, but its role in DNA repair appears to depend on the function of both a SET methyltransferase domain and a *Mariner*-family transposase domain [@PMID:16332963;@PMID:24573677;@PMID:21491884].
Since the murine *Setmar* ortholog lacks the latter element, and because primate *SETMAR* is involved in a DNA repair process that is not expected to affect the rate of C>A mutations, we believe it is unlikely to underlie the epistatic interaction between the chromosome 4 and 6 mutator loci in the BXDs (*Supplementary Information*).
Moreover, we did not observe any significant cis-eQTLs for *Setmar* across a variety of tissues in the BXD cohort (Table @tbl:eqtl-results).
None of the remaining DNA repair genes (*Fancd2* or *Rad18*) contains a nonsynonymous fixed difference between the C57BL/6J and DBA/2J parental strains, and none appear to be regulated by cis-eQTLs that would feasibly lead to a germline C>A mutator phenotype (Table @tbl:eqtl-results); the only significant cis-eQTL we observed was for *Fancd2* in gastrointestinal tissue, at which *D* alleles actually led to *increased* expression.


<!-- We also note that *FANCD2* deficiency in human cancer can lead to increased rates of *de novo* structural variation [@PMID:36450981]. -->

### An *Ogg1* mutator allele might impair the excision of 8-oxoguanine lesions

*Ogg1* is a member of the same base-excision repair (BER) pathway as *Mutyh*, the protein-coding gene we previously implicated as harboring mutator alleles at the locus on chromosome 4 [@PMID:17581577].
Each of these genes has a distinct role in the BER response to oxidative DNA damage, and thereby the prevention of C>A mutations [@PMID:28963982;@PMID:24732879].
Following damage by reactive oxygen species, *Ogg1* is able to recognize and remove 8-oxoguanine lesions that are base-paired with cytosine nucleotides; once 8-oxoG is excised, other members of the BER pathway are mobilized to restore a proper G:C base pair at the site.
If an 8-oxoG lesion is not removed before the cell enters S-phase, adenine can be mis-incorporated opposite 8-oxoG during DNA replication [@PMID:28963982].
If this occurs, *Mutyh* can excise the mispaired adenine, leaving a one-nucleotide gap that is processed and filled with a cytosine by other BER proteins.
The resulting C:8-oxoG base pair can then be "returned" to *Ogg1* for excision and repair.
Defects in the BER response to oxidative damage lead to significantly elevated rates of C>A mutation.
For example, triple-knockout (KO) mice lacking *Ogg1*, *Mutyh*, and *Mth1* (which encodes an enzyme that prevents 8-oxo-dGTP from being incorporated during DNA synthesis [@PMID:8226881]) accumulate a 100-fold excess of 8-oxoG in their gonadal cells [@PMID:24732879].
Almost 99% of *de novo* germline mutations in the *Ogg1/Mutyh/Mth1* triple KO mice are C>A transversions, demonstrating the clear role of 8-oxoG repair in preventing C>A mutation.
Additionally, missense mutations and loss-of-heterozygosity in *Ogg1* have been associated with increased risk of human cancer [@PMID:22829015;@PMID:9662341], and copy-number losses of either *Ogg1* or *Mutyh* are linked to elevated rates of spontaneous C>A mutation in human neuroblastoma [@doi:10.1073/pnas.2007898118]. 

#### Nonsynonymous mutations may underlie the chromosome 6 mutator phenotype

The p.Thr95Ala *Ogg1* missense variant is not predicted to be deleterious by the *in silico* tool SIFT [@PMID:12824425], and occurs at a nucleotide that is not particularly well-conserved across mammalian species (Table @tbl:nonsyn-diffs).
We also observe that the *D* allele at p.Thr95Ala is segregating at an allele frequency of approximately 26% among wild-derived *Mus musculus domesticus* animals, and is fixed in other wild populations of *Mus musculus musculus*, *Mus musculus castaneus*, and *Mus spretus* . 
Although we would expect *a priori* that *Ogg1* deficiency should lead to increased 8-oxoG accumulation and elevated C>A mutation rates, these lines of evidence suggest that p.Thr95Ala is not highly deleterious on its own, and might only exert a detectable effect on the BER gene network when *Mutyh* function is also impaired.
It is also possible that *D* alleles at *Ogg1* lead to a very subtle increase in C>A mutation rates, and we are simply underpowered to detect such a small mutation rate effect in the BXDs.

#### No indication of causal structural variation or mobile element insertions near the chromosome 6 mutator locus

Although we argue above that *Ogg1* is likely the the best candidate gene to explain the new BXD C>A mutator phenotype, we cannot conclusively determine that the p.Thr95Ala missense mutation is a causal allele. 
We previously hypothesized that *Mutyh* missense mutations on *D* haplotypes were responsible for the large-effect C>A mutator phenotype we observed in the BXDs [@PMID:35545679]. 
However, subsequent long-read assemblies of several inbred laboratory mouse strains revealed that this mutator phenotype might be caused by a ~5 kbp mobile element insertion (MEI) within the first intron of *Mutyh* [@doi:10.1016/j.xgen.2023.100291], which is associated with significantly reduced expression of *Mutyh* in embryonic stem cells.
We queried the new high-quality assemblies for evidence of mobile elements or other large structural variants (SVs) in the region surrounding the mutator locus on chromosome 6, but found no similarly compelling evidence that either SVs or MEIs might underlie the mutator phenotype described in this study. 

#### Expression quantitative trait loci (eQTLs) might mediate germline mutator phenotypes in the BXDs

We observed strong-effect cis-eQTLs for *Ogg1* expression across a number of tissues in the BXDs (Table @tbl:eqtl-results).
In each of these tissue types, *D* genotypes were associated with decreased expression of *Ogg1*.
As mentioned above, new evidence from long-read genome assemblies has demonstrated that an intronic mobile element insertion in *Mutyh* may be responsible for decreased *Mutyh* expression, and therefore higher C>A mutation rates, in BXDs with *D* haplotypes at the chromosome 4 mutator locus [@doi:10.1016/j.xgen.2023.100291].
Taken together, these results raise the exciting possibility that the mutator loci on both chromosome 4 and chromosome 6 lead to increased C>A mutation rates by lowering the expression of DNA repair genes in the same base-excision repair network.


### *Mbd4* may buffer the effects of *Mutyh* mutator alleles by triggering apoptosis

As mentioned in the **Results**, *Mbd4* lies just outside of the 90% bootstrap confidence interval on chromosome 6.
Due to the uncertainties associated with bootstrap confidence intervals in QTL mapping [@PMID:16783000], we have included a discussion of the evidence supporting *Mbd4* as a causal gene below.

Unlike the *Ogg1* p.Thr95Ala mutation, the p.Asp129Asn variant in *Mbd4* resides within an annotated protein domain (the *Mbd4* methyl-CpG binding domain), occurs at a nucleotide and amino acid residue that are both well-conserved, and is predicted to be deleterious by SIFT [@PMID:12824425] (Table @tbl:nonsyn-diffs). 
A missense mutation that affects the homologous amino acid in humans (p.Asp142Gly in GRCh38/hg38) is also present on a single haplotype in the Genome Aggregation Database (gnomAD) [@PMID:32461654] and is predicted by SIFT and Polyphen [@PMID:20354512] to be "deleterious" and "probably_damaging" in human genomes, respectively. 

One puzzling observation is that loss-of-function mutations in *Mbd4* are not typically associated with C>A mutator phenotypes. 
Instead, *Mbd4* deficiency is usually implicated in C>T mutagenesis at CpG sites, and we did not detect an excess of C>T mutations in BXDs with *D* alleles at the chromosome 6 mutator locus (Figure @fig:spectra-comparison-all).
However, loss of function mutations in *Mbd4* have also been shown to exacerbate the effects of exogenous DNA damage agents.
For example, mouse embryonic fibroblasts that harbor homozygous *Mbd4* knockouts fail to undergo apoptosis following treatment with a number of chemotherapeutics and mutagenic compounds [@PMID:14614141]. 
Most of these exogenous mutagens cause DNA damage that is normally repaired by mismatch repair (MMR) machinery, but murine intestinal cells with biallelic *Mbd4* LOF mutations also showed a reduced apoptotic response to gamma irradiation, which is repaired independently of the MMR gene *Mlh1* [@PMID:14562041]. 
Homozygous loss of *Mbd4* function also leads to accelerated intestinal tumor formation in mice that harbor an *Apc* allele that predisposes them to intestinal neoplasia [@PMID:12130785], and mice with biallelic truncations of the *Mbd4* coding sequence exhibit modestly increased mutation rates in colon cancer cell lines, including increased C>A mutation rates in certain lines [@PMID:17285135].

Together, these lines of evidence suggest that *Mbd4* can modulate sensitivity to many types of exogenous mutagens, potentially through its role in determining whether cells harboring DNA damage should undergo apoptosis [@PMID:14614141;@PMID:14562041]. 
We speculate that in mice with deficient 8-oxoguanine repair &mdash; caused by a mutator allele in *Mutyh*, for example &mdash; reactive oxygen species (ROS) could cause accumulation of DNA damage in the germline. 
If those germ cells harbor fully functional copies of *Mbd4*, they might be able to trigger apoptosis and partially mitigate the effects of a *Mutyh* mutator allele.
However, mice with reduced activity of both *Mbd4* and *Mutyh* may have a reduced ability to initiate cell death in response to DNA damage; as a result, their germ cells may accumulate even higher levels of ROS-mediated damage, leading to substantially elevated germline C>A mutation rates. 

We anticipate that future experimental work will be able to more conclusively establish a mechanistic explanation for the epistatic interaction between mutator loci described in this paper. 

### Strengths and limitations of the aggregate mutation spectrum distance approach

Our aggregate mutation spectrum distance (AMSD) approach was able to identify a mutator allele that escaped notice using quantitative trait locus (QTL) mapping. 
To more systematically compare the power of AMSD and QTL mapping, we performed simulations under a variety of possible parameter regimes. 
Overall, we found that AMSD and QTL mapping have similar power to detect mutator alleles on haplotypes that each harbor tens or hundreds of *de novo* germline mutations (Figure @fig:ihd_vs_qtl_power).
Nonetheless, only AMSD was able to discover the mutator locus on chromosome 6 in the BXDs, demonstrating that it outperforms QTL mapping in certain experimental systems.
For example, simulations demonstrate that AMSD enjoys greater power than QTL mapping when haplotypes carry variable numbers of mutations that can be leveraged for mutator mapping (Figure @fig:ihd_vs_qtl_power_variable_counts). 
Because the BXDs were generated in six breeding epochs over a period of nearly 40 years, the oldest lines have accumulated orders of magnitude more mutations than the youngest lines; these younger BXDs have much noisier mutation spectra as a result.
While approaches for QTL mapping typically weight the phenotypic measurements of each sample equally, AMSD compares the *aggregate* mutation spectra of haplotypes at every locus, a property that likely increased its power to detect mutators in the BXD dataset.

Another benefit of the AMSD approach is that it obviates the need to perform separate association tests for every possible $k$-mer mutation type, and therefore the need to adjust significance thresholds for multiple tests.
Since AMSD compares the complete mutation spectrum between haplotypes that carry either allele at a site, it would also be well-powered to detect a mutator allele that exerted a coordinated effect on multiple $k$-mer mutation types (e.g., increased the rates of both C>T and C>A mutations). 

<!-- Finally, we find that IHD outperforms QTL mapping when simulated mutators are present at allele frequencies that substantially deviate from 50% ().
This feature of inter-haplotype distance may prove especially useful when mapping mutator alleles in natural, outbreeding populations, in which the effects of negative selection will likely keep mutators at relatively low population frequencies.  -->

However, the AMSD method suffers a handful of drawbacks when compared to QTL mapping.
Popular QTL mapping methods (such as R/qtl2 [@PMID:30591514]) use linear models to test associations between genotypes and phenotypes, enabling the inclusion of additive and interactive covariates, as well as kinship matrices, in QTL scans.
Although we have developed methods to account for inter-sample relatedness in the AMSD approach (*Materials and Methods*), they are not as flexible as similar methods in QTL mapping software.
Additionally, the AMSD method assumes that mutator alleles affect a subset of $k$-mer mutation types; if a mutator allele increased the rates of all mutation types equally on haplotypes that carried it, AMSD would be unable to detect it.

### Discovering mutator alleles in other experimental systems

Our discovery of a second BXD mutator allele underscores the power of recombinant inbred lines (RILs) as a resource for dissecting the genetic architecture of germline mutation rates. 
Large populations of RILs exist for many model organisms, and we anticipate that as whole-genome sequencing becomes cheaper and cheaper, the AMSD method could be useful for future mutator allele discovery outside of the BXDs.
At the same time, RILs are a finite resource that require enormous investments of time and labor to construct. 
If germline mutator alleles are only detectable in these highly unusual experimental populations, we are unlikely to discover more than a small fraction of the mutator alleles that may exist in nature. 

Fortunately, the approach introduced in this paper is readily adaptable to datasets beyond RILs. 
Thousands of human pedigrees have been sequenced in an effort to precisely estimate the rate of human *de novo* germline mutation [@PMID:31549960;@PMID:28959963;@PMID:29700473], and as family sequencing has become a more common step in the diagnosis of many congenital disorders, these datasets are growing on a daily basis. 
Large cohorts of two- or three-generation families are an example of a regime in which AMSD could enjoy high power; by pooling sparse mutation counts across many individuals who share the same candidate mutator allele, even a subtle mutator signal could potentially rise above the noise of *de novo* germline mutation rate estimates.
We note, however, that the aggregate mutation spectrum distance approach will require modification before it can be successfully applied to cohorts of outbred, sexually-reproducing individuals.
AMSD assumes that individuals harbor one of two possible genotypes at each marker, and does not yet account for heterozygous genotypes.
As a result, our method is currently applicable only to resources like the BXD RILs, in which individuals have been inbred for sufficiently long that effectively all genotypes are homozygous.

Selection on germline mutator alleles will likely prevent large-effect mutators from reaching high allele frequencies, but a subset may be detectable by sequencing a sufficient number of human trios [@PMID:35666194]. 
Since germline mutators often seem to exert their effects on a small number of mutation types, mutation spectrum analyses may have greater power to detect the genes that underlie heritable mutation rate variation, even if each gene has only a modest effect on the overall mutation rate per generation. 


## Materials and Methods

### Identifying *de novo* germline mutations in the BXDs

The BXD resource currently comprises a total of 152 recombinant inbred lines (RILs). 
BXDs were derived from either F2 or advanced intercrosses, and subsequently inbred by brother-sister mating for up to 180 generations [@PMID:33472028]. 
BXDs were generated in distinct breeding "epochs," which were each initiated with a distinct cross of C57BL/6J and DBA/2J parents; epochs 1, 2, 4, and 6 were derived from F2 crosses, while epochs 3 and 5 were derived from advanced intercrosses [@PMID:33472028]. 
Previously, we analyzed whole-genome sequencing data from the BXDs and identified candidate *de novo* germline mutations in each line [@PMID:35545679]. 
A detailed description of the methods used for DNA extraction, sequencing, alignment, and variant processing, as well as the characteristics of the *de novo* mutations, are available in a previous manuscript [@PMID:35545679].

Briefly, we identified private single-nucleotide mutations in each BXD that were absent from all other BXDs, as well as from the C57BL/6J and DBA/2J parents. We required each private variant to be meet the following criteria: 

* genotyped as either homozygous or heterozygous for the alternate allele, with at least 90% of sequencing reads supporting the alternate allele

* supported by at least 10 sequencing reads

* Phred-scaled genotype quality of at least 20 

* must not overlap regions of the genome annotated as segmental duplications or simple repeats in GRCm38/mm10

* must occur on a parental haplotype that was inherited by at least one other BXD at the same locus; these other BXDs must be homozygous for the reference allele at the variant site

### A new approach to discover germline mutator alleles

#### Calculating aggregate mutation spectrum distance

We developed a new approach to discover loci that affect the germline *de novo* mutation spectrum in biparental RILs (Figure @fig:distance-method).

We assume that a collection of haplotypes has been genotyped at informative markers, and that *de novo* germline mutations have been identified on each haplotype.

At each informative marker, we divide haplotypes into two groups based on the parental allele that they inherited. 
We then compute a $k$-mer mutation spectrum using the aggregate mutation counts in each haplotype group. 
The $k$-mer mutation spectrum contains the frequency of every possible $k$-mer mutation type in a collection of mutations, and can be represented as a vector of size $6 \times 4^{k - 1}$ after collapsing by strand complement. 
For example, the 1-mer mutation spectrum is a 6-element vector that contains the frequencies of C>T, C>G, C>A, A>G, A>T, and A>C mutations. 
Since C>T transitions at CpG nucleotides are often caused by a distinct mechanism (spontaneous deamination of methylated cytosine), we expand the 1-mer mutation spectrum to include a separate category for CpG>TpG mutations [@PMID:19488047].

At each marker, we then compute the cosine distance between the two aggregate spectra.
The cosine distance between two vectors $\mathbf{A}$ and $\mathbf{B}$ is defined as 

$$D^C = 1 - \frac{\mathbf{A} \cdot \mathbf{B}}{||\mathbf{A}|| \ ||\mathbf{B}||}$$

where $||\mathbf{A}||$ and $||\mathbf{B}||$ are the $L^2$ (or Euclidean) norms of $\mathbf{A}$ and $\mathbf{B}$, respectively. 
The cosine distance metric has a number of favorable properties for comparing mutation spectra. 
Since it adjusts for the magnitude of the two input vectors, cosine distance can be used to compare two spectra with unequal total mutation counts (even if those total counts are relatively small). 
Additionally, by calculating the cosine distance between mutation spectra, we avoid the need to perform separate comparisons of mutation counts at each individual $k$-mer mutation type. 

Inspired by methods from QTL mapping [@PMID:7851788;@PMID:30591514], we use permutation tests to establish genome-wide cosine distance thresholds. 
In each of $N$ permutation trials, we randomly shuffle the per-haplotype mutation data such that haplotype labels no longer correspond to the correct mutation counts. 
Using the shuffled mutation data, we perform a genome-wide scan as described above, and record the maximum cosine distance observed at any locus. 
After $N$ permutations (usually 10,000), we compute the $1 - p$ percentile of the distribution of maximum statistics, and use that percentile value as a genome-wide significance threshold (for example, at $p = 0.05$).

#### Estimating confidence intervals around AMSD peaks

If we identified an adjusted cosine distance peak on a particular chromosome, we used a bootstrap resampling approach [@PMID:8725246] to estimate confidence intervals.
In each of $N = 10,000$ trials, we resampled the mutation spectrum data and corresponding marker genotypes (on the chromosome of interest) with replacement.
Using those resampled spectra and genotypes, we performed an aggregate mutation spectrum distance scan on the chromosome of interest and recorded the position of the marker with the largest adjusted cosine distance value.
We then defined a 90% confidence interval by finding two marker locations between which 90% of all $N$ bootstrap samples produced a peak cosine distance value. 
In other words, we estimated the bounds of the 90% confidence interval by finding the markers that defined the 5th and 95th percentiles of the distribution of maximum adjusted cosine distance values across $N$ bootstrap trials.
We note, however, that the bootstrap can exhibit poor performance in QTL mapping studies [@PMID:16783000]; namely, bootstrap confidence intervals tend to be larger than those estimated using either a "LOD drop" method or a Bayes credible interval, and can exhibit poorer-than-expected coverage (a measure of whether the confidence interval contains the true QTL location).

#### Accounting for relatedness between strains 

We expect each BXD to derive approximately 50% of its genome from C57BL/6J and 50% from DBA/2J. 
As a result, every pair of BXDs will likely have identical genotypes at a fraction of markers. 
Pairs of more genetically similar BXDs may also have more similar mutation spectra, potentially due to shared polygenic effects on the mutation process. 
Therefore, at a given marker, if the BXDs that inherited *D* alleles are more genetically dissimilar from those that inherited *B* alleles (considering all loci throughout the genome in our measurement of genetic similarity), we might expect the aggregate mutation spectra in the two groups to also be more dissimilar. 

We implemented a simple approach to account for these potential issues of relatedness. 
At each marker $g_i$, we divide BXD haplotypes into two groups based on the parental allele they inherited. 
As before, we first compute the aggregate mutation spectrum in each group of haplotypes and calculate the cosine distance between the two aggregate spectra ($D^{C}_{i}$). 
Then, within each group of haplotypes, we calculate the allele frequency of the *D* allele at every marker along the genome to obtain a vector of length $n$, where $n$ is the number of genotyped markers. 
To quantify the genetic similarity between the two groups of haplotypes, we calculate the Pearson correlation coefficient $r_i$ between the two vectors of marker-wide *D* allele frequencies. 

Put another way, at every marker $g_i$ along the genome, we divide BXD haplotypes into two groups and compute two metrics: $D^{C}_{i}$ (the cosine distance between the two groups' aggregate spectra) and $r_i$ (the correlation between genome-wide *D* allele frequencies in the two groups). 
To control for the potential effects of genetic similarity on cosine distances, we regress $\left(D^C_{1}, D^C_{2}, \ldots D^C_{n} \right)$ on $\left( r_1, r_2, \ldots r_n \right)$ for all $n$ markers using an ordinary least-squares model.
We then use the residuals from the fitted model as the "adjusted" cosine distance values for each marker. 
If genome-wide genetic similarity between haplotypes perfectly predicts cosine distances at each marker, these residuals will all be 0 (or very close to 0). 
If genome-wide genetic similarity has no predictive power, the residuals will simply represent the difference between the observed cosine distance at a single marker and the marker-wide mean of cosine distances.

#### Accounting for BXD population structure due to breeding epochs

The current BXD family was generated in six breeding "epochs."
As discussed previously, each epoch was initiated with a distinct cross of C57BL/6J and DBA/2J parents; BXDs in four of the epochs were generated following F2 crosses of C57BL/6J and DBA/2J, and BXDs in the other two were generated following advanced intercrosses.
Due to this breeding approach the BXD epochs differ from each other in a few important ways.
For example, BXDs derived in epochs 3 and 5 (i.e., from advanced intercross) harbor larger numbers of fixed recombination breakpoints than those from epochs 1, 2, 4, and 6 [@PMID:33472028].
Although the C57BL/6J and DBA/2J parents used to initialize each epoch were completely inbred, they each possessed a small number unique *de novo* germline mutations that were subsequently inherited by many of their offspring.
A number of these "epoch-specific" variants have also been linked to phenotypic variation observed between BXDs from different epochs [@PMID:33472028;@PMID:31274109;@PMID:30984232;@PMID:31057322].

To account for potential population structure, as well as these epoch-specific effects, we introduced the ability to perform stratified permutation tests in the aggregate mutation spectrum distance approach.
Normally, in each of *N* permutations we shuffle the per-haplotype mutation spectrum data such that haplotype labels no longer correspond to the correct mutation spectra (i.e., shuffle mutation spectra *across* epochs).
In the stratified approach, we instead shuffle per-haplotype mutation data *within* epochs, preserving epoch structure while still enabling mutation spectra permutations.

> We used this epoch-aware approach for all permutation tests presented in this manuscript.


#### Implementation and source code

The aggregate mutation spectrum distance method was implemented in Python, and relies heavily on the following Python libraries: `numpy`, `pandas`, `matplotlib`, `scikit-learn`, `pandera`, `seaborn`, and `numba` [@doi:10.1038/s41586-020-2649-2;@doi:10.5281/zenodo.3509134;@doi:10.1109/MCSE.2007.55;@url:https://jmlr.csail.mit.edu/papers/v12/pedregosa11a.html;@doi:10.25080/Majora-342d178e-010;@doi:10.21105/joss.03021;@doi:10.1145/2833157.2833162].

The code underlying AMSD, as well as documentation of the method, is available on GitHub (https://github.com/quinlan-lab/proj-mutator-mapping). We have also deposited a reproducible Snakemake [@doi:10.12688/f1000research.29032.1] workflow for running reproducing all analyses and figures presented in the manuscript.

### Simulations to assess the power of the aggregate mutation spectrum distance approach

We performed a series of simple simulations to estimate our power to detect alleles that affect the germline mutation spectrum using the aggregate mutation spectrum distance method.

#### Simulating genotypes 

First, we simulate genotypes on a population of haplotypes at a collection of sites.
We define a matrix $G$ of size $(s, h)$, where $s$ is the number of sites and $h$ is the number of haplotypes. 
We assume that every site is biallelic, and that the minor allele frequency at every site is 0.5. 
For every entry $G_{i,j}$, we take a single draw from a uniform distribution in the interval $[0.0, 1.0)$. 
If the value of that draw is less than 0.5, we assign the value of $G_{i,j}$ to be $1$. 
Otherwise, we assign the value of $G_{i,j}$ to be $0$. 

#### Defining expected mutation type probabilities

Next, we define a vector of 1-mer mutation probabilities:

$$P = \left( 0.29, \ 0.17, \ 0.12, \ 0.075, \ 0.1, \ 0.075, \ 0.17 \right)$$

These probabilities sum to 1 and roughly correspond to the expected frequencies of C>T, CpG>TpG, C>A, C>G, A>T, A>C, and A>G *de novo* germline mutations in mice, respectively [@PMID:31492841].
If we are simulating the 3-mer mutation spectrum, we modify the vector of mutation probabilities $P$ to be length 96, and assign every 3-mer mutation type a value of $\frac{P_c}{16}$, where $P_c$ is the probability of the "central" mutation type associated with the 3-mer mutation type. 
In other words, each of the 16 possible N<ins>C</ins>N>N<ins>T</ins>N 3-mer mutation types would be assigned a mutation probability of $\frac{P_c}{16} = \frac{0.46}{16} = 0.02875$.
We then generate a vector of lambda values by scaling the mutation probabilities by the number of mutations we wish to simulate ($m$):

$$\lambda = Pm$$

We also create a second vector of lambda values ($\lambda^{\prime}$), in which we multiply the $\lambda$ value of a single mutation type by the mutator effect size $e$. 

Rather than simulate the same mean number of mutations ($m$) on every haplotype, we also performed a series of simulations in which the mean number of mutations on each haplotype was allowed to vary.
The BXD RILs were inbred for variable numbers of generations, and each BXD therefore accumulated a variable number of *de novo* germline mutations [@PMID:35545679].
To more closely approximate the BXD haplotypes, we performed simulations in which the number of mutations ($m$) on each haplotype was drawn from a uniform distribution from $m$ to $20m$.
In other words, we created a vector of mutation counts $M$ containing $h$ evenly-spaced integers from $m$ to $20m$, where $h$ is the number of simulated haplotypes.
Thus, if we simulated between 100 and 2,000 mutations on 50 haplotypes, the $i$th entry of $M$ would be $100 + \frac{(2,000 - 100)}{50}i$.
Each haplotype's mean number of mutations was then assigned by looking up the haplotype's index $i$ in $M$.


In our simulations, we assume that genotypes at a single site (the "mutator locus") are associated with variation in the mutation spectrum. 
That is, at a single site $s_i$, all of the haplotypes with $1$ alleles should have elevated rates of a particular mutation type and draw their mutation counts from $\lambda^{\prime}$, while all of the haplotypes with $0$ alleles should have "wild-type" rates of that mutation type and draw their mutation counts from $\lambda$.
We therefore pick a random site $s_i$ to be the "mutator locus," and identify the indices of haplotypes in $G$ that were assigned $1$ alleles at $s_i$.
We call these indices $h_{mut}$.

#### Simulating mutation spectra

To simulate the mutation spectrum on our toy population of haplotypes, we define a matrix $C$ of size $(h, n)$, where $n = 6 \times 4^{k - 1}$ (or if $k = 1$ and we include CpG>TpG mutations, $6 \times 4^{k - 1} + 1$).

Then, we populate the matrix $C$ separately for *mutator* and *wild-type* haplotypes.
For every row $i$ in the matrix (i.e., for every haplotype), we first ask if $i$ is in $h_{mut}$ (that is, if the haplotype at index $i$ was assigned a $1$ allele at the "mutator locus"). 
If so, we set the values of $C_i$ to be the results of a single Poisson draw from $\lambda^{\prime}$. 
If row $i$ is not in $h_{mut}$, we set the values of $C_i$ to be the results of a single Poisson draw from $\lambda$.

#### Assessing power to detect a simulated mutator allele using AMSD

For each combination of parameters (number of simulated haplotypes, number of simulated markers, mutator effect size, etc.), we run 100 independent trials.
In each trial, we simulate the genotype matrix $G$ and the mutation counts $C$.
We calculate a "focal" cosine distance as the cosine distance between the aggregate mutation spectra of haplotypes with either genotype at $s_i$ (the site at which we artificially simulated an association between genotypes and mutation spectrum variation).
We then perform an aggregate mutation spectrum distance scan using $N = 1,000$ permutations.
If fewer than 5% of the $N$ permutations produced a cosine distance greater than or equal to the focal distance, we say that the approach successfully identified the mutator allele in that trial. 

#### Assessing power to detect a simulated mutator allele using quantitative trait locus (QTL) mapping

Using simulated data, we also assessed the power of traditional quantitative trait locus (QTL) mapping to detect a locus associated with mutation spectrum variation. 
As described above, we simulated both genotype and mutation spectra for a population of haplotypes under various conditions (number of mutations per haplotype, mutator effect size, etc.).
Using those simulated data, we used R/qtl2 [@PMID:30591514] to perform a genome scan for significant QTL as follows; we assume that the simulated genotype markers are evenly spaced (in physical Mbp coordinates) on a single chromosome.
First, we calculate the fraction of each haplotype's *de novo* mutations that belong to each of the $6 \times 4^{k-1}$ possible $k$-mer mutation types.
We then convert the simulated genotypes at each marker to genotype probabilities using the `calc_genoprob` function in R/qtl2, with `map_function = "c-f"` and `error_prob = 0`.
For every $k$-mer mutation type, we use genotype probabilities and per-haplotype mutation fractions to perform a scan for QTL with the `scan1` function; to make the results more comparable to those from the AMSD method, we do not include any covariates or kinship matrices in these QTL scans.
We then use the `scan1perm` function to perform 1,000 permutations of the per-haplotype mutation fractions and calculate log-odds (LOD) thresholds for significance.
We consider the QTL scan to be "successful" if it produces a LOD score above the significance threshold (defined using $\alpha = \frac{0.05}{7}$) for the marker at which we simulated an association with mutation spectrum variation.

**Note**: In our simulations, we augment the mutation rate of a single $k$-mer mutation type on haplotypes carrying the simulated mutator allele.
However, in an experimental setting, we would not expect to have *a priori* knowledge of the mutation type affected by the mutator.
Thus, by using an alpha threshold of 0.05 in our simulations, we would likely over-estimate the power of QTL mapping for detecting the mutator.
Since we would need to perform 7 separate QTL scans (one for each 1-mer mutation type plus CpG>TpG) in an experimental setting, we calculate QTL LOD thresholds at a Bonferroni-corrected alpha value of $\alpha = \frac{0.05}{7}$.


### Applying the aggregate mutation spectrum distance method to the BXDs

We downloaded previously-generated BXD *de novo* germline mutation data from the GitHub repository associated with our previous manuscript, which was also archived at Zenodo [@url:https://github.com/tomsasani/bxd_mutator_manuscript;@doi:10.5281/zenodo.5941048;@PMID:35545679], and downloaded a CSV file of BXD genotypes at ~7,300 informative markers from GeneNetwork [@url:http://gn1.genenetwork.org/dbdoc/BXDGeno.html;@PMID:27933521]. 
We also downloaded relevant metadata about each BXD from the manuscript describing the updated BXD resource [@PMID:33472028]. 
These files are included in the GitHub repository associated with this manuscript.

As in our previous manuscript [@PMID:35545679], we included mutation data from a subset of the 152 BXDs in our aggregate mutation spectrum distance scans. 
Specifically, we removed BXDs that were backcrossed to a C57BL/6J or DBA/2J parent at any point during the inbreeding process (usually, in order to rescue that BXD from inbreeding depression [@PMID:33472028]).
We also removed BXD68 from our genome-wide scans, since we previously discovered a hyper-mutator phenotype in that line; the C>A germline mutation rate in BXD68 is over 5 times the population mean, likely due to a private deleterious nonsynonymous mutation in *Mutyh* [@PMID:35545679]. 
In our previous manuscript, we removed any BXDs that had been inbred for fewer than 20 generations, as it takes approximately 20 generations of strict brother-sister mating for an RIL genome to become >98% homozygous [@url:https://link.springer.com/book/10.1007/978-1-349-04904-2]. 
As a result, any potential mutator allele would almost certainly be either fixed or lost after 20 generations; if fixed, the allele would remain linked to any excess mutations it causes for the duration of subsequent inbreeding.
In other words, the *de novo* mutations present in the genome of a "young" BXD (i.e., a BXD that was inbred for fewer than 20 generations) would not reflect a mutator allele's activity as strongly as the mutations present in the genome of a much older BXD.
This presented a challenge when we used quantitative trait locus mapping to discover mutator alleles in our previous manuscript, since the phenotypes (i.e., C>A mutation rates) of young and old BXDs were weighted equally; thus, we simply removed the younger BXDs from our analysis to avoid using their especially noisy mutation spectra.
Since AMSD computes an *aggregate* mutation spectrum using all BXDs that inherited a particular allele at a locus, and can overcome the sparsity and noise of individual mutation spectra, we chose to include these younger BXDs in our genome-wide scans in this study.

In total, we included 117 BXDs in our genome-wide scans.

### Identifying candidate single-nucleotide mutator alleles overlapping the chromosome 6 peak

We investigated the region implicated by our aggregate mutation spectrum distance approach on chromosome 6 by subsetting the joint-genotyped BXD VCF file (European Nucleotide Archive accession PRJEB45429 [@url:https://www.ebi.ac.uk/ena/browser/view/PRJEB45429]) using `bcftools` [@PMID:33590861]. 
We defined the candidate interval surrounding the cosine distance peak on chromosome 6 as the 90% bootstrap confidence interval (extending from approximately 95 Mbp to 114 Mbp).
To predict the functional impacts of both single-nucleotide variants and indels on splicing, protein structure, etc., we annotated variants in the BXD VCF using the following `snpEff` [@PMID:22728672] command: 

```
 java -Xmx16g -jar /path/to/snpeff/jarfile GRCm38.75 /path/to/bxd/vcf > /path/to/uncompressed/output/vcf
```

and used `cyvcf2` [@PMID:28165109] to iterate over the annotated VCF file in order to identify nonsynonymous fixed differences between the parental C57BL/6J and DBA/2J strains.

### Identifying candidate structural variant alleles overlapping the chromosome 6 peak

We downloaded summary VCFs containing insertion, deletion and inversion structural variants (identified via high-quality, long-read assembly of inbred laboratory mouse strains [@doi:10.1016/j.xgen.2023.100291]) from the Zenodo link associated with the Ferraj et al. manuscript: https://doi.org/10.5281/zenodo.7644286.

We then downloaded a TSV file containing RefSeq gene predictions in GRCm39/mm39 from the UCSC Table Browser [@PMID:14681465], and used the `bx-python` library [@url:https://github.com/bxlab/bx-python] to intersect the interval spanned by each structural variant with the intervals spanned by the `txStart` and `txEnd` of every RefSeq entry.

We queried all structural variants within the 90% bootstrap confidence interval on chromosome 6.

### Extracting mutation signatures 

We used SigProfilerExtractor (v.1.1.21) [@PMID:30371878] to extract mutation signatures from the BXD mutation data. After converting the BXD mutation data to the "matrix" input format expected by SigProfilerExtractor, we ran the `sigProfilerExtractor` method as follows:

```python
# install the mm10 mouse reference data
genInstall.install('mm10')

# run mutation signature extraction
sig.sigProfilerExtractor(
    'matrix',
    /path/to/output/directory,
    /path/to/input/mutations,
    maximum_signatures=10,
    nmf_replicates=100,
    opportunity_genome="mm10",
)
```

### Comparing mutation spectra between Mouse Genomes Project strains

We downloaded mutation data from a previously published analysis [@PMID:30753674] (Supplementary File 1, Excel Table S3) that identified strain-private mutations in 29 strains that were originally whole-genome sequenced as part of the Sanger Mouse Genomes (MGP) project [@PMID:21921910]. 
When comparing counts of each mutation type between MGP strains that harbored either *D* or *B* alleles at the chromosome 4 or chromosome 6 mutator loci, we adjusted mutation counts by the number of callable A, T, C, or G nucleotides in each strain as described previously [@PMID:35545679].

### Querying GeneNetwork for eQTLs at the mutator locus

We used the online GeneNetwork resource [@PMID:27933521], which contains array- and RNA-seq-derived expression measurements in a wide variety of tissues, to find *cis*-eQTLs for the DNA repair genes we implicated under the cosine distance peak on chromosome 6. 
On the GeneNetwork homepage (genenetwork.org), we selected the "BXD Family" **Group** and used the **Type** dropdown menu to select each of the specific expression datasets described in Table @tbl:eqtl-provenance. 
In the **Get Any** text box, we then entered the listed gene name and clicked **Search**. 
After selecting the appropriate trait ID on the next page, we used the **Mapping Tools** dropdown to run Hayley-Knott regression [@PMID:16718932] with default parameters: 1,000 permutations, interval mapping, no cofactors, and WGS-based genotypes (2022). 

If we discovered a significant cis-eQTL for the gene of interest (that is, a locus on chromosome 6 with an LRS greater than or equal to the "significant LRS" genome-wide threshold), we then performed a second genome-wide association test for the trait of interest using GEMMA [@PMID:2453419] with the following parameters: WGS-based marker genotypes, a minor allele frequency threshold of 0.05, and leave-one-chromosome-out (LOCO).
By using both Haley-Knott regression and GEMMA, we could first discover loci that exceeded a genome-wide LRS threshold, and then more precisely estimate the effect of those loci on gene expression [@doi:10.1101/2020.12.23.424047].

The exact names of the expression datasets we used for each tissue are shown in Table @tbl:eqtl-provenance below:

| Tissue name | Complete name of GeneNetwork expression data | 
| - | - | 
| Kidney | `Mouse kidney M430v2 Sex Balanced (Aug06) RMA` | 
| Gastrointestinal | `UTHSC Mouse BXD Gastrointestinal Affy MoGene 1.0 ST Gene Level (Apr14) RMA` |
| Hematopoetic stem cells | `UMCG Stem Cells ILM6v1.1 (Apr09) transformed` | 
| Spleen | `UTHSC Affy MoGene 1.0 ST Spleen (Dec10) RMA` |  
| Liver | `UTHSC BXD Liver RNA-Seq Avg (Oct19) TPM Log2` | 
| Heart | `NHLBI BXD All Ages Heart RNA-Seq (Nov20) TMP Log2 **` | 
| Hippocampus | `Hippocampus Consortium M430v2 (Jun06) RMA` |

Table: Names of gene expression datasets used for each tissue type on GeneNetwork {#tbl:eqtl-provenance}

### Calculating the frequencies of candidate mutator alleles in wild mice 

To determine the frequencies of the *Ogg1* and *Setmar* nonsynonymous mutations in other populations of mice, we queried a VCF file containing genome-wide variation in 67 wild-derived mice from four species of *Mus* [@PMID:27622383]. 
We calculated the allele frequency of each nonsynonymous mutation in each of the four species or subspecies (*Mus musculus domesticus*, *Mus musculus musculus*, *Mus musculus castaneus*, and *Mus spretus*), including genotypes that met the following criteria:

* supported by at least 10 sequencing reads 

* Phred-scaled genotype quality of at least 20

### Testing for epistasis between the two mutator loci

To test for statistical epistasis between the mutator loci on chromosome 4 and chromosome 6, we modeled C>A mutation rates in the BXDs as a function of genotypes at either locus. 
Specifically, we tested for statistical interaction between genotypes by fitting a generalized linear model in the R statistical language as follows:

```R
m1 <- glm(Count ~ offset(log(ADJ_AGE)) + Genotype_A * Genotype_B, data = data, family=poisson())
```

In this model, `Count` is the count of C>A *de novo* mutations observed in each BXD. 
`ADJ_AGE` is the product of the number of "callable" cytosine/guanine nucleotides in each BXD (i.e., the total number of cytosines/guanines covered by at least 10 sequencing reads) and the number of generations for which the BXD was inbred. 
We included the logarithm of `ADJ_AGE` as an "offset" in order to model the response variable as a rate (expressed per base-pair, per generation) rather than an absolute count; the BXDs differ in both their durations of inbreeding and the proportions of their genomes that were sequenced to sufficient depth, which influences the number of mutations we observe in each BXD. 
The `Genotype_A` and `Genotype_B` terms represent the genotypes of BXDs at markers `rs27509845` and `rs46276051` (the markers with peak cosine distances on chromosomes 4 and 6 in the two aggregate mutation spectrum distance scans). 
We limited our analysis to the n = 108 BXDs that were homozygous at both sites, allowing us to model genotypes at either locus as binary variables ("B" or "D"). 
Using analysis of variance (ANOVA), we then compared the model including an interaction effect to a model including only additive effects:

```R
m2 <- glm(Count ~ offset(log(ADJ_AGE)) + Genotype_A + Genotype_B, data = data, family=poisson())
```

```R
anova(m1, m2, test="Chisq")
```

If model `m1` is a significantly better fit to the data than `m2`, we can reject the null hypothesis that the effect of *D* genotypes at both markers is equal to the sum of the marginal effects of *D* genotypes at either `rs27509845` or `rs46276051`.
In other words, if `m1` is a better fit than `m2`, then the combined effect of *D* genotypes at both markers is non-additive, and indicative of statistical epistasis.

We tested for epistasis in the Sanger Mouse Genomes Project (MGP) strains using a nearly-identical approach. 
In this analysis, we fit two models as follows:

```R
m1 <- glm(Count ~ offset(log(CALLABLE_C)) + Genotype_A * Genotype_B, data = data, family=poisson())

m2 <- glm(Count ~ offset(log(CALLABLE_C)) + Genotype_A + Genotype_B, data = data, family=poisson())
```

where `Count` is the count of strain-private C>A mutations observed in each MGP strain [@PMID:30753674]. 
The `CALLABLE_C` term represents the total number of cytosine and guanine nucleotides that were accessible for mutation calling in each strain, and the `Genotype_A` and `Genotype_B` terms represent MGP genotypes at the chromosome 4 and chromosome 6 mutator loci, respectively. 
We compared the two models using ANOVA as described above.






## Acknowledgments

We thank Robert W. Williams (University of Tennessee Health Sciences Center) and Don F. Conrad (Oregon Health & Science University) for very helpful comments and feedback on a draft of this manuscript.

## Supplementary information {.page_break_before}

### Missense mutations in *Setmar* are unlikely to contribute to epistasis in the BXDs

Unlike *Ogg1*, *Setmar* does not participate directly in base-excision repair, though its primate ortholog plays an indirect role in the repair of double-stranded DNA breaks via non-homologous end joining (NHEJ). 
In anthropoid primates, *SETMAR* encodes a fusion of two functional domains: a SET domain-containing histone methyltransferase and a transposase domain from the *Mariner* family (MAR) [@PMID:16672366]; the mouse *Setmar* ortholog only encodes the histone methyltransferase domain.
In human cell lines, *SETMAR* localizes to induced double-strand breaks (DSBs) and dimethylates nearby H3K36, which promotes the recruitment of DNA repair components involved in NHEJ to the DSB [@PMID:21187428].
There is also evidence that overexpression of *SETMAR* (also known as *Metnase*) improves the efficiency of NHEJ [@PMID:16332963] and leads to increased cell survival following exposure to ionizing radiation [@PMID:16332963].
Point mutations in either the SET or MAR domains significantly reduced the ability of *SETMAR* to promote non-homologous end joining and DNA repair [@PMID:16332963;@PMID:24573677;@PMID:21491884], suggesting that both domains are needed for its role in DNA repair.
Another study found that overexpression of the isolated SET and MAR domains, but not of wild-type *SETMAR*, had a modest effect on NHEJ repair; overexpression of the SET domain slightly *decreased* NHEJ repair of a linearized plasmid in human cells, while overexpression of the *Mariner*-derived domain increased NHEJ relative to controls [@PMID:31238295].

Taken together, these results suggest that both the SET and transposase domains of primate *SETMAR* are important for *SETMAR*-mediated DNA repair. 
The p.Leu103Phe missense mutation that differentiates C57BL/6J and DBA/2J (Table @tbl:nonsyn-diffs) resides within the *Setmar* pre-SET domain and occurs at an amino acid residue that is predicted to be deleterious by SIFT [@PMID:12824425].
However, since the mouse *Setmar* ortholog lacks the *Mariner*-derived domain, we believe that the the p.Leu103Phe or p.Ser273Arg missense mutations are unlikely to affect C>A mutation rates in the BXDs. 
Moreover, we believe that the documented mutator phenotypes associated with *Ogg1*, as well as that gene's known role in base-excision repair, make it  more likely candidate to underlie the epistatic interaction with *Mutyh* we observed in this study.

### Supplementary Figures

![
**Simulations to assess the power of the aggregate mutation spectrum distance method.** 
In each of 50 trials, we simulated genotypes at 1,000 biallelic loci on a toy population of either 50 or 100 haplotypes as follows.
At every locus on every haplotype, we drew a single floating point value from a uniform distribution $[0, 1)$.
If that value was less than or equal to 0.5, we set the allele to be "A"; otherwise, we set the allele to be "B".
In each trial, we also simulated *de novo* germline mutations on the population of haplotypes, such that at a single locus $g_i$, we augmented the mutation rate of a particular $k$-mer by the specified effect size (an effect size of 1.5 indicates a 50% increase in the mutation rate) on haplotypes carrying "A" alleles.
We then applied the aggregate mutation spectrum distance method to these simulated data and asked if the adjusted cosine distance at locus $g_i$ was greater than expected by chance. 
Given a specific combination of parameters, the y-axis denotes the fraction of 50 trials in which the simulated mutator allele could be detected at a significance threshold of p = 0.05.
Shaded areas indicate the 95% bootstrap confidence interval surrounding that estimate.
](images/fig-power-simulations.png){#fig:simulations tag="1-figure supplement 1" width=7.5in} 

![
**Comparing power between the aggregate mutation spectrum distance method and QTL mapping.** 
In each of 50 trials, we simulated genotypes at 1,000 biallelic loci on a toy population of 100 haplotypes as follows.
At every locus on every haplotype, we drew a single floating point value from a uniform distribution $[0, 1)$.
If that value was less than or equal to 0.5, we set the allele to be "A"; otherwise, we set the allele to be "B".
In each trial, we also simulated *de novo* germline mutations on the population of haplotypes, such that at a single locus $g_i$, we augmented the rate of the specified mutation type by the specified effect size (an effect size of 1.5 indicates a 50% increase in the mutation rate) on haplotypes carrying "A" alleles.
We then applied the aggregate mutation spectrum distance method to these simulated data and asked if the adjusted cosine distance at locus $g_i$ was greater than expected by chance. 
Similarly, in each trial, we used R/qtl2 to perform a genome scan for QTL and asked if the log-odds score at $g_i$ was greater than expected by chance.
Given a specific combination of parameters, the y-axis denotes the fraction of 50 trials in which the simulated mutator allele could be detected at a significance threshold of p = 0.05 (for AMSD) or at an alpha of $\frac{0.05}{7}$ (for QTL mapping).
Shaded areas indicate the 95% bootstrap confidence interval surrounding that estimate.
](images/fig-power-comparison.png){#fig:ihd_vs_qtl_power tag="1-figure supplement 2" width=7.5in} 

![
**Comparing power between the aggregate mutation spectrum distance method and QTL mapping with variable counts of simulated mutations.** 
In each of 50 trials, we simulated genotypes at 1,000 biallelic loci on a toy population of 50 or 100 haplotypes as follows.
At every locus on every haplotype, we drew a single floating point value from a uniform distribution $[0, 1)$.
If that value was less than or equal to 0.5, we set the allele to be "A"; otherwise, we set the allele to be "B".
In each trial, we also simulated *de novo* germline mutations on the population of haplotypes, such that at a single locus $g_i$, we augmented the rate of the specified mutation type by the specified effect size (an effect size of 1.5 indicates a 50% increase in the mutation rate) on haplotypes carrying "A" alleles.
To more closely approximate the BXD RILs, the mean number of simulated mutations on each haplotype was allowed to vary by a factor of 20 (see Materials and Methods for more details).
We then applied the aggregate mutation spectrum distance method to these simulated data and asked if the adjusted cosine distance at locus $g_i$ was greater than expected by chance. 
Similarly, in each trial, we used R/qtl2 to perform a genome scan for QTL and asked if the log-odds score at $g_i$ was greater than expected by chance.
Given a specific combination of parameters, the y-axis denotes the fraction of 50 trials in which the simulated mutator allele could be detected at a significance threshold of p = 0.05 (for AMSD) or at an alpha of $\frac{0.05}{7}$ (for QTL mapping).
Shaded areas indicate the 95% bootstrap confidence interval surrounding that estimate.
](images/fig-power-comparison-variable-counts.png){#fig:ihd_vs_qtl_power_variable_counts tag="1-figure supplement 3" width=7.5in} 

![
**Comparing power between the aggregate mutation spectrum distance method and QTL mapping with variable mutator allele frequencies.** 
In each of 50 trials, we simulated genotypes at 1,000 biallelic loci on a toy population of 100 haplotypes as follows.
At every locus on every haplotype, we drew a single floating point value from a uniform distribution $[0, 1)$.
If that value was less than or equal to 0.5, we set the allele to be "A"; otherwise, we set the allele to be "B".
To model the effects of mutator allele frequencies on AMSD and QTL power, we allowed the expected frequency of "A" alleles at the mutator allele marker to be either 0.1, 0.25, or 0.5 in these simulations.
In each trial, we also simulated *de novo* germline mutations on the population of haplotypes, such that at a single locus $g_i$, we augmented the rate of the specified mutation type by the specified effect size (an effect size of 1.5 indicates a 50% increase in the mutation rate) on haplotypes carrying "A" alleles.
We then applied the aggregate mutation spectrum distance method to these simulated data and asked if the adjusted cosine distance at locus $g_i$ was greater than expected by chance. 
Similarly, in each trial, we used R/qtl2 to perform a genome scan for QTL and asked if the log-odds score at $g_i$ was greater than expected by chance.
Given a specific combination of parameters, the y-axis denotes the fraction of 50 trials in which the simulated mutator allele could be detected at a significance threshold of p = 0.05 (for AMSD) or at an alpha of $\frac{0.05}{7}$ (for QTL mapping).
Shaded areas indicate the 95% bootstrap confidence interval surrounding that estimate.
](images/fig-power-comparison-variable-afs.png){#fig:ihd_vs_qtl_power_variable_afs tag="1-figure supplement 4" width=7.5in} 

![
**Quantitative trait locus scans for mutation spectrum phenotypes.**
Using the BXDs with D genotypes at `rs27509845` (the marker with the highest cosine distance on chromosome 4; n = 66 BXDs, 42,171 total mutations), we used R/qtl2 to perform QTL scans for the fractions of each 1-mer mutation type.
QTL scans also included a kinship matrix (that contained the pairwise genetic similarity between each pair of BXDs, calculated using the leave-one-chromosome-out method) as a random effect term using the `kinship` keyword argument in the `scan1` function.
Plots show the log-odds (LOD) score at every genotyped marker in blue; the dotted black line represents the genome-wide LOD significance threshold (established using 1,000 permutations at an alpha of $\frac{0.05}{7}$ to account for the fact that 7 separate association tests were performed.)
](images/fig-qtl-scans.png){#fig:qtl-scans tag="2-figure supplement 1" width=7.5in} 

![
**Mutation spectra comparison in BXD strains.**
Fractions of *de novo* germline mutations in BXDs with either *D* or *B* genotypes at markers `rs27509845` and `rs46276051`, stratified by mutation type.
](images/fig-spectra-comparison-bxd-all.png){#fig:spectra-comparison-all tag="3-figure supplement 1" width=7.5in}

![
**Mutation spectra comparison in Sanger Mouse Genomes Project strains.**
Fractions of *de novo* germline mutations in Sanger MGP strains with either *D* or *B* haplotypes at the chromosome 4 and chromosome 6 mutator loci, stratified by mutation type.
](images/fig-spectra-comparison-mgp.png){#fig:spectra-comparison-mgp tag="3—figure supplement 2" width=7.5in} 

![
**Frequency of nonsynonymous DNA repair mutations in wild mice.** Alternate allele frequencies of each nonsynonymous DNA repair mutation overlapping the chromosome 6 mutator locus were calculated in populations of wild-derived mice from Harr et al. [@PMID:27622383]. Numbers of mice in each subpopulation are shown in parentheses. *Mmc* (*Mus musculus castaneus*), *Mmd* (*Mus musculus domesticus*), *Mmm* (*Mus musculus musculus*), and *Ms* (*Mus spretus*). The *Mbd4* p.Asp129Asn mutation was not observed in any wild populations.
](images/fig-wild-afs.png){#fig:wild-afs tag="3-figure supplement 3" width=7.5in}


### Supplementary Tables

| Gene name | Tissue name | # BXDs with expression data |  Top significant marker | -log10(p) at top significant marker (GEMMA) | Additive effect of D allele on expression (GEMMA) |
| - | - | - | - | - | - |
| *Ogg1* | Kidney | 53 | `rsm10000004188` | 12.89 | -0.180 |
| *Ogg1* | Liver | 50 | `rsm10000004188` | 13.57 | -0.155 | 
| *Ogg1* | Spleen | 79 | `rsm10000003418` | 4.73 | -0.056 |
| *Ogg1* | Gastrointestinal | 46 | `rs4173870` | 5.43 | -0.048 |
| *Fancd2* | Gastrointestinal | 46 | `rsm10000004199` | 8.60 | 0.133 | 
| *Ogg1* | Hippocampus | 67 | `rsm10000004188` | 16.50 | -0.165 |
| *Rad18* | Hippocampus | 67 | `rsm10000003463` | 6.32 | 0.068 |
| *Setmar* | Hippocampus | 67 | `rs13478947` | 11.03 | 0.141 |
| *Mbd4* | Spleen | 79 | `rsm10000004199` | 6.05 | 0.071 | 

Table: Significant cis-eQTLs for DNA repair genes in various tissues identified using GeneNetwork. {#tbl:eqtl-results tag="supplement 1"}

<!-- | SV start | SV end |  SV type | Gene name(s) | Overlaps exon? |
| - | - | - | - | - |
| 112,629,618 | 112,636,619 | DEL | *Rad18* | No | 

Table: Large structural variants overlapping protein-coding genes in the mutator locus on chromosome 6. All coordinates are with respect to GRCm39/mm39. {#tbl:sv-overlap tag="supplement 2"} -->



## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>

