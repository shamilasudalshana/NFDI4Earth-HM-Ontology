# NFDI4Earth HM-Ontology

The **NFDI4Earth HM-Ontology** is a lightweight, domain-specific ontology developed to describe hydrological concepts, variables, and relationships in a semantically consistent and machine-readable way. It is intended to support the **FAIR (Findable, Accessible, Interoperable, Reusable)** principles for hydrological data by enabling semantic annotation, RDF transformation, and integration into knowledge graphs.

This ontology was developed as part of [NFDI4Earth project](https://www.nfdi4earth.de/) focused on transforming conventional hydrology datasets (e.g., CSVs) into semantically enriched RDF knowledge graphs, enabling better interoperability, query capabilities, and integration with other datasets using Semantic Web technologies.

## 🌊 Purpose and Scope

Hydrological datasets are often shared in formats like CSV, which lack semantic annotations and thus pose challenges for data discovery, reuse, and automated reasoning. The **NFDI4Earth HydroOntology** addresses these challenges by:

- Linking to existing vocabularies (e.g., SOSA, QUDT, EnvThes, Schema.org).
- Supporting the semantic transformation of datasets such as **LamaH-CE**.
- Enabling intelligent querying through **SPARQL** or integration with **question-answering systems**.

## 🚀 Key Features

- OWL-compliant ontology built on RDF standards.
- Alignments with:
  - [SOSA/SSN](https://www.w3.org/TR/vocab-ssn/): For sensor and observation modeling.
  - [QUDT](http://qudt.org/): For units and quantities.
  - [EnvThes](https://vocabs.lter-europe.net/EnvThes/en/): For environmental related definitions. 
  - [Schema.org](https://schema.org): For general-purpose descriptions.
- Built-in support for mapping CSV columns to ontology concepts via custom mapping configuration.

## 🧪 Example Use Case(s)

The ontology was used to annotate and convert the [LamaH-CE](https://github.com/realwaterresearch/LamaH-CE) dataset to RDF using a custom-built tool called **HydroTurtle**. The annotated RDF knowledge graph enabled:

- Integration of catchment attributes and time series measurements.
- Execution of SPARQL queries for hydrological analysis.
- Natural Language Question Answering over RDF data. 

The LamaH-CE Knowledge Graph can be found [here](Zenodo Link), and the scripts for the conversion from CSV to RDF are accessible at [repository](https://github.com/shamilasudalshana/Hydro-NLQA-LamaH-CE)

## 🔗 Re-using the Ontology

- Recommended prefix: hyobs
- Unique terms for the annotation of the hydrometeorological observations and time series: [`owl/ttl`](./NFDI4Earth_HydroOntology_FULL.ttl) | [online](https://hydro-knowledge-graph-f48785.pages.rwth-aachen.de/)
- Basic data model for the LamaH-CE and CAMELS-GB datasets [image]() | [owl]()

<img width="841" height="470" alt="image" src="https://github.com/user-attachments/assets/fde2f17d-ac4b-48c4-93e3-184f8df46e18" />

##  Contact
- Shamila
- [AurioL Degbelo](https://sites.google.com/site/aurioldegbelo/)

## Acknowledgments
This ontology is developed as part of the [NFDI4Earth](https://www.nfdi4earth.de/) initiative, aiming to advance research data management in Earth System Sciences. The project is coordinated by Technische Universität Dresden and funded by the German Research Foundation (DFG) under project number 460036893.




