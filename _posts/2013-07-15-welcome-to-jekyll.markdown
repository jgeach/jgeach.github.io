---
layout: post
title:  "Data reduction, etc."
date:   2013-07-15 18:55:46
categories: data reduction, s2cls, vics82
---

Been churning through more SCUBA-2 CLS data reduction (8TB raw in the can),
but pausing a week or so while our new SMP machine (256GB/32-core) and 32TB
data store is added to the cluster.

Tried training the SOM on H-ATLAS SPIRE photometry and GAMA redshifts with
the aim of producing a non-parametric photo-z estimator for sub-mm colours.
Looks promising, but requires more burn-in.

Submitted SPT/WISE QSO cross-correlation Letter

Spent Thursday/Friday working on VICS82 data for survey definition paper.
Positional accuracy looks good across the board, less then a quarter of an
arcsecond scatter in VICS82-2MASS positions over wide fields. Counts look
sane, but need to tweak photometric calibration a little by the look of it.
Next job is to produce beta versions of J+K matched catalogues, combined with
SDSS. Will allow basic gJK KX quasar selection for a start.


