---
layout: page
title: 'Linking Datasets'
permalink: /linking-datasests/
nav: true
weight: 6
---

Data linking or data matching is the process of combining two or more datasets. It allows program administrations to provide more integrated and client-friendly government services.

Data linking also provides policy analysts and researchers a wider lens to draw insights and improve services. There are two ways to link datasets — deterministic and probabilistic.

### Deterministic data linking

Deterministic data linking combines individual records only if the fields that are being compared match exactly. For example, two agencies could use social security numbers to combine their datasets. This type of data linking is most suitable when both datasets have a consistent, unique identifier.

### Probabilistic data linking

Probabilistic data linking combines individual records using a special algorithm that compares multiple fields to determine if two records are the same entity. For example, [P20 WIN’s data linking process](https://youtu.be/c6D_8qisXyA) uses identifiers such as name, birthday, and other fields present in both datasets to combine datasets. Probabilistic data linking is best suited for datasets that don’t have a unique identifier. It’s also best suited when two datasets have a unique identifier that’s inconsistently present or untrusted.

### Blocking

When comparing two datasets, checking every single possible pair is computationally taxing. For example, two datasets each containing 100 records would require 10,000 pairwise comparisons. This computational reality quickly becomes unmanageable when linking larger administrative datasets.

Blocking solves this computational challenge by only comparing pairs that are likely to match according to particular fields. For example, by using age for blocking, only records with the same birth year are compared to each other. A common strategy is to run multiple block passes because some fields are missing or erroneous. The [Australian Government’s Open Data Toolkit](https://toolkit.data.gov.au/Data_Linking_Information_Series_Sheet_4:_Probabilistic_linking.html) provides a table of fields to consider when blocking.

### Measuring Accuracy

There are two types of matching errors that arise when linking records. The first is a false negative, which implies two records that fail to meet the set matching criteria actually are a match. The second is a false positive, which is when two records meet the set matching criteria when they are in fact not a match. There is a tradeoff between false negatives and false positives when determining the stringency of any matching criteria. A stricter matching criteria will decrease the number of false positives but increase the number of false negatives, while a more lenient matching criteria will increase the number of false positives but decrease the number of false negatives. The context of the data match provides guidance on which type of error to minimize.

It is very difficult to capture the true number of false negatives and false positives in a data merge. Researchers have implemented creative methods for assessing the accuracy of record linkage algorithms. For example, [researchers at the University of Michigan](https://sites.lsa.umich.edu/mgms/wp-content/uploads/sites/283/2020/12/entity_resolution_20201203.pdf) tested a supervised learning, record linkage algorithm by training it on a large, novel dataset that includes biometric identifiers (fingerprints) to construct unbiased measures of error. [Other researchers](http://www-personal.umich.edu/~baileymj/Bailey_Cole_Henderson_Massey.pdf) have examined the performance of widely-used record linking algorithms with hand-linked datasets and synthetic datasets. Synthetic datasets have known errors introduced to fields of interest.

## Transferring and linking data in P20 WIN

P20 WIN’s data linking process uses identifiers such as name, birthday, and other fields present in both datasets to combine datasets. [This video](https://youtu.be/c6D_8qisXyA) provides more details about P20 WIN’s data linking process. Additional detail can be found in the P20 WIN Data Governance Manual [key processes](https://p20-win.github.io/Data-Governance-Manual/key-processes/).
