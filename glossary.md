# Glossary 

## Datalake, Datawarehouse, Datamesh

[*Data lakes*](https://aws.amazon.com/big-data/datalakes-and-analytics/what-is-a-data-lake/) are a central place for collecting *raw* data from different sources (e.g. unparsed raw spectra).

[*Data warehouses*](https://en.wikipedia.org/wiki/Data_warehouse), in contrast, are a central place to central place for structured data integrated from different sources.

[*Data meshes*](https://martinfowler.com/articles/data-mesh-principles.html) are, in contrast to centralized datalakes or datawarehouses, a decentralized data architecture in which each domain will offer data as a product. This can be thought of as the data equivalent of microservices that found broad use for scalable software products. You might be interested in [Donny Winston's view on the implications for science](https://donnywinston.com/posts/scientific-data-is-fundamentally-distributed/).

## Data schema, model, format

*Data model* abstract description of the data structure (the elements and their relationships)

*Data schema*  describe the data models in a formal language. JSON-LD and XML are common formats for schemas.  ̰

*Data format* serialization of specific content in some dataschema.  

You might also want to give [Donny Winston's view](https://donnywinston.com/posts/data-formats-versus-data-models/) a look.

## Data dictionary 
A data dictionary describes the detailed definition (format, meaning, relationship, usage) and documentation about each data element in a data model.



## Dublin Core, DataCite

[The Dublin Core Metadata Element Set](https://en.wikipedia.org/wiki/Dublin_Core) is a set of 15 elements like "Contributor", "Date", "Format" that should be used for describing data resources. Related is the [DataCite Metadata Standard](https://schema.datacite.org/).


## ELN 
Electronic lab notebooks (ELNs) come in different forms. Sometimes, they are merely a revised note-taking app. Some, however, are more tailored for chemistry and provide special fields for reactions, chemicals, and spectra. You can find good overviews on [this compilation](https://zenodo.org/record/4723753) from the Harvard Medical school or [this one](https://www.data.cam.ac.uk/data-management-guide/electronic-research-notebooks) from the University of Cambridge.


## Five star open-data principles

[Deployment principles for open data proposed by Tim Berners-Lee](https://5stardata.info/en/)

★ make your stuff available on the Web (whatever format) under an open license

★★ make it available as structured data (e.g., Excel instead of image scan of a table)

★★★ make it available in a non-proprietary open format (e.g., CSV instead of Excel)

★★★★ use URIs to denote things, so that people can point at your stuff

★★★★★ link your data to other data to provide context

## LIMS 
Laboratory infrastructure management systems (LIMS) allow tracking and managing samples. Often they allow defining locations at which different material or equipment is stored and can then track the moves and uses of the materials


## Markup language 

A markup language allows annotating the text to decouple the structure from the content. One example is LaTeX, where the `\section` command can be used to define the concept of a section. In the context of data, markup languages such as [Extensible Markup Language (XML)](https://en.wikipedia.org/wiki/XML) are typically used. Indeed, it was built to annotate writing with formatting and metadata.
The archetypal example for chemistry is [CML](https://www.xml-cml.org/).


## Open notebook science 
[Open notebook science (ONS)](https://www.nature.com/articles/npre.2007.39.1) was popularized by Jean-Claude Bradley, and refers to making *all* primary research outputs openly available as they are recorded. The goal is to minimize the amount of "dark data", e.g., "failed" experiments that would never get published. [openlabnotebooks.org](https://openlabnotebooks.org/) collects some efforts.

## Open world assumption

The open-world assumption is the assumption that a statement might be true irrespective of whether it is known to be true. 
Semantic technologies (e.g., OWL) make the open-world assumption, i.e., the absence of statement does not mean that it is false. Many "classical" databases, in contrast, make the assumption that the absence of a statement means that is false. 

Quoting the example from [Wikipedia](https://en.wikipedia.org/wiki/Open-world_assumption) 

```
Statement: "Mary" "is a citizen of" "France"
Question: Is Paul a citizen of France?

"Closed world" (for example SQL) answer: No.
"Open world" answer: Unknown.
```


## Ontology 
Ontologies describe and clarifies the meaning and relation of terms in a formal language.

An ontology supports all the following use cases (table stolen from [Charles Hoyt](https://cthoyt.com/2020/05/12/building-an-ontology.html))


| Phrase                | Definition                                                      |
| --------------------- | --------------------------------------------------------------- |
| Controlled Vocabulary | An enumerated set of entities                                   |
| Dictionary            | An enumerated set of entities and their definitions             |
| Thesaurus             | An enumerated set of entities and their synonyms                |
| Hierarchy             | An enumerated set of entities with one parent for each          |
| Multi-Hierarchy       | An enumerated set of entities with one or more parents for each |

You can find more definitions of terms uses in the context of semantic techniques in [this  glossay by Charles Hoyt](https://cthoyt.com/2021/10/07/biopragmatics-glossary.html).


[The web ontology language OWL](https://en.wikipedia.org/wiki/Web_Ontology_Language) can be used to author ontologies. 

## RDF 

The [Resource Description Framework (RDF)](https://en.wikipedia.org/wiki/Resource_Description_Framework) breaks down information into triples of subject, verb, object that are linked in a graph like database which machines can use to explore information (and understand how information is connected). An example for a triple can be substance (subject) inhibits (verb) protein (object) and the same element can also be used in publication (subject) describes (verb) protein. Importantly the parts of the triples are usually (except for values) URIs. SPARQL is a language that can be used to query RDF. 

## Relational vs document databases

[Relational databases](https://en.wikipedia.org/wiki/Relational_database) (e.g., Oracle, PostgreSQL) store table in tables, comparable to spreadsheets. The word relational refers to the fact that the rows within a table are related according to some concept such as "employees" or "chemicals".

[Document databases](https://en.wikipedia.org/wiki/Document-oriented_database) (e.g., Mongo), in contrast, store all information for a given object in a single document, and every stored document can be different from every other. Documents can be thought of as objects in programming.

## Semantic Web

The [semantic web](https://www.w3.org/standards/semanticweb/) is an extension of the world wide web with metadata that makes data machine-interpretable such that agents can perform themselves actions using data. A key part is [linked data](https://www.w3.org/DesignIssues/LinkedData.html) that enables others to find, and use, related data. The principles of linked data are:

1. Use URIs as names for things

2. Use HTTP URIs so that people can look up those names.

3. When someone looks up a URI, provide useful information, using the standards (RDF*, SPARQL)

4. Include links to other URIs, so that they can discover more things.

it is [the fifth star of the five star open-data principles](https://5stardata.info/en/).


## URI, URL, IRI, GUPRI

A [URI](https://datatracker.ietf.org/doc/html/rfc3986) is sequence of a subset of ASCII characters that consists of a string that defines a scheme (e.g., `https`) followed by a `:` and a sequence specifying the authority (e.g.  `example.org`), the path (e.g., `/some/page`) and then optionally a query (e.g., `?get=name`) and optionally fragment (`#results`).
A URL is a special form of URI that is a locator, i.e. it can be resolved to some resource. An IRI is a generalization of URI to unicode glyps.

A more detailed explanation on the difference between URLs, URIs, and IRIs can be found [here](https://fusion.cs.uni-jena.de/fusion/2016/11/18/iri-uri-url-urn-and-their-differences/).

GUPRIs (globally unique persistent resolvable identifires) are simply URIs with the additional constraints that they must be globally unique and persistent, typically provided via a centralized registration service like the Digital Object Identifier Foundation ([DOI](https://doi.org) or [Handle](https://www.dona.net/handle-system). 
These identifiers are a technical solution fulfilling F1 of the [FAIR Principles](https://www.go-fair.org/fair-principles/).

## UUID

A universally unique identifier (UUID) is a 128-bit number that is, with high probability, globally unique.