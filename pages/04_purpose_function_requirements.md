---
title: State purpose, function and requirements
type: steps
page_id: 04_purpose_function_requirements
description: Document your tool or workflow to clearly describe purpose, function and requirements. E.g. annotations, standard metadata files, long form text descriptions, complete user documentation and / or software publication. 
---


## Why?



## How?

### 1. Ontology terms and tags

Ontologies are standardised dictionaries for specific domains, and make sure that researchers are using the same names to describe the same concepts. EDAM is a good choice for bioscience[Ison2013]. It is under constant development and is used by registries (e.g. bio.tools[Ison2019], WorkflowHub[Goble2021]). This interactive browser created by the EDAM team makes selecting terms a breeze: https://edamontology.github.io/edam-browser. If EDAM is not suitable, you can use FAIRsharing to locate additional ontologies (https://fairsharing.org/search?fairsharingRegistry=Standard) [Sansone2019]. You can also add custom tags or keywords to your software. Terms commonly used in your research community or domain would be a good start.

### 2. Standard metadata files

The next level for annotations is to include metadata files alongside your software that are both human and machine-readable. Good options include:

- Citation file format (`CITATION.cff`)[Druskat2021].
- Codemeta (`codemeta.json`, https://codemeta.github.io/)[Jones2017]. This project offers a useful online wizard that generates a correctly structured `codemeta.json` file for you: https://codemeta.github.io/codemeta-generator/.

### 3. Long form text descriptions: 

Additional long form descriptions can be added directly to websites, platforms or registries where your software can be accessed [Lee2018][Hermann2022]. 

### 4. Complete documentation sets

Long form text descriptions, which should cover purpose, scope and requirements, can be extended to create complete documentation (covered well in this Ten Simple Rules article[Lee2018]). 

{% include callout.html type="tip" content="If you do this, you do not need to start from scratch every time. Make life easier for yourself by reusing one of the approaches detailed below!" %}

- Reuse a template that is used in your community. Did you know that by using a blank community template (e.g. nf-core, https://nf-co.re/tools/#creating-a-new-pipeline, https://github.com/AustralianBioCommons/doc_guidelines) you can address almost all of the steps described here! 
- A point-and-click build a README template (https://readme.so/)[Oelsner2023]. 
- Automated documentation tools, as described in rule number eight of `Ten Simple Rules for documenting scientific software` [Lee2018].

### 5. Software publication

The final, most time consuming, and arguably most valuable avenue is to document your software in a peer-reviewed journal publication[Romano2020]. Aside from documentation, the literature is the most obvious place to look for software purpose and function, as publications explain the context in which the software was created. If you’re not sure where to publish, a list of target journals is available from the Software Sustainability Institute [ChueHong2023]. When publishing, don’t forget to use your ORCID to identify yourself as an author [step #6](#06_orcid).


## Examples

We have included examples here that follow one or more annotation and documentation best practices:

- PacBio HiFi genome assembly using hifiasm[Price2022].
- rnaseq nf-core workflow[Patel2023]. 
- bio-cwl-tools collection (https://github.com/common-workflow-library/bio-cwl-tools): includes tools and workflows that embed metadata into the CWL code. For example, `Kraken2` [Wood2019] in this collection uses Schema.org [Guha2015] metadata annotations: https://github.com/common-workflow-library/bio-cwl-tools/blob/258190fac5bb35500544229ff9d679026b5f3aeb/kraken2/kraken2.cwl .


## References


## Resources

