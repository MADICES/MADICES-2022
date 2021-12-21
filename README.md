# Machine-Actionable Data Interoperability for Chemical Sciences (MADICES): Bridging experiments, simulations, and machine learning for spectral data

**UNDER CONSTRUCTION**

*These notes are taken from the draft [Google doc](https://docs.google.com/document/d/1AP24-2ytyDjZvLK5kG5pRnQFtIA_7M8nYeqHEskWvQI/edit) with minor tidying.*

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

### Organizing commitee (alphabetical)

- Shyam Dwaraknath
- Matthew Evans
- Sebastiaan Huber
- Kevin Maik Jablonka
- Carlo Pignedoli

### Structure

- Three remote days (planned for February 7-9 2022)
- Attempt to straddle multiple timezones with 2-3 hour sessions I-IV at (say) 08:00 UTC, 12:00 UTC, 16:00 UTC and 20:00 UTC
- All talks streamed live on YouTube and Zoom so that records are available immediately
- Followed up in subsequent months by:
    - A minimal number of meetings targeted at particular important breakout topics, with the aim to distill issues/opportunities into a section for a perspective paper
    - Something like a Hackathon (say, Summer 2022, following release of a manifesto/paper) to investigate gaps in the ecosystem/solve technical issues in this area

1. Introductions from organizers
    - Important that these are pre-recorded and available ideally the week before the conference, but also “screened” live
    - Discusses motivations and goals for the overall conference and beyond
    - Survey backgrounds and interests of attendees, including possible breakout room attendance (online survey sent week(s) in advance) 

2. Keynotes (I and III on day 1) 
    - Need to invite one keynote speaker with 30 minute(?) slots. Suggestions:
        - Josh Schrier
        - Conor Coley
    - Invite 5-6 people for panel discussion after the keynotes. Suggestions:
        - Zach Trautt (or someone else from MGI/NIST)
        - Alasdair Gray (or someone else from bioschemas)
        - Someone from EU materials ontology world OntoTrans/OntoCommons 
        - Nicholas Sauter (crystallography but bio-focused)
        - Henk Birkholz (or someone else from an NFDI with focus on materials data management)
        - Someone from Acceleration Consortium?
    - Shorter talks (10-20 mins) from various initiatives (can also be used as a pool for panel):
        - Academic research:
            - BIG-MAP
            - NFDI4Chem
            - NCCR
            - MARDA
            - Allotrope Foundation
            - MaterialD1g1tal
        - Industrial research:
            - Toyota Research Institute
            - BASF
            - Bosch
            - Citrine Informatics
            - Novartis
            - Merck
        - Instrument manufacturers/facility managers (for specific XAS):
            - Sigray
            - Bruker
            - Rigaku
            - A large synchotron? 
        - RDM schema/tool developers:
            - OpenBIS
            - Cheminfo
            - MDCS
            - Chemotion
            - Labstep
            - eLabFTW
            - CHADA/MODA
            - KADI4MAT
            - LabTrove
            - IUPAC
            - CIF
        - Open science orgs (if we have space)
            - Open Knowledge Foundation (CKAN, Frictionless)
            - Blue Obelisk
            - International Data Spaces
            - Gaia-X
            - datacc
            - OSF

3. Breakout discussions (all other sessions, up to 3 concurrent rooms). 
    - Pre-prepared (and shared) intro to topic from room organizer (10 minutes)
    - Discussion (90 minutes)
    - Break (20 minutes)
    - Debrief with all rooms (10 minutes per room)
    - In the final day, focus on tying discussions together into a paper section
    - Potential topics can be found in `./breakouts`.
