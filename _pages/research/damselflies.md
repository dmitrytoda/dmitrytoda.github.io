---
layout: single
classes: wide	
permalink: /research/damselflies/    
sidebar:
  nav: pages
---

# Phenomics of sexual conflict in damselflies

The common bluetail damselfly *Ischnura elegans* is exhibits temporally stable female-limited colour polymorphism (Fig 1A): one androchrome (male mimicking) morph and two gynochrome morphs (​infuscans and ​infuscans obsoleta​; Fig. 1C). Strong balancing selection is thought to maintain the trimorphic state of this system across a range of environmental and climatic conditions (Le Rouzic et al. 2015; Fig. 1B). However, while the frequency of androchrome morphs was around 30% in southern Europe (Figure 1B), in most populations in northern Europe the androchome morph is by far the most common with between 60-80% (Gosden et al. 2011, Svensson et al. 2020). This contradicts the theory by which female androchrome morphs should experience negative frequency dependent 3 selection, because the efficacy of male mimicry might break down when the mimicking morphs become too common.

<p align="center"><img src="/assets/images/damselfly_polymorphism.png" width="600" /></p>
<p style="font:caption">Figure 1 - A) Mating in the common bluetail damselfly (*Ischnura elegans*), where the male (upper) and the female can remain in copula for several hours. B) Variation in female colour morph frequencies of *I. elegans* across Europe: the frequency of androchrome (male-mimicking) females increases at higher latitudes. C) Colour development is genetic and controlled by a single autosomal locus with three alleles forming a dominance hierarchy (androchrome > infuscans > infuscans obsoleta). All images reproduced from (Svensson et al. 2020) with permission from Erik Svensson.</p>

One explanation for the high frequency of the male mimicking female morph is that the benefits of female polymorphism may be frequency dependent, but the costs are frequency independent. For example, at high latitudes, the morphs do not only differ in their abdominal colouration, but also in their cold tolerance (Svensson et al. 2020). These findings highlight the need for more comprehensive phenotypic investigations of the ​*I. elegans* ​polymorphism that go beyond the quantification of colour, specifically, extensive morphological and behavioral analyses.

<p align="center"><img src="/assets/images/damselfly_phenopype.jpg" width="600" /></p>
<p style="font:caption">Figure 2 - Scanned image of the common bluetail damselfly (*Ischnura elegans*), segmented with the Python package <a href="https://mluerig.github.io/phenopype/">phenopype</a> </p>

I am currently conducting a comprehensive analysis of morphology in an existing large image dataset of different Swedish *​I. elegans* populations to test whether the three female morphs express morph-specific sets of covarying traits, which are under correlational selection. I am using a suite of simple segmentation algorithms to extract continuous morphological information from existing data (scanned images) that have been collected by the Svensson lab. In a second step, I will also implement deep learning methods to screen for axes of phenotypic variation not captured by the human eye. 


### Literature 

Gosden, T. P., R. Stoks, and E. I. Svensson. 2011. Range limits, large-scale biogeographic variation, and localized evolutionary dynamics in a polymorphic damselfly. Biological journal of the Linnean Society. Linnean Society of London 102:775–785

Le Rouzic, A., T. F. Hansen, T. P. Gosden, and E. I. Svensson. 2015. Evolutionary time-series analysis reveals the signature of frequency-dependent selection on a female mating polymorphism. The American naturalist 185:E182–96

Svensson, E. I., B. Willink, M. C. Duryea, and L. T. Lancaster. 2020. Temperature drives pre-reproductive selection and shapes the biogeography of a female polymorphism. Ecology letters 23:149–159.