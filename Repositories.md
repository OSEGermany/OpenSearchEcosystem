# Repositories

## Introduction

This document maintains a list of repositories that are used within the
project.  We make a distinction between three types of repositories:
**Project repositories** in which the work (mostly) takes place and that can be
considered part of our project.  Project repositories contain the contributions
to this project and need a license check, credits, and they should be indicated
as modules of the project.

The second type consitutes **contributing repositories**: These are
repositories that this project contributes to, but are not directly targeted by
this project.  These repos have a more supporting role and the project
repositories may make use of this category of repositories.

Finally, **reference repositories** are of the third type.  These repositories
are not necessarily part of the project but are relevant to the project either
for inspiration or for alternative implementation directions.

## Project Repositories

### https://github.com/iop-alliance/OpenKnowHow/

This repository is forked from OPEN-NEXT project that initiated this version of
Open Know How / Library of Open Source Hardware (OKH-LOSH) work.  It contains a
specification of the Open Know How standard in Linked Open data form.  Note
that it overrides the first version that was not using linked open data.

### https://codeberg.org/elevont/open-dataset/

A newly created ontology for annotating data-sets with relevant data.
It is tweaked towards scraped data, at the moment.

### https://github.com/iop-alliance/OKH-krawler/

This repository is forked from the OPEN-NEXT project and provides a crawler
that searches for OKH hardware projects on GitHub, Thingiverse, and OSHWA.

### https://github.com/OPEN-NEXT/LOSH-OKH-tool

Validate and convert OKH metadata.  This repository is about to be moved to the
iop-alliance GitHub organization.

### https://codeberg.org/elevont/owl2shacl/

Convert (simple) ontologies to SHACL shapes in order to validate to what extent
linked data satisfies the ontology.

### https://codeberg.org/elevont/ontprox/

An HTTP service that provides the user with up-to-date ontologies in various formats.

### https://codeberg.org/elevont/eyeball

An OWL/RDF linter.

### https://github.com/OSEGermany/okh-scraper/

A stand-alone service that scrapes(/crawls) Open Source Hardware (OSH) projects from different platforms and other hosting technologies.

## Contributing Repositories

### https://github.com/oeg-upm/OOPS

A linter for ontologies that makes a distinction between various pitfalls in ontology design.

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

## Reference Repositories

### https://github.com/iop-alliance/okh-search

A prototype federated search engine for OKH projects.  It is based on the OKH
v1 standard.
