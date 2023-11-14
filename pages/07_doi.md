---
title: Generate and use digital object identifiers (DOI)
page_id: 07_doi
description: Generate digital object identifiers (DOI) for your tools and workflows and use these to link to your software.
---


**A DOI is a persistent identifier, and allows unambiguous linking to your software.**


## How?

Below we share our recommendations.

- Scientific journal articles will come with a DOI, if you choose to publish your software in a journal. See also the [documentation step](04_purpose_function_requirements).
- If you have shared your code publicly via a repository on {% tool "github" %}, you can use {% tool "zenodo" %} {% cite european_organization_for_nuclear_research_zenodo_2013 %} to archive your repository and [issue this archive a DOI](https://docs.github.com/en/repositories/archiving-a-github-repository/referencing-and-citing-content). Currently, Zenodo will also issue a new DOI for your repository each time a new GitHub release is created.
- There are over 400,000 software DOIs in Zenodo {% cite fenner_doi_2018 noauthor_datacite_nodate %}, and so to distinguish specific software artefacts like workflows and make them more visible, you can either use a registry that is able to mint DOIs, such as {% tool "workflowhub" %}, or add your Zenodo generated DOI to a registry entry to make the best use of both resources.


## Example

We have included examples of publications where WorkflowHub DOIs are included: providing persistent links to workflows:

- {% cite satgunaseelan_viral_2022 %}
- {% cite atasoy_microbial_2023 %}
- {% cite lott_futureproofing_2022 %}

You can find additional examples by searching [Google Scholar](https://scholar.google.com/) for the core 
element of the WorkflowHub DOI: `10.48546/WORKFLOWHUB.WORKFLOW`.

<br>
<br>


## References

{% bibliography --cited %}


## Page resources

