# HydroShare Schema.org

This repository provides documentation for HydroShare's implementation of Schema.org metadata. The HydroShare production system is at https://www.hydroshare.org.

## Introduction

Schema.org (http://schema.org) is a collaboration among major Internet search engines to create, maintain, and promote schemas for structured data on the Internet. Recently, several organizations have been working on how to describe datasets published on the Internet using the Schema.org vocabulary to better enable discovery of published datasets as products of research. This repository describes how HydroShare is implementing Schema.org metadata elements to support discovery of HydroShare resources.

HydroShare has a dual purpose in implementing Schema.org metadata for its resources. First, we want HydroShare resources to be discoverable using Google Dataset Search (https://toolbox.google.com/datasetsearch) and other tools that may use Schema.org metadata. Second, we want to make sure that HydroShare resources can be discovered and access through DataONE (https://www.dataone.org/), which is a community driven project that provides access to data across multiple member repositories and supports enhance search and discovery of Earth and environmental data.

To accomplish these objectives, HydroShare's implementation is based on Version 1.2.0 of the Science On Schema.Org (SOSO) Guidance Documents available at https://github.com/ESIPFed/science-on-schema.org.

>Matthew B. Jones, Stephen Richard, Dave Vieglais, Adam Shepherd, Ruth Duerr, Doug Fils, Lewis McGibbney. (2021). Science-on-Schema.org v1.2.0 (Version 1.2.0). Zenodo. https://doi.org/10.5281/zenodo.4477164

## This repository contains:

* [Description of HydroShare's Implementation](https://github.com/hydroshare/hs_schema.org/blob/main/guides/HydroShare_Technical_Implementation.md)
* [Examples of Dataset Encoding](https://github.com/hydroshare/hs_schema.org/tree/main/examples)

## Sponsors and Credits

[![NSF-1664061](https://img.shields.io/badge/NSF-1664061-blue.svg)](https://nsf.gov/awardsearch/showAward?AWD_ID=1664061)

This material is based upon work supported by the National Science Foundation (NSF) under award 1664061. Any opinions, findings, conclusions, or recommendations expressed in this material are those of the authors and do not necessarily reflect the views of the NSF.