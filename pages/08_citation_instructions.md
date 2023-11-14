---
title: Include clear citation instructions
type: steps
page_id: 08_citation_instructions
description: Provide clear citation instructions to users of your tool or workflow, for example by using a standard file (e.g. CITATION.cff). 
---


**Make sure others know how to cite your software by providing clear instructions, or by using standards like the citation file format (*.CFF).**


## How?

You can use one, or more, of the following options to clearly indicate to users how to cite your software. 

Don't forget to also consult the [Software Citation Checklist for Developers](https://doi.org/10.5281/zenodo.3482769) {% cite chue_hong_software_2019 %}. 

### Use services that render a citation for you

| Source      | Citation example                                                                                                                                                                                                              |
|-------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| WorkflowHub | `Price, G., & Farquharson, K. (2022). PacBio HiFi genome assembly using hifiasm v2.1. WorkflowHub. https://doi.org/10.48546/WORKFLOWHUB.WORKFLOW.221.3` {% cite price_pacbio_2022 %}                                 |
| Zenodo      | `Anne Fouilloux, & Melanie Föll. (2021). Galaxy workflow from Galaxy 101 for everyone (1.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.5090049` {% cite fouilloux_galaxy_2021 %} |

{% include callout.html type="note" content="Some platforms also allow you to select from multiple citation styles." %}


### Formatted citations in your documentation

Adding a `how-to cite` section to your documentation allows you to specify exactly how you would like someone else to cite your software {% cite lee_ten_2018 %}.


### Include standard files

Standard metadata files provided alongside your software that are both human and machine-readable can include citation information.

{% include callout.html type="tip" content="Use the available online wizards to create [`codemeta.json`](https://codemeta.github.io/codemeta-generator/) and [`CITATION.cff`](https://citation-file-format.github.io/cff-initializer-javascript/#/) files!" %}


####  `CITATION.CFF`

The {% tool "cff" %} {% cite druskat_citation_2021 %} example below is from the following workflow: Price, G., & Farquharson, K. (2022). PacBio-HiFi-genome-assembly-using-hifiasm (Version 2.1.0) [Computer software]. https://doi.org/10.48546/WORKFLOWHUB.WORKFLOW.221.3

```yaml
cff-version: 2.1.0
message: "If you use this workflow, please cite it as below."
authors:
  - family-names: "Price"
    given-names: "Gareth"
    orcid: "https://orcid.org/0000-0003-2439-8650"
  - family-names: "Farquharson"
    given-names: "Katherine"
    orcid: "https://orcid.org/0000-0002-9009-7453"
title: "PacBio-HiFi-genome-assembly-using-hifiasm"
version: 2.1.0
doi: 10.48546/WORKFLOWHUB.WORKFLOW.221.3
date-released: 2022-10-21
```

#### `codemeta.json` 

A {% tool "codemeta" %} {% cite jones_codemeta_2017 %} file is included for this example workflow: Kasinadhuni, N., Al Bkhetan, Z., Zakrzewski, M., Chan, K., Winter, U., & Gustafsson, J. (2023). HiFi de novo genome assembly workflow (Version 1.1.0) [Computer software]. https://github.com/AustralianBioCommons/hifi-assembly-workflow


## References

{% bibliography --cited %}


## Page resources

