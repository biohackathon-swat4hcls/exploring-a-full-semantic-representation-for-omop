---
title: 'SWAT4HCLS23 Hack report: Explore a full semantic rfpresentation of OMOP'
title_short: 'SWAT4HCLSHACK #10: semantic OMOP'
tags:
  - OMOP
  - Ontologies
  - Semantic
  - Graph
authors:
  - name: Andrea Splendiani
    orcid: 0000-0000-0000-0000
    affiliation: 1
  - name: Alberto Labarga
    orcid: 0000-0000-0000-0000
    affiliation: 2
  - name: Michel Dumontier
    orcid: 0000-0000-0000-0000
    affiliation: 2
  - name: Christine Kakalou
    orcid: 0000-0000-0000-0000
    affiliation: 2
  - name: Remzi Celebi
    orcid: 0000-0000-0000-0000
    affiliation: 2
  - name: Harald Witte
    orcid: 0000-0000-0000-0000
    affiliation: 2
  - name: Pantelis Natsiavas
    orcid: 0000-0000-0000-0000
    affiliation: 2
  - name: Alban Gaignard
    orcid: 0000-0000-0000-0000
    affiliation: 2
  - name: Pablo Alarcon Moreno
    orcid: 0000-0000-0000-0000
    affiliation: 2
  - name: Achilleas Chytas
    orcid: 0000-0000-0000-0000
    affiliation: 2
  - name: Shatvik ?
    orcid: 0000-0000-0000-0000
    affiliation: 2
  - name: Ronald Cornet
    orcid: 0000-0000-0000-0000
    affiliation: 2
  - name: Deepak Unni
    orcid: 0000-0000-0000-0000
    affiliation: 2
    
affiliations:
  - name: First Affiliation
    index: 1
  - name: Second Affiliation
    index: 2
date: 8 November 2023
cito-bibliography: paper.bib
event: BH23EU
biohackathon_name: "SWAT4HCLS BioHackathon 2024"
biohackathon_url:   "https://biohackathon-europe.org/"
biohackathon_location: "Leiden, Netherlands, 2024"
group: Project 26
# URL to project git repo --- should contain the actual paper.md:
git_url: https://github.com/biohackrxiv/publication-template
# This is the short authors description that is used at the
# bottom of the generated paper (typically the first two authors):
authors_short: First Author \emph{et al.}
---


# Introduction

As part of the SWAT4HCLS 2024 BioHackathon, we set to explore what full semantic representation of OMOP could provide. OMOP is a widely used standard to represent Real World Data (RWD) in a standardized way. A significant efforts in its specification andsupporting processes relates to the standardization of ontologies. Howwever, these are intended to normalise categorical values. The structure of the model itself is represented as a relational model with limited attention to semantics. In this hackathon we set to explore how a full semantic representation could be achieved, and what it could entail.
# Formatting

This document use Markdown and you can look at [this tutorial](https://www.markdowntutorial.com/).

## Subsection level 2

Please keep sections to a maximum of only two levels.

## Tables and figures

Tables can be added in the following way, though alternatives are possible:

Table: Note that table caption is automatically numbered and should be
given before the table itself.

| Header 1 | Header 2 |
| -------- | -------- |
| item 1 | item 2 |
| item 3 | item 4 |

A figure is added with:

![Caption for BioHackrXiv logo figure](./biohackrxiv.png)

# Other main section on your manuscript level 1

Lists can be added with:

1. Item 1
2. Item 2

# Citation Typing Ontology annotation

You can use [CiTO](http://purl.org/spar/cito/2018-02-12) annotations, as explained in [this BioHackathon Europe 2021 write up](https://raw.githubusercontent.com/biohackrxiv/bhxiv-metadata/main/doc/elixir_biohackathon2021/paper.md) and [this CiTO Pilot](https://www.biomedcentral.com/collections/cito).
Using this template, you can cite an article and indicate _why_ you cite that article, for instance DisGeNET-RDF [@citesAsAuthority:Queralt2016].

The syntax in Markdown is as follows: a single intention annotation looks like
`[@usesMethodIn:Krewinkel2017]`; two or more intentions are separated
with colons, like `[@extends:discusses:Nielsen2017Scholia]`. When you cite two
different articles, you use this syntax: `[@citesAsDataSource:Ammar2022ETL; @citesAsDataSource:Arend2022BioHackEU22]`.

Possible CiTO typing annotation include:

* citesAsDataSource: when you point the reader to a source of data which may explain a claim
* usesDataFrom: when you reuse somehow (and elaborate on) the data in the cited entity
* usesMethodIn
* citesAsAuthority
* citesAsEvidence
* citesAsPotentialSolution
* citesAsRecommendedReading
* citesAsRelated
* citesAsSourceDocument
* citesForInformation
* confirms
* documents
* providesDataFor
* obtainsSupportFrom
* discusses
* extends
* agreesWith
* disagreesWith
* updates
* citation: generic citation


# Results


# Discussion

...

## Acknowledgements

...

## References
