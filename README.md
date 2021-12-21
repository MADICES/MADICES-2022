# Machine-Actionable Data Interoperability for Chemical Sciences (MADICES): Bridging experiments, simulations, and machine learning for spectral data

## Introduction

Recent advances in the computational sciences allow us to simulate many spectra (e.g., X-ray absorption, infrared/Raman, NMR) in silico. In principle, this could open up unprecedented possibilities for the interpretation of experimental data. 
Experimental data, however, comes in various, often undocumented or proprietary formats. 
In recent efforts, this experimental data is being recorded in electronic lab notebooks and archived with open data formats, aiding and automating crucial metadata capture. 
However, most of these lab notebooks have no mechanisms to exchange data between each other and even less so with our simulation tools, and typically, exporting data from such notebooks again requires lossy conversion to a chosen file format.

Standardization is an arduous process, and for a wide enough domain, it is infeasible. 
Nevertheless, without significant effort, there is a danger that we will not escape the local minima of [“★★★/★★★★★”](https://www.w3.org/DesignIssues/LinkedData.html) linked open data (as defined by Tim Berners-Lee).
In the case of the interoperability between experimental and computational data, there is the additional difficulty that computational systems are completely described, idealized systems with implicit assumptions, whereas for experimental systems parameters are ill-defined, unknown, or uncertain.
Moreover, we also often miss a link between spectra data and the (meta) data contextualising the sample and its history.
How and where can we be interoperable in this setting? How can we make sure that experimental data can readily be consumed by computational tools, and vice versa, from the bottom-up? 
How can we share, contextualise and disseminate analysis (e.g., post-processing, peak assignment) in a reproducible way (on platforms such as [MaterialsCloud](https://materialscloud.org) or the [Chemotion](https://www.chemotion.net)? 
What new paradigms could such interoperability enable?

At the CECAM MADICES 2022 workshop, we will bring together developers, scientists and data specialists to discuss the hurdles and opportunities of data interoperability in the context of the chemical and materials sciences.
We will strive for general technical recommendations,  with  X-ray absorption spectroscopy as the first prototype use case.

## Workshop aims

- Connecting resources and people working across the globe on these issues in our field, catalyzing collaborations on common open source software tools and infrastructure for reporting and describing schemas, APIs and other tools.
- A perspective paper authored by all workshop attendees outlining the current state of our field, with recommendations and suggestions for the future.
- More targeted follow-up meetings and discussions on particular aspects and technologies picked up during the workshop.
- The planning/organization of a hackathon-style event in mid-late 2022 targeted at interoperability between existing projects and the development of new software tools.

