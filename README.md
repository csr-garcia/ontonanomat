# ontonanomat

[![DOI](https://zenodo.org/badge/1115429569.svg)](https://doi.org/10.5281/zenodo.18201275)

Overview

This repository contains the ontology GSN-Remediation, developed to support ontology-based semantic integration of green-synthesized nanomaterials, their physicochemical profiles, remediation mechanisms, sustainability attributes, and provenance.
It accompanies the manuscript:

Ontology-Based Semantic Integration of Green-Synthesized Nanomaterials for Sustainable Environmental Remediation

The goal is to enable FAIR, machine-actionable, and interoperable knowledge representation for adsorption and photocatalytic remediation workflows.

This ontology is licensed under Creative Commons Attribution 4.0 International (CC BY 4.0).

Ontology

File: green_nanomaterials_ontology.ttl
Format: OWL 2 DL (Turtle)
Base IRI: https://w3id.org/gsn-remediation#

Key Modules:

Nanomaterials
Contaminants
Remediation Mechanisms (Adsorption, Photocatalysis)
Experimental Conditions
Performance Indicators
Sustainability Profiles
Provenance (PROV-O alignment)

The ontology reuses concepts from:

ChEBI
ENVO
eNanoMapper
CHEMINF
PROV-O
SHACL (recommended for validation)

Datasets (FAIR Structured Examples)

To demonstrate the ontology, this repository includes illustrative datasets derived from the two case-study instances presented in the manuscript's Appendix C:

Adsorption of methylene blue using macroporous polyacrylamide/γ-Fe₂O₃ beads
Photocatalytic degradation of Rhodamine B using a green-synthesized visible-light photocatalyst
These are not copyrighted experimental datasets but ontology-aligned demonstration datasets.

Available Formats:
Format	File	Description
CSV	dataset_case_studies.csv	Flat table suitable for ML and tabular workflows
JSON	dataset_case_studies.json	Object-oriented representation
RDF/Turtle	dataset_case_studies.ttl	Knowledge graph aligned with the ontology
Excel	dataset_case_studies.xlsx	Multi-sheet dataset (nanomaterials, synthesis, mechanisms, conditions, performance, provenance)

Each dataset includes:

Material identity
Physicochemical attributes
Synthesis route
Sustainability metadata
Target contaminant
Mechanistic pathway
Experimental parameters
Performance indicators
Provenance and publication metadata

SPARQL Query Library

File: green_nanomaterials_queries.rq

Includes:
High-performance adsorbents (qmax > threshold)
Photocatalysts with band-gap constraints
Sustainability benchmarking (energy demand vs rate constant)
Contaminant → nanomaterial mapping
Provenance tracing
Metadata completeness audits

Compatible with:
Apache Jena Fuseki
GraphDB
Oxigraph
RDFox
Protégé SPARQL tab

FAIR & Reusability

The ontology and datasets are designed following FAIR principles:
Findable: persistent IRI structure + structured metadata
Accessible: open repository, standard formats
Interoperable: OWL, RDF, SPARQL, reuse of domain ontologies
Reusable: CC BY 4.0 license, full documentation

License
This project is released under the Creative Commons Attribution 4.0 International (CC BY 4.0)
Allowing reuse, adaptation, and redistribution with attribution.

Citation

If you use this ontology or datasets, please cite:
García-García, C.A. Ontology-Based Semantic Integration of Green-Synthesized Nanomaterials for Environmentally Sustainable Remediation Processes. (2025).
