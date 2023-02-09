---
title: Manuscript Title
keywords:
- markdown
- publishing
- manubot
lang: en-US
date-meta: '2023-02-09'
author-meta:
- John Doe
- Jane Roe
header-includes: |
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta property="og:type" content="article" />
  <meta name="dc.title" content="Manuscript Title" />
  <meta name="citation_title" content="Manuscript Title" />
  <meta property="og:title" content="Manuscript Title" />
  <meta property="twitter:title" content="Manuscript Title" />
  <meta name="dc.date" content="2023-02-09" />
  <meta name="citation_publication_date" content="2023-02-09" />
  <meta property="article:published_time" content="2023-02-09" />
  <meta name="dc.modified" content="2023-02-09T17:01:59+00:00" />
  <meta property="article:modified_time" content="2023-02-09T17:01:59+00:00" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="John Doe" />
  <meta name="citation_author_institution" content="Department of Something, University of Whatever" />
  <meta name="citation_author_orcid" content="XXXX-XXXX-XXXX-XXXX" />
  <meta name="twitter:creator" content="@johndoe" />
  <meta name="citation_author" content="Jane Roe" />
  <meta name="citation_author_institution" content="Department of Something, University of Whatever" />
  <meta name="citation_author_institution" content="Department of Whatever, University of Something" />
  <meta name="citation_author_orcid" content="XXXX-XXXX-XXXX-XXXX" />
  <link rel="canonical" href="https://quinlan-lab.github.io/mutator-epistasis-manuscript/" />
  <meta property="og:url" content="https://quinlan-lab.github.io/mutator-epistasis-manuscript/" />
  <meta property="twitter:url" content="https://quinlan-lab.github.io/mutator-epistasis-manuscript/" />
  <meta name="citation_fulltext_html_url" content="https://quinlan-lab.github.io/mutator-epistasis-manuscript/" />
  <meta name="citation_pdf_url" content="https://quinlan-lab.github.io/mutator-epistasis-manuscript/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://quinlan-lab.github.io/mutator-epistasis-manuscript/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://quinlan-lab.github.io/mutator-epistasis-manuscript/v/d288ee8483638987711ee086970a140e9803626c/" />
  <meta name="manubot_html_url_versioned" content="https://quinlan-lab.github.io/mutator-epistasis-manuscript/v/d288ee8483638987711ee086970a140e9803626c/" />
  <meta name="manubot_pdf_url_versioned" content="https://quinlan-lab.github.io/mutator-epistasis-manuscript/v/d288ee8483638987711ee086970a140e9803626c/manuscript.pdf" />
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
([permalink](https://quinlan-lab.github.io/mutator-epistasis-manuscript/v/d288ee8483638987711ee086970a140e9803626c/))
was automatically generated
from [quinlan-lab/mutator-epistasis-manuscript@d288ee8](https://github.com/quinlan-lab/mutator-epistasis-manuscript/tree/d288ee8483638987711ee086970a140e9803626c)
on February 9, 2023.
</em></small>



## Authors



+ **John Doe**
  <br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [johndoe](https://github.com/johndoe)
    · ![Twitter icon](images/twitter.svg){.inline_icon width=16 height=16}
    [johndoe](https://twitter.com/johndoe)
    · ![Mastodon icon](images/mastodon.svg){.inline_icon}
    [\@johndoe@mastodon.social](https://mastodon.social/@johndoe)
    <br>
  <small>
     Department of Something, University of Whatever
     · Funded by Grant XXXXXXXX
  </small>

+ **Jane Roe**
  ^[✉](#correspondence)^<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [janeroe](https://github.com/janeroe)
    <br>
  <small>
     Department of Something, University of Whatever; Department of Whatever, University of Something
  </small>


::: {#correspondence}
✉ — Correspondence possible via [GitHub Issues](https://github.com/quinlan-lab/mutator-epistasis-manuscript/issues)
or email to
Jane Roe \<jane.roe@whatever.edu\>.


:::


## Abstract {.page_break_before}

Lorem ipsum.


## Introduction

Maintaining genome integrity in the mammalian germline is enormously complex. Hundreds of protein-coding genes contribute to pathways involved in DNA replication, and hundreds more are mobilized in response to damage by exogenous and endogenous mutagens [@PMID:28485537]. Despite this abundance of potential targets, *mutator alleles* that augment the germline mutation rate have largely eluded detection in mammals. 

Germline mutator alleles are difficult to detect for a number of reasons, including the fidelity of germline genome replication and the effects of selection on mutators. On average, humans are born with about 70 to 100 *de novo* germline mutations per diploid genome [@PMID:28959963; @PMID:31549960]; in mice, the number is closer to 20 or 30 [@PMID:31492841]. Moreover, in a population of sufficiently large $N_e$, we would also expect even low-effect mutator alleles to be efficiently selected against. The selection coefficient on a mutator allele is approximately $2s \Delta U$ [@PMID:27739533], where *s* is the mean selective coefficient on a new deleterious mutation and $\Delta U$ is the excess number of new deleterious mutations caused by the mutator allele; the product of $s$ and $\Delta U$ is multiplied by 2 to account for the expected number of generations for which mutator will be linked to the excess mutations it causes. Given the low germline *de novo* mutation rate in mamalian genomes and the strength of selection on a potential mutator allele, we would likely require a very large number of offspring, as well as an environment that attenuates the effects of selection, in order to detect the effects of a germline mutator allele.

In general, we would expect haplotypes that carry mutator alleles at a particular locus to carry an excess of total germline mutations, compared to those that harbor wild-type alleles. However, protein-coding genes involved in DNA replication and repair often recognize particular sequence motifs or excise lesions at specific nucleotides [@PMID:28485537]. Thus, we might also expect that the spectrum of de novo mutations -- i.e, the frequency of each individual mutation type (C>T, A>G, etc.) -- will differ between genomes that harbor either a mutator or wild-type allele at a given locus.

Previously, we discovered a germline mutator allele in mice by analyzing whole-genome sequencing data from 152 recombinant inbred lines (RILs). These RILs, known as the **B**X**D**s [@PMID:33472028], were derived from C57**B**L/6J and **D**BA/2J, two laboratory strains that exhibit significant differences in their germline mutation spectra [@PMID:30753674]. Following either F2 or advanced intercrosses of the parental strains, the BXDs were inbred by brother-sister mating for up to 180 generations, attenuating the effects of natural selection on both standing and new variation. Over the course of inbreeding, each BXD therefore accumulated hundreds or thousands of germline *de novo* mutations on a linear mosaic of the parental haplotypes that was almostly completely homozygous. Previously, we identified up to 2,000 germline de novo mutations in each line and used quantitative trait locus (QTL) mapping to identify a locus on chromosome 4 that was strongly associated with the C>A germline mutation rate [@PMID:35545679]. The QTL overlapped *Mutyh*, which encodes a protein that normally prevents C>A mutations by repairing oxidative DNA damage [@PMID:17581577], and we hypothesized that missense mutations in *Mutyh* were responsible for a 50% increase in the C>A mutation rate between BXDs with either parental haplotype at the QTL.

In this study, we developed a new method to detect alleles that affect the mutation spectrum in two-parent RILs, and applied it to previously generated mutation data from the BXDs. We assessed its power to detect candidate mutator alleles, and discovered compelling evidence of epistasis between two germline mutator alleles that augment the C>A germline mutation rate.


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>

