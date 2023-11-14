---
title: State purpose, function and requirements
page_id: 04_purpose_function_requirements
description: Document your tool or workflow to clearly describe purpose, function and requirements. E.g. annotations, standard metadata files, long form text descriptions, complete user documentation and / or software publication. 
---


**To find and understand your software, documentation that describes its function needs to be accessible to both the user and to search engines. Structured and meaningful documentation directly supports the reuse and citation of your software.**


## How?

Pick one, or more, of the following options (#1-5) for documenting your tool of workflow. These options are listed in order of increasing complexity and completeness.

{% include callout.html type="important" content="Don't forget that there are services available that allow you to check the FAIRness of your software! See [below](#check-fairness) for more details." %}


### 1. Ontology terms and tags

Ontologies are standardised dictionaries for specific domains, and make sure that researchers are using the same names to describe the same concepts. EDAM is a good choice for bioscience {% cite ison_edam_2013 %}. It is under constant development and is used by registries (e.g. {% tool "biotools" %} {% cite ison_biotools_2019 %}, {% tool "workflowhub" %} {% cite goble_implementing_2021 %}). 

If EDAM is not suitable, you can use {% tool "fairsharing" %} to [locate additional ontologies](https://fairsharing.org/search?fairsharingRegistry=Standard) {% cite sansone_fairsharing_2019 %}. You can also add custom tags or keywords to your software. Terms commonly used in your research community or domain would be a good start.

{% include callout.html type="tip" content="[EDAM browser](https://edamontology.github.io/edam-browser) makes selecting terms a breeze!" %}


### 2. Standard metadata files

The next level for annotations is to include metadata files alongside your software that are both human and machine-readable. Good options include:

- {% tool "cff" %} {% cite druskat_citation_2021 %}.
- {% tool "codemeta" %} {% cite jones_codemeta_2017 %}.

{% include callout.html type="tip" content="Use the available online wizards to create [`codemeta.json`](https://codemeta.github.io/codemeta-generator/) and [`CITATION.cff`](https://citation-file-format.github.io/cff-initializer-javascript/#/) files!" %}


### 3. Long form text descriptions

Additional long form descriptions can be added directly to websites, platforms or registries where your software can be accessed {% cite lee_ten_2018 hermann_documenting_2022 %}. 


### 4. Complete documentation sets

Long form text descriptions, which should cover purpose, scope and requirements, can be extended to create complete documentation (covered well in this Ten Simple Rules article {% cite lee_ten_2018 %}). 

{% include callout.html type="tip" content="If you do this, you do not need to start from scratch every time. Make life easier for yourself by reusing one of the approaches detailed below!" %}

- **Reuse a template that is used in your community**. Did you know that by using a blank community template (e.g. [nf-core creating a new pipeline](https://nf-co.re/tools/#creating-a-new-pipeline), [Australian BioCommons documentation guidelines](https://github.com/AustralianBioCommons/doc_guidelines)) you can address almost all of the steps described here! 
- **Build a README template using {% tool "readme_so" %}** {% cite oelsner_readmeso_nodate %}. 
- **Automated documentation tools**, as described in rule number eight of `Ten Simple Rules for documenting scientific software` {% cite lee_ten_2018 %}.


### 5. Software publication

The final, most time consuming, and arguably most valuable avenue is to document your software in a peer-reviewed journal publication  {% cite romano_ten_2020 %}. Aside from documentation, the literature is the most obvious place to look for software purpose and function, as publications explain the context in which the software was created. If you’re not sure where to publish, a list of target journals is available from the Software Sustainability Institute {% cite chue_hong_which_nodate %}. When publishing, don’t forget to use your ORCID to identify yourself as an author [step #6](#06_orcid).


## Check FAIRness

- [**FAIRsoft Evaluator**](https://openebench.bsc.es/observatory/)
- 


## Examples

We have included examples here that follow one or more annotation and documentation best practices:

- `PacBio HiFi genome assembly using hifiasm` workflow {% cite price_pacbio_2022 %}.
- `rnaseq nf-core` workflow {% cite harshil_patel_nf-corernaseq_2023 %}. 
- [`bio-cwl-tools` collection](https://github.com/common-workflow-library/bio-cwl-tools): includes tools and workflows that embed metadata into the `CWL` code. For example, `Kraken2` {% cite wood_improved_2019 %} in this collection uses `Schema.org` {% cite guha_schemaorg_2015 %} [metadata annotations](https://github.com/common-workflow-library/bio-cwl-tools/blob/258190fac5bb35500544229ff9d679026b5f3aeb/kraken2/kraken2.cwl).


## References

{% bibliography --cited %}


## Page resources

