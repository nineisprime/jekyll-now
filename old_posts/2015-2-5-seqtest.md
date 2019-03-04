---
layout: post
title:
---

#### 2/5/15. False discovery rate control for sequential hypothesis testing
**Authors:** Ang Li and Rina Foygel Barber  
**Presenter:** Ang Li  
**Abstract:** We consider the multiple testing problem on a ranked list of hypotheses,
where rank is based on prior information, e.g. from an earlier study
under different experimental conditions. The aim is to select a data-dependent
cutoff k and declare the first k hypotheses to be statistically significant while
bounding the false discovery rate (FDR). Generalizing several existing methods,
we develop a family of “accumulation tests” to choose a cutoff k that
adapts to the amount of signal at the top of the ranked list. Each test is characterized
by an “accumulation function” that uses the first k p-values to estimate
the FDR among the top k ranked hypotheses. We prove control of a modified
FDR for finite samples, and the exact FDR asymptotically. We also prove
that using a simple step function yields nearly optimal power against a broad
class of alternate hypotheses. These results are validated by simulations. We
apply the tests to data on differential gene expression over a dosage gradient
(using high dosage data as prior information, we gain power at low dosage),
and to the problem of high-dimensional model selection (via recent results that
compute a sequence of p-values for the LASSO).
