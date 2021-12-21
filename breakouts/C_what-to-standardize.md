# What should we standardize? 

- Standardize on the data, format, model, or on the tool or the transport level? 
- Tool development is more complicated/time-consuming than the development of parsers. 
    - How can we remain format agnostic? 
    - Can we leave people their own formats but “tag”/”annotate” concepts? 
    - Does this help? 
    - Is it practical? 
    - How could it be implemented? 
    - What specific technologies can be used to enable interoperability?
- Linked data formats and the semantic web: 
    - JSON-LD to provide context and ontologies to make agreement explicit.
    - Is “Linked” Open Data too much of a barrier? 
    - Can tools/frameworks like LinkML help bridge the schema > ontology gap?
- Data Format vs data model:
    - How do we make sure the model travels with the serialization?
- Are centralised software libraries required to support such an effort, or would they simply be useful? 
    - Who would write these? 
    - What “higher-order” libraries could be useful? (e.g. a GitHub action that takes a Python library, with some config, and creates an API server, with machine-readable metadata/schemas published on an “app registry”)
- Learning from other fields: 
    - If you have something scalable for chemistry, does it scale to other domains? 
    - If it doesn’t, why not? 
    - If there are standards for other domains (e.g. sample-based sciences), why can’t we use them? 

