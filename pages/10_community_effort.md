---
title: Join or align with a community effort
type: steps
page_id: 10_community_effort
description: Align to, follow, or join a community effort that is relevant to your software. For example, coding language, platform, or scientific domain specific communities.
---


{% include callout.html type="important" content="Join, or align with, a community that is related to your software type or language. Their standards and guidelines will often help make your software findable and citable." %}


## How?

Using a {% tool "nextflow" %} computational workflow as an example, there are effectively three levels of community involvement:

1. Just adopting Nextflow, as it is a popular and well maintained workflow language.
2. Following community defined (i.e. {% tool "nf-core" %}) workflow development best practices.
3. Joining the nf-core community and contributing a workflow directly to their existing maintained collection.


## Examples

- **{% tool "cwl" %}**
- **{% tool "galaxy" %}**: The Galaxy project has many communities that address software. The most prominent include the Intergalactic Utilities Commission (IUC) and IWC who look after software tools and computational workflows respectively. There are also many domain specific communities as well, including for example, microGalaxy and Galaxy-Proteomics (Galaxy-P).
- **{% tool "python" %}**
- **{% tool "nextflow" %}**: {% tool "nf-core" %} is a significant effort in this space, and there are talks, training and hackathons you can join. Check out their [`join nf-core`](https://nf-co.re/join) page to find out how to get involved. 
- **{% tool "r" %}**: {% tool "bioconductor" %}
- **{% tool "snakemake" %}**: Visit the {% tool "snakemake-community" %} and don’t forget to check the different ways you can get [support](https://snakemake.readthedocs.io/en/stable/#support).

{% include callout.html type="tip" content="Are you not sure which community to join? You could start by joining one of the many [RSE societies](https://researchsoftware.org/) that exist globally. These communities address many of the challenges faced by creators of research-centric software, including visibility of their contribution to research." %}
 

### Table 3. A selection of community guidelines and standards for software.

| Practice  | IWC (Galaxy | nf-core (Nextflow) | Snakemake-workflows + [guidelines](https://github.com/snakemake-workflows/docs#guidelines) + [distribution & reproducibility](https://snakemake.readthedocs.io/en/stable/snakefiles/deployment.html#distribution-and-reproducibility) | FAIR4RS {% cite barker_introducing_2022 %} | [ELIXIR SMP](https://github.com/elixir-europe/smp) {% cite alves_elixir_2021 %} |
|----|---|---|---|---|---|
| Automated testing | Yes  | Yes | Yes | No | Yes |
| Versioning | Yes | Yes | No | Yes | Yes |
| Documentation | Yes | Yes | Yes | Yes | Yes |
| Changelog | Yes  | Yes | No | Yes | Yes |
| Licence | Yes | Yes | Yes | Yes | Yes |
| Repository layout | Yes | Yes | Yes | No | No |
| Metadata (e.g., author) | Yes | No | No | Yes | Yes |
| Coding style | No | Yes | No | No | No |
| Containerization | No | Yes | No | No | Yes |


## References

{% bibliography --cited %}


## Page resources

