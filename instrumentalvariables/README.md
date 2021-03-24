# Causal Inference with Instrumental Variables

Youngjoon Lee

Last updated: March 24, 2021

## Video and Slides

A video of the presentation can be found [here](https://www.dropbox.com/s/ve9fsriqh2tf5ei/causal-inference-instrumental-variables-ylee.mp4?dl=0).

The lides used for presentation are available [here](https://github.com/EandrewJones/gvpt-methods/blob/master/instrumentalvariables/RealFinal_Instrumental Variable Strategy_03222021.pptx).

## Description

In this workshop, Youngjoon discusses instrumental variables as an approach to causal inference when we have a continuous treatment variable in the presence of confounding. The talk covers the following:

1) Conditions under which IV approaches are applicable
2) The assumptions required for IV to be valid
3) How to test the strength of an instrument
4) Examples of IV approaches in the literature
5) A quick example of how to fit an two-stage least squares regression in R

## Statistical software for Two-Stage Least Squares

In the presentation, Youngjoon shows how to use the [ivreg](https://www.rdocumentation.org/packages/ivreg/versions/0.5-0) package in R to fit a two-stage least squares. An introductory vignette for how to install and use this package is available [here](https://cran.r-project.org/web/packages/ivreg/vignettes/ivreg.html).
