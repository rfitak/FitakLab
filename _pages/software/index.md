---
layout: page
title: Software
permalink: /software/
toggle: on
rank: 4
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

The R package 'OptM' is a tool I am developing to determine the optimal number of migration edges on a population tree using the [_TREEMIX_](https://bitbucket.org/nygcresearch/treemix/wiki/Home) software. Currently, _TREEMIX_ recommends to stop adding migration edges when 99.8% of the observed variation is explained by the model.  Using OptM, one can use either an _ad hoc_ statistic based on the second-order rate of change in likelihood (what I call "_Δm_") or a series of linear modeling approaches to determine the optimal cutoff using a more quantitative approach.
OptM is currently available on CRAN in a beta-testing phase.  Please check it out and let me know how it can improve!

<br>

***

<div style="text-align:center;margin-top: 50px;">
<button style="-moz-box-shadow:inset 0px 1px 3px 0px #91b8b3; -webkit-box-shadow:inset 0px 1px 3px 0px #91b8b3; box-shadow:inset 0px 1px 3px 0px #91b8b3; background:-webkit-gradient(linear, left top, left bottom, color-stop(0.05, #768d87), color-stop(1, #6c7c7c)); background:-moz-linear-gradient(top, #768d87 5%, #6c7c7c 100%); background:-webkit-linear-gradient(top, #768d87 5%, #6c7c7c 100%); background:-o-linear-gradient(top, #768d87 5%, #6c7c7c 100%); background:-ms-linear-gradient(top, #768d87 5%, #6c7c7c 100%); background:linear-gradient(to bottom, #768d87 5%, #6c7c7c 100%); filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#768d87', endColorstr='#6c7c7c',GradientType=0); background-color:#768d87; -moz-border-radius:5px; -webkit-border-radius:5px; border-radius:5px; border:1px solid #566963; display:inline-block; cursor:pointer; color:#ffffff; font-family:Arial; font-size:15px; font-weight:bold; padding:11px 23px; text-decoration:none; text-shadow:0px -1px 0px #2b665e;" onclick="window.location.href='https://rfitak.shinyapps.io/circbio/';">Circular Stats Online Calculator</button>
</div>
<br>
This web app takes you to a simple online calculator to use for graphing circular data (a dataset of angles), calculating the circular mean, performing the Rayleigh test, and comparing two groups.  The calculator is designed to be simple, intuitive, and for particular use in conjunction with the Pill Bug Lab (see link below).
<html>
<head><title>Circular Calculator</title></head>
<body>
<iframe id="Circular Calculator" src="https://rfitak.shinyapps.io/circbio/" style="border: none; width: 100%; height: 850px" frameborder="0"></iframe>
</body>
</html>

<div style="text-align:center;">
<button style="-moz-box-shadow:inset 0px 1px 3px 0px #91b8b3; -webkit-box-shadow:inset 0px 1px 3px 0px #91b8b3; box-shadow:inset 0px 1px 3px 0px #91b8b3; background:-webkit-gradient(linear, left top, left bottom, color-stop(0.05, #768d87), color-stop(1, #6c7c7c)); background:-moz-linear-gradient(top, #768d87 5%, #6c7c7c 100%); background:-webkit-linear-gradient(top, #768d87 5%, #6c7c7c 100%); background:-o-linear-gradient(top, #768d87 5%, #6c7c7c 100%); background:-ms-linear-gradient(top, #768d87 5%, #6c7c7c 100%); background:linear-gradient(to bottom, #768d87 5%, #6c7c7c 100%); filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#768d87', endColorstr='#6c7c7c',GradientType=0); background-color:#768d87; -moz-border-radius:5px; -webkit-border-radius:5px; border-radius:5px; border:1px solid #566963; display:inline-block; cursor:pointer; color:#ffffff; font-family:Arial; font-size:15px; font-weight:bold; padding:11px 23px; text-decoration:none; text-shadow:0px -1px 0px #2b665e;" onclick="window.location.href='https://rfitak.github.io/Circular_Biology/';">Pill Bug Lab</button>
</div>

<br>

***

<br>

**Publications using this software**

1. __CircMLE__
  - [Fitak RR and Johnsen S. (2017) Bringing the analysis of animal orientation data full circle: model-based approaches with maximum likelihood. _J Exp Biol_ 220: 3878-3882.](https://doi.org/10.1242/jeb.167056)
2. __CircMLE__
  - [Kingston ACN, Chappell DR, Speiser DI. (2018) Evidence for spatial vision in _Chiton tuberculatus_, a chiton with eyespots. _J Exp Biol_ 221: jeb183632.](https://doi.org/10.1242/jeb.183632)
3. __CircMLE__
  - [Sumner-Rooney L, Kirwan JD, Lowe E, Ulrich-Luter E. (2020) Extraocular vision in a brittle star Is mediated by chromatophore movement in response to ambient light. _Curr Biol_ 30: 1-9.](https://doi.org/10.1016/j.cub.2019.11.042)
4. __CircMLE__
  - [Fitak RR, Wheeler BR, Johnsen S. (2020) Effect of a magnetic pulse on orientation behavior in rainbow trout (<i>Oncorhynchus mykiss</i>). _Behav Proc_ 172:104058.](https://doi.org/10.1016/j.beproc.2020.104058)
5. __CircMLE__
  - [Diego‐Rasilla FJ, Luengo RM. (2020) Magnetic compass orientation in common midwife toad tadpoles, <i>Alytes obstetricans</i> (Anura, Alytidae). _J Ethol_ in press.](https://doi.org/10.1007/s10164-020-00653-3)
7. __CircMLE__
  - [Landler L, Ruxton G, Malkemper P. (2020). Grouped circular data in biology: advice for effectively implementing statistical procedures. _Behav Ecol Sociobiol_ 74: 100.](https://doi.org/10.1007/s00265-020-02881-6)
8. __CircMLE__
  - [Caspar K, Moldenhauer K, Moritz R, Němec P, Malkemper P, Begall, S. (2020). Eyes are essential for magnetoreception in a mammal. _J R Soc Interface_ 17:20200513.](https://doi.org/10.1098/rsif.2020.0513)
9. __CircMLE__
  - [Ojeda V, Schaaf A, Altamirano TA, Bonaparte B, Bragagnolo L, Chazarreta L, Cockle K, Dias R, Di Sallo F, Ibarra JT, Ippi S, Jauregui A, Jiménez JE, Lammertink M, López F, Montellano MGN, de la Peña M, Rivera L, Vivanco C, Santillán M, Soto GE, Vergara PM, Wynia A, Politi N. (2021). Latitude does not influence cavity entrance orientation of South American avian excavators. _Auk_ 138:1-14](https://doi.org/10.1093/ornithology/ukaa064)
**Data Sets, Databases, Other**

* [Puma Genetic Database](https://www.arcgis.com/home/item.html?id=4d9e04e504bb453691fbff736df49b3b)

**Contributors**

* [TBD](https://github.com/rfitak)
