---
layout: ontology_detail
id: eupath
title: eupathdb ontology
jobs:
  - id: https://travis-ci.org/eupath-ontology/eupathdb-ontology
    type: travis-ci
build:
  checkout: git clone https://github.com/eupath-ontology/eupathdb-ontology.git
  system: git
  path: "."
contact:
  email: cjmungall@lbl.gov
  label: Chris Mungall
description: eupathdb ontology is an ontology...
domain: stuff
homepage: https://github.com/eupath-ontology/eupathdb-ontology
products:
  - id: eupath.owl
  - id: eupath.obo
dependencies:
 - id: obi
 - id: ro
tracker: https://github.com/eupath-ontology/eupathdb-ontology/issues
license:
  url: http://creativecommons.org/licenses/by/3.0/
  label: CC-BY
---

Enter a detailed description of your ontology here
