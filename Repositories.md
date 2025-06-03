> depreciated, the list is now maintained and continued via: https://codeberg.org/OSEGermany/OpenSearchEcosystem

# Repositories

## Introduction

This document maintains a list of repositories that are used within the
project.  We make a distinction between three types of repositories:

- **[project repositories]** are where most of the work takes place
and that can be considered part of our project.
All the official hand-overs for our NGI-Search project are amongst these,
and thus they need a license check, credits, and they might indicate
being partly funded by NGI-Search in their READMEs.

- The second type consitutes **[contributing repositories]**:
These are repositories that this project contributes to,
but are not directly targeted by this project.
These repos have more of a supporting role
and the [project repositories] may make use of them.

- Finally, **[reference repositories]** are not necessarily part of the project,
but are relevant to the project either for inspiration
or for alternative implementation directions.

All projects in all three categories are Open Source licenced.

## Project Repositories

### https://github.com/iop-alliance/OpenKnowHow/

This repository is forked from OPEN-NEXT project that initiated this version of
Open Know How / Library of Open Source Hardware (OKH-LOSH).  It contains a
specification of the Open Know-How standard in [Linked Open Data][LOD] form.
Note that it now officially deprecates the first version
which was not using LOD.

### https://codeberg.org/elevont/open-dataset/

A newly created ontology for annotating data-sets with relevant data.
It is tweaked towards scraped data, at the moment.

### https://github.com/iop-alliance/OKH-krawler/

This provides a scraper that collects OSH projects
from various hosting technologies/platforms,
like Thingiverse, OSHWA and Appropedia.

### https://github.com/OPEN-NEXT/LOSH-OKH-tool

Validate and convert OKH metadata.

### https://codeberg.org/elevont/owl2shacl/

Convert (simple) ontologies to SHACL shapes in order to validate to what extent
linked data adheres to the ontology.

### https://codeberg.org/elevont/ontprox/

An HTTP service that acts as a proxy for ontologies,
converting them on-the-fly into the requested RDF serialization format or/and HTML.

### https://codeberg.org/elevont/eyeball

An RDF linter.
Revived after a period of 10+ years of inactivity and code-rot.

### https://github.com/OSEGermany/okh-scraper/

A stand-alone service that scrapes(/crawls) Open Source Hardware (OSH) projects from different platforms and other hosting technologies.

## Contributing Repositories

### https://github.com/oeg-upm/OOPS

A linter for RDF/OWL ontologies that makes a distinction between various pitfalls in ontology design.

### https://github.com/perma-id/w3id.org

Contains information about permanent URL that redirect to our ontolgies.

### https://github.com/osegermany/OKH-RDF-DB

Helps you to test the OKH data with the Apache Jena triple-store.

### https://github.com/elevont/rdf.sh

A command-line utility for Semantic Web operations.

### https://gitlab.com/OSEGermany/oh-tsdc

Contains Technology-specific Documentation Criteria (TsDC) according to DIN SPEC 3105-1.

### https://gitlab.com/OSEGermany/oh-tsdc-tools

Tools to convert different formats of Technology-specific Documentation Criteria (TsDC) into each other.

### https://github.com/elevont/jena.git

A Java framework for writing Semantic Web applications.  Note that this is our
own distribution of it that enables RDF 1.0.  It is used in the Eyeball OWL/RDF
linter.

### https://github.com/elevont/lov-dump-updater

Takes the [LOV] [data dump](https://lov.linkeddata.es/dataset/lov/sparql),
reformats it, and stores the changes since the last time into a git repo.
This allows for easy consumption of (the changes of) "all" the ontologies out there.

### https://codeberg.org/elevont/lov-dump

The outcome/output of te above repo.

### https://codeberg.org/elevont/rdfoothills

A library for conversion between different RDF serialization formats, using external tools, and for RDF MIME-types.

## Reference Repositories

### https://github.com/iop-alliance/okh-search

A prototype federated search engine for OKH projects.  It is based on the OKH
v1 standard.

[Project repositories]: #project-repositories
[contributing repositories]: #contributing-repositories
[reference repositories]: #reference-repositories
[LOD]: https://en.wikipedia.org/wiki/Linked_data#Linked_open_data
[LOV]: https://lov.linkeddata.es/
