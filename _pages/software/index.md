---
layout: page
title: Software
permalink: /software/
toggle: on
rank: 3
---

***

<br>
<div style="margin-bottom: 50px;">
    <img class="float-right" width="50%" src="{{ 'circmle.jpg' | prepend: site.images_dir | prepend: site.baseurl }}" />
</div>
<div style="text-align:center;">
<button style="-moz-box-shadow:inset 0px 1px 3px 0px #91b8b3; -webkit-box-shadow:inset 0px 1px 3px 0px #91b8b3; box-shadow:inset 0px 1px 3px 0px #91b8b3; background:-webkit-gradient(linear, left top, left bottom, color-stop(0.05, #768d87), color-stop(1, #6c7c7c)); background:-moz-linear-gradient(top, #768d87 5%, #6c7c7c 100%); background:-webkit-linear-gradient(top, #768d87 5%, #6c7c7c 100%); background:-o-linear-gradient(top, #768d87 5%, #6c7c7c 100%); background:-ms-linear-gradient(top, #768d87 5%, #6c7c7c 100%); background:linear-gradient(to bottom, #768d87 5%, #6c7c7c 100%); filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#768d87', endColorstr='#6c7c7c',GradientType=0); background-color:#768d87; -moz-border-radius:5px; -webkit-border-radius:5px; border-radius:5px; border:1px solid #566963; display:inline-block; cursor:pointer; color:#ffffff; font-family:Arial; font-size:15px; font-weight:bold; padding:11px 23px; text-decoration:none; text-shadow:0px -1px 0px #2b665e;" onclick="window.location.href='https://cran.r-project.org/web/packages/CircMLE';">CircMLE</button>
</div>
<br>

The R package 'CircMLE' is a series of wrapper functions to implement the 10 maximum likelihood models of animal orientation described by [Schnute and Groot (1992)](https://doi.org/10.1016/S0003-3472(05)80068-5). The functions also include the ability to use different optimizer methods, calculate various model selection metrics (i.e., AIC, AICc, BIC), perform likelihood ratio tests and plot results.

***

<div style="margin-bottom: 50px;">
    <img class="float-right" width="50%" src="{{ 'optm.jpg' | prepend: site.images_dir | prepend: site.baseurl }}" />
</div>
<div style="text-align:center;">
<button style="-moz-box-shadow:inset 0px 1px 3px 0px #91b8b3; -webkit-box-shadow:inset 0px 1px 3px 0px #91b8b3; box-shadow:inset 0px 1px 3px 0px #91b8b3; background:-webkit-gradient(linear, left top, left bottom, color-stop(0.05, #768d87), color-stop(1, #6c7c7c)); background:-moz-linear-gradient(top, #768d87 5%, #6c7c7c 100%); background:-webkit-linear-gradient(top, #768d87 5%, #6c7c7c 100%); background:-o-linear-gradient(top, #768d87 5%, #6c7c7c 100%); background:-ms-linear-gradient(top, #768d87 5%, #6c7c7c 100%); background:linear-gradient(to bottom, #768d87 5%, #6c7c7c 100%); filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#768d87', endColorstr='#6c7c7c',GradientType=0); background-color:#768d87; -moz-border-radius:5px; -webkit-border-radius:5px; border-radius:5px; border:1px solid #566963; display:inline-block; cursor:pointer; color:#ffffff; font-family:Arial; font-size:15px; font-weight:bold; padding:11px 23px; text-decoration:none; text-shadow:0px -1px 0px #2b665e;" onclick="window.location.href='https://cran.r-project.org/web/packages/OptM';">OptM</button>
</div>
<br>

The R package 'OptM' is a tool I am developing to determine the optimal number of migration edges on a population tree using the [_TREEMIX_](https://bitbucket.org/nygcresearch/treemix/wiki/Home) software. Currently, _TREEMIX_ recommends to stop adding migration edges when 99.8% of the observed variation is explained by the model.  Using OptM, one can use either an ad hoc statistic based on the second-order rate of change in likelihood (what I call "Δm") or a series of linear modeling approaches to determine the optimal cutoff using a more quantitative approach.
OptM is currently available on CRAN in a beta-testing phase.  Please check it out and let me know how it can improve!
<br>
***
<br>

**Publications using this software**

1. [Double-Hit Gene Expression Signature Defines a Distinct Subgroup of Germinal Center B-Cell-Like Diffuse Large B-Cell Lymphoma](http://ascopubs.org/doi/full/10.1200/JCO.18.01583)
2. [Genome-wide discovery of somatic regulatory variants in diffuse large B-cell lymphoma](https://www.nature.com/articles/s41467-018-06354-3)
3. [Targeted error-suppressed quantification of circulating tumor DNA using semi-degenerate barcoded adapters and biotinylated baits](https://www.nature.com/articles/s41598-017-10269-2)
4. [Enhancing knowledge discovery from cancer genomics data with Galaxy](https://academic.oup.com/gigascience/article-lookup/doi/10.1093/gigascience/gix015)

**Data Sets**

* [73 paired de novo DLBCL genomes](https://ega-archive.org/studies/EGAS00001002936)
* [30 paired relapsed/refractory DLBCL exomes](https://ega-archive.org/datasets/EGAD00001003395)

**Contributors**

* [Chris Rushton](https://github.com/ckrushton)
* [Bruno Grande](https://github.com/scientificbruno)
