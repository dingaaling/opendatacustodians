# 2023 ODC Project Roadmap

Target Outcome: In 2023, the ODC project aims to scale up the existing MVP to a Python library for transferring file-level Github repo metadata to a database. With the database/API, ODC will support 2 outcomes associated with its partner communities:
Open Repo Maintainers: ability to pull custom subsets of data to feed into applications like a static site or dashboard
Open AI Orgs: tools to help removal of contributor data from ML datasets if they revoke their consent for its use

## Milestone 1 (Technical Focus)
Identify target database providers to build ODC data transfer to (e.g. Firebase, data.world, HuggingFace Datasets) prioritising open source options
Create functionality to tag subsets of data, to enable queries for 
utility (e.g. domain, type of doc, expertise level) and 
privacy (e.g. only data from opt-in data subjects)
Scale up file cataloguing system for mapping file-level repo data to a database from notebook MVP to Python library

Target Output: Python library for using a CLI (low code) or web dashboard (no code) to catalogue file-level Github repo metadata in a database, providing options for user metadata tagging features, to enable data customisation or contributor privacy-preserving functionality. These two functionalities of utility & privacy represent the core needs of the 2 target community partners.

## Milestone 2 (Open Repo Maintainer Community Focus - The Turing Way)
Build features for content personalisation features to create custom data subsets
Test integration capabilities of repo data with other applications for display

Target Output: Data pipeline for returning a custom subset of repo data to feed into an application for displaying data, such as a static site generator (e.g. Jekyll, Jupyter Book, mkdocs) or web hosting service (e.g. Github pages, Netlify)

## Milestone 3 (Open AI Community Focus - BigCode)
Build features to support opt-in/opt-out capabilities for data contributors for sharing of their data for different contexts/audiences
Test integration with BigCode workstreams for repo-level or file-level removal of contributor data

Target Output: Tools compatible with the Github ecosystem for supporting data contributors to assert intent and control over what their data can be used for (e.g. dataset for closed ML model, dataset for open ML model, any ML model dataset)
