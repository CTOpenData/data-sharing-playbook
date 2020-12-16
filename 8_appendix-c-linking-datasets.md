---
layout: page
title: 'Appendix C: Linking Datasets'
permalink: /linking-datasets/
nav: true
weight: 8
---

Data linking or data matching is the process of combining two or more datasets. It allows program administrations to provide more integrated and client-friendly government services. 

Data linking also provides policy analysts and researchers a wider lens to draw insights and improve services. There are two ways to link datasets — deterministic and probabilistic.

### Deterministic data linking
Deterministic data linking combines individual records only if the fields that are being compared match exactly. For example, two agencies could use social security numbers to combine their datasets. This type of data linking is most suitable when both datasets have a consistent, unique identifier. 

### Probabilistic data linking
Probabilistic data linking combines individual records using a special algorithm that compares multiple fields to determine if two records are the same entity. For example, [P20 WIN's data linking process](https://youtu.be/c6D_8qisXyA) uses identifiers such as name, birthday, and other fields present in both datasets to combine datasets. Probabilistic data linking is best suited for datasets that don’t have a unique identifier. It’s also best suited when two datasets have a unique identifier that’s inconsistently present or untrusted.

### Blocking
When comparing two datasets, checking every single possible pair is computationally taxing. For example, two datasets each containing 100 records would require 10,000 pairwise comparisons. Pairwise comparisons quickly become unmanageable when linking two administrative datasets.

Blocking solves this computational challenge by only comparing pairs that are likely to match according to particular fields. For example, by using age for blocking, only records with the same birth year are compared to each other. A common strategy is to run mulitple block passes because some fields are missing or erroneous. The [Australian Government's Open Data Toolkit](https://toolkit.data.gov.au/Data_Linking_Information_Series_Sheet_4:_Probabilistic_linking.html) 
provides a table of fields to consider when blocking.

### Deduplication 

### Recommended reading
* [Two Methods Of Linking: Probabilistic And Deterministic Record-linkage Methods](https://aspe.hhs.gov/report/studies-welfare-populations-data-collection-and-research-issues/two-methods-linking-probabilistic-and-deterministic-record-linkage-methods)
* [Linkage Feasibility—To Link or Not To Link](https://www.ncbi.nlm.nih.gov/books/NBK253318/)
* [Data Matching Software Tools](https://github.com/J535D165/data-matching-software)
* [Improving deduplication of identities](http://www.datasciencepublicpolicy.org//wp-content/uploads/2018/11/dedupewhitepaper.pdf)
* [Linking Administrative Data: Strategies and Methods](https://github.com/californiapolicylab/data-linking/blob/master/Data%20Linking%20-%20white%20paper%20-%2012%2018%2018%20-%20FINAL.pdf)
* [Challenges in administrative data linkage for research](https://journals.sagepub.com/doi/10.1177/2053951717745678)
### Active Research and Development 
* 
