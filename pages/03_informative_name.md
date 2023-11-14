---
title: Give your tool or workflow an informative name
type: steps
page_id: 03_informative_name
description: Software names should be short, unique, searchable, and provide info about the software while avoiding a prefix (e.g. `bio`) and complex characters.
---


**An ideal name will make your software recognisable, its function understandable, and make the software easy to find using a search engine.**


## How?

Make sure that the name for your tool or workflow has at least some of the following features.


### Short & Human readable

6 - 15 characters. Shorter names are easy to search, remember, 
write and can increase name recognition.


### Unique & searchable

Make sure the name is easy for a search engine to find. Don’t pick a 
common or popular name that means something else: if the name doesn't 
clash with other findable things, it can be found immediately when searching, 
or it will be at the top of the search engine result.


### Informative

If possible, the name can explain what the tool or workflow does. 
Good examples are {% tool "bedtools" %} {% cite quinlan_bedtools_2010 %} and 
{% tool "samtools" %} {% cite li_sequence_2009 %}, as the names mention the 
data formats used (`BED`, `SAM`) and suggest that the software encompasses many tools. 

{% include callout.html type="tip" content="Some names don’t really tell 
you anything about the software. As an example, accept this challenge: 
[**Pokémon or big data term?**](http://pixelastic.github.io/pokemonorbigdata/)" %}


### Avoid prefixes e.g. `bio`

Don't use a prefix like `bio` in the name if it could be reused outside 
of the biosciences domain. The same applies for `geo`, `astro`, `eco` etc. 
You will notice that some popular tools and platforms are exceptions to 
this rule (e.g. {% tool "biotools" %} {% cite ison_biotools_2019 %}).


### Use `ASCII`

Computers and search engines don’t like complex characters and white spaces: 
use the `ASCII standard`. The key reason to avoid complex characters is that 
they create issues for findability if a software registry doesn't process these 
characters properly or if the name is challenging for a user to type.


## Examples

Great software name examples include {% tool "workflowhub" %}, {% tool "fastqc" %} 
and {% tool "hifiadapterfilt" %}. Each name is short, unique, searchable, and 
provides information about the software while avoiding both the `bio` prefix 
and complex characters.


## References

{% bibliography --cited %}


## Page resources

