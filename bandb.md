---
title: Band B
layout: band
---

Grade B is about the validity of the data. Checking the faithfulness and representation. It can include components of exploratory data analysis.

## What does it include?

* visualisations for exploratory analysis e.g. PCA and Hierarchical Clustering
* noise characterisation.
* missing values.
* entity disambiguation, record linkage, duplicate detection
* anomaly detection
* sanity checks on the use of physical units (if used)
* data representation (vectorizing, word embeddings etc)? Or does this come in Grade A. 
* Availability in a commonly usable format (e.g. json, RDF etc).

## Examples

* Was a column or columns accidentally perturbed (e.g. through a sort operation that missed one or more columns)?
* Was a [gene name accidentally converted to a date](http://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-5-80)?


For data that is Grade B, we are ready to define a candidate question, the context.
