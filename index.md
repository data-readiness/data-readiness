---
layout: prfaq
title: About
weight: 1
faq:
- Q: What are the bands of data readiness?
  A: "For the moment we have described three bands of data readiness. Within
  each band there will be sub bands. One role of this site is to
  achieve consensus on what those sub-bands (and bands) should represent
  so that data readiness levels can be deployed across a wide range of
  applications."
- Q: "Where does data start?"
  A: "Typically, all data starts at sub-band C4, 'hearsay data', meaning
  that people have heard that the data exists, so they say it does. The
  ultimate aim, is to bring a data set to A1, at this subband the data
  is ready for deployment or productionization. 

  To explore each band go to the associated pages on the page above. You can make
  suggestions for changes to band or sub-band descriptions through github pull requests."
- Q: Are these bands set in stone?
  A: "No, the intention of this site is to share experience and best
  practice among practitioners of the data sciences. You can
  contribute changes via pull requests from github (each of the pages has an
  'edit' button). The merits of those changes can be debated via
  github issues."
- Q: "What if we combine data sets? Is the data readiness of the combined
data the minimum of the two data sets?"
  A:  "No, because there may be ethical, legal or topological reasons
  why we cannot bring the data together. The Data Readiness Level (DRL) of two combined data
  sets would be at *most* the minimum of the two DRLs, but could well
  be lower. Even two data sets at A1, when combined, could require
  record deduplication, which immediately sends the data back to Band B. Of
  course such combined data would likely be quicker to pull through
  the readiness levels than raw data which hadn't been looked at
  before. I.e. record deduplication may be the only task required to
  leave Band B."
- Q: "Does it make sense to think about data without the context? Can
  we process data before we know what we want to do with it?"
  A: "Historically in statistics it doesn't seem to have made sense,
  and also in the sciences it is frowned upon to collect data on
  'fishing expeditions'. However, in practice, scientific questions
  are refined as more data is collected. And there is now good
  precedent for large scale screens (e.g. transcriptome analysis
  during development or disease) where the context is very broad."
- Q: Are you related to the NSI Nanotechnology discussion?
  A: "No, we conceived of data readiness levels separately, but after
  that discussion, and looking at that document, we feel the scope is too
  narrow for wide usage. The aim in this effort is to ensure that we
  gain a much broader consensus across data sciences."
- Q: Why is this the right time for this new idea?
  A: "We are trying to reflect the new reality that much data (indeed the
  majority) is now collected by happenstance, and this data needs very different treatment from data
  that is actively acquired. Those who are acquiring the data need to be cognisant of
  the challenges, as well as those who are making decisions about the
  data and how it will be used in analysis. "
---

In the data sciences, data quality is a prerequisite for success. So the fact that we don't have a common language for describing the status of our data is a severe constraint. Imagine if, when you are talking about data, you can qualify its
readiness. Imagine that you can use a few terms to develop an
immediate sense of what investment is required to extract the value
from the data.

Data Readiness Levels start
with the concept of *hearsay data*, data which someone heard is
available, so they say it is. This is where many projects start. They
then provide a scale of readiness which is designed to assist decision
makers and practitioners in assessing the project status, which
resources need to be deployed, what time lines and costs are likely to
be. Data readiness levels are a set of terms used to characterize the
readiness of data for deployment.

Data Readiness levels allow managers and decision makers to understand project status, and where investment is needed without intimate familiarity with the data itself.

You can read more in [this blog post](http://inverseprobability.com/2017/01/12/data-readiness-levels) and [this arxiv paper](https://arxiv.org/abs/1705.02245).

