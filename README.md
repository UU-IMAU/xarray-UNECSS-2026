## UNECSS 2026 Xarray Workshop

**Intro to Big Array Data Analysis in Python for geospatial science and microscopy**


**Date**: 25 September 2026

**Time**: 14:00 – 16:30

**Speaker**: [Nick Hodgskin](README.md#speaker)

**Required resources**: Laptop (and charger if needed)



## Summary

Data coming from satellites, climate models, and high-resolution microscopes have unique aspects in common. The datasets are very large (typically ranging from gigabytes to terabytes) meaning they often cannot be loaded entirely into memory, and the datasets are fundamentally multidimensional which prevents effective analysis using tabular data processing techniques. Processing data requires software and infrastructure that meets these challenges and empower researchers to deliver insight.

This workshop first provides an overview of this problem space, before providing a foundation to the Python package that has arrived at the centre of it all — Xarray. In this tutorial we will also look at how SURF Research Cloud infrastructure can be used to effectively deploy Xarray workflows, and work with big array data.


## Agenda

The slides for the workshop are [available here](./UNECSS-2026-slides.pdf).

| Time | Item |
|---|---|
| 14:00 - 14:30 | Why Xarray? |
| 14:30 – 15:00 | Notebooks:<br/>[Xarray data structures](notebooks/01-datastructures-intermediate.ipynb)<br/>[Indexing basics](notebooks/02.1_indexing_Basic.ipynb)<br/>[Computation with Xarray](notebooks/03.1_computation_with_xarray.ipynb)<br/>[Basic plotting](notebooks/04.1_basic_plotting.ipynb)<br/>[Advanced: Computational patterns in Xarray](notebooks/09-high-level-computation-patterns.ipynb) |
| 15:00 – 15:30 | Coffee break |
| 15:30 – 16:00 | Continuing with notebooks | 
| 16:00 – 16:30 | The bigger picture |

---

## Speaker

Nick Hodgskin ([@VeckoTheGecko on GitHub](https://github.com/VeckoTheGecko)) is a Research Software Engineer and Xarray maintainer working at Utrecht University, primarily on Parcels (a Lagrangian simulation framework used in physical oceanography). Here he has been leading a rewrite of Parcels to use Xarray as a core data structure, along the way improving Parcels interoperability with the Pangeo ecosystem of packages. A self proclaimed "Pangeo evangelist", Nick loves communicating the power of the Scientific Python stack with Xarray for geospatial analysis, as well as its flexibility in different domains — which he does by organising fortnightly talks at his institute, as well as by giving tutorials.


## Acknowledgements

The notebooks from this workshop are adapted from [Xarray Tutorial](https://tutorial.xarray.dev).

## About UNECSS

The [Utrecht University](https://www.uu.nl/en) [NIOZ](https://www.nioz.nl/en) Early Career Scientist Symposium (UNECSS) is a cross-institute collaboration geared towards early careers scientists in the fields of oceanography and climate reasearch.

The focus for this year is exploring how AI, machine learning and big data are transforming ocean and climate research.
