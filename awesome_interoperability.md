# MADICES awesome resource [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[Parts copied from the neo-chem compilation](https://github.com/neo-chem/awesome-chemical-data).

## Data

- [TED talk about Tim Berners-Lee about linked data](https://www.youtube.com/watch?v=OM6XIICm_qo)
- [Course about RDF, Knowledge Graphs from TU Dresden](https://www.youtube.com/channel/UCCvDWNsR8YlQrB1tSj9Xqsw)


### Schemas, Ontologies & Vocabularies

- [Pachl, C.; Frank, N.; Breitbart, J.; Bräse, S. Overview of Chemical Ontologies. arXiv:2002.03842 [cs] 2020.](https://arxiv.org/pdf/2002.03842.pdf)
- [The Trouble with Ontologies, or, How to Build an Ontology](https://cthoyt.com/2020/05/12/building-an-ontology.html)
- [Cox SJD, Gonzalez-Beltran AN, Magagna B, Marinescu MC (2021) Ten simple rules for making a vocabulary FAIR. PLOS Computational Biology 17(6)](https://doi.org/10.1371/journal.pcbi.1009041)


## Tools

- [Linked Data Modeling Language](https://linkml.io/): Define schema as `yaml` files and generate JSON-Schema, RDF, OWL, GraphQL, Python dataclasses
- [Versioning of data schema: Translate your data with lenses](https://www.inkandswitch.com/cambria/): Blog posts discusses the challenges and potential solutions for dealing with evolving data schema. 
- [Basic tabular data annotation from frictionless data](https://specs.frictionlessdata.io/table-schema/#name)
- [rdf-tabular](https://github.com/ruby-rdf/rdf-tabular). Also see [this talk](https://www.youtube.com/watch?v=qIXcnSCOyZs)
- [Research Object Crates](https://www.researchobject.org/), a schema.org-based container specification for the serialization of research data.

See also the [Semantic Python Overview](https://github.com/pysemtec/semantic-python-overview) list.

## Initiatives 

- [NFDI4Chem](https://www.nfdi4chem.de/): Initiative to build an open and FAIR infrastructure for research data management in chemistry with an associated [Knowledge Base](https://knowledgebase.nfdi4chem.de) on how to be FAIR in chemistry.

- [Blue Obelisk](https://blueobelisk.github.io/): Internet group promoting reusable chemistry via open source software development. [📄](https://pubs.acs.org/doi/10.1021/ci050400b) [📄](https://jcheminf.biomedcentral.com/articles/10.1186/1758-2946-3-37)

- [GO FAIR Chemistry Implementation Network](https://www.go-fair.org/implementation-networks/overview/chemistryin/): Goals are "to enhance the open, FAIR and effective communication of chemical knowledge within the chemical sciences and between chemistry and other disciplines" and "to enable chemists and chemistry to contribute to the achievement of the UN Global Sustainable Development goals" (direct quotes from the website). [📄](https://www.mitpressjournals.org/doi/full/10.1162/dint_a_00035).

- [Chemistry Research Data IG](https://www.rd-alliance.org/groups/chemistry-research-data-interest-group.html): Interest Group of the Research Data Alliance (RDA) that aims to foster exchange on chemical data.

- [RDA/CODATA Materials Data, Infrastructure & Interoperability IG](https://www.rd-alliance.org/groups/rdacodata-materials-data-infrastructure-interoperability-ig.html): Interest Group of the Research Data Alliance (RDA) that aims to foster exchange on material data.

- [Materials Research Data Alliance (MaRDA)](https://www.marda-alliance.org/): a community network focused on developing the open, accessible, and interoperable materials data that fuels the Materials Genome Initiative (MGI).


## Related compilations

- [Awesome Materials Informatics](https://github.com/tilde-lab/awesome-materials-informatics): In contrast to this compilation, [Awesome Materials Informatics](https://github.com/tilde-lab/awesome-materials-informatics) focuses more on computational materials science.

- [FAIRsharing.org](https://fairsharing.org) domain collections for [Chemistry](https://fairsharing.org/collection/Chemistry) and [Semantic Assets for Materials Science](https://fairsharing.org/collection/SemanticAssetsMatSci).

- [FAIRsFAIR ACME-FAIR Guide: Defining Data Interoperability Frameworks](https://zenodo.org/record/5775552) - one section in a 7-part set of recommendations for ensuring FAIR practice across domains.

## Recommended by participants 

### Data formats and models 
- [JCAMP](http://www.jcamp-dx.org/) - IUPAC recommended data exchange format with standardized vocabularies for some fields
- [FAIRSpec](https://github.com/IUPAC/IUPAC-FAIRSpec) - standard for sharing spectroscopic data
- [DataCite metadata schema](https://datacite.org/) - A set of mandatory metadata that must be registered with the DataCite Metadata Store when minting a DOI persistent identifier for a dataset
- [AniML](https://www.animl.org/) - Analytical Information Markup Language (AnIML) is an open ASTM XML standard for storing and sharing any analytical chemistry data.
- [Chemical Markup Language CML](https://www.xml-cml.org/) - is an approach to managing molecular information using XML
- [NeXus format](https://www.nexusformat.org/) -  common data format for neutron, x-ray, and muon science
- [JSON-LD](https://search.brave.com/search?q=json-ld&source=desktop) - publishing linked data as JSON files on the Web
- [GEMD data model](https://citrineinformatics.github.io/gemd-docs/) -  Graphical Expression of Materials Data that  links together materials, the processes that produced them, and the measurements that characterize them
- [chemrof](https://chemkg.github.io/chemrof/) - data model for managing information about chemical entities, ranging from atoms through molecules to complex mixtures.

### Ontologies

- [MOP](https://www.ebi.ac.uk/ols/ontologies/mop) - Molecular process ontology
- [RXNO](https://www.ebi.ac.uk/ols/ontologies/rxno) - name reaction ontology
- [OWL](https://www.w3.org/OWL/) - Web ontology language
- [ChEBI](https://www.ebi.ac.uk/chebi/) - Chemical Entities of Biological Interest is a chemical database and ontology of molecular entities
  
### Tools
- [PyStow](https://github.com/cthoyt/pystow) - for reproducible downloading of data in various computational Workflows in Python
- [Chemotion](https://www.chemotion.net/chemotionsaurus/index.html) - Electronic lab notebook, focussed on organic chemistry, developed at KIT
- [rdflib](https://github.com/RDFLib/rdflib) - Python libary to deal with RDF
- [LinkML](https://linkml.io/) -- see above
- [Ontology Development Kit](https://github.com/INCATools/ontology-development-kit) - a toolbox of various ontology related tools such as [ROBOT](https://github.com/ontodev/robot), [owltools](https://github.com/owlcollab/owltools), [dosdp-tools](https://github.com/INCATools/dosdp-tools) and many more, bundled as a docker image, a set of executable workflows for managing your ontologies continuous integration, quality control, releases and dynamic imports
- [iochem-bd](https://www.iochem-bd.org/) - The Computational Chemistry Results Repository, using CML as internal data format 
- [Wikidata](https://www.wikidata.org/wiki/Wikidata:Main_Page) - a collaboratively edited multilingual knowledge graph 
- [Pipeline Pilot](https://www.3ds.com/products-services/biovia/products/data-science/pipeline-pilot/) - Proprietary software to build ETL, data science/analytics workflows in a graphical user interface
- [OPTIMADE](https://www.optimade.org/) - consortium that aims to make materials databases interoperable by developing a specification for a common REST API
