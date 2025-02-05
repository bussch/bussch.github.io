---
title: "Generating Data Augmentation Queries Using Large Language Models" 
date: 2023-07-01
lastmod: 2023-07-01
tags: ["data integration", "databases", "online learning", "reinforcement learning", "information retrieval", "large language models", "machine learning"]
author: ["Christopher Buss", "Jasmin Mousavi", "Mikhail Tokarev", "Arash Termehchy", "David Maier", "Stefan Lee"]
description: "This paper evaluates parameter efficent techniques for producing more effective data integration queries."
summary: "As an alternative to manually writing mappings from entities to queries, one can learn these mappings progressively by leveraging end users’ feedback. We evaluate the use of parameter efficient techniques for leveraging a pretrained large language model (LLM) for this task of online query policy learning. We evaluate teqniques for parameter efficent fine-tuning of LLMs online. *Also presented at the 2nd NeurIPS Table Representation Learning Workshop, December, 2023.*" 
cover:
    image:
    alt:
    relative: false
editPost:
    URL:
    Text:

---

---

##### Related material

+ [Paper](LLMDB3.pdf)
+ [Code + Datasets](https://github.com/bussch/QueryBasedEntityAugmentation)
+ [Slides (LLMDB '23 @ VLDB)](augmentation_queries-llmdb23.pdf)
+ [Poster (TaDa '23 @ NuerIPS)](augmentation_queries-trl-neurips_2023.pdf)

---

##### Abstract

Users often want to augment entities in their datasets with relevant information from external data sources. As many external sources are accessible only via keyword-search interfaces, a user usually has to manually formulate a keyword query that extracts relevant information for each entity. This is challenging as many data sources contain numerous tuples, only a small fraction of which may be relevant. Moreover, different datasets may represent the same information in distinct forms and under different terms. In such cases, it is difficult to formulate a query that precisely retrieves information relevant to a specific entity. Current methods for information enrichment mainly rely on resource-intensive manual effort to formulate queries to discover relevant information. However, it is often important for users to get initial answers quickly and without substantial investment in resources (such as human attention). Thus, as an alternative to manually writing mappings from entities to queries, one can learn these mappings progressively by leveraging end users’ feedback. We evaluate the use of parameter efficient techniques for leveraging a pretrained large language model (LLM) for this task of online query policy learning.

---

##### Citation

**Christopher Buss**, Jasmin Mousavi, Mikhail Tokarev, Arash Termehchy, David Maier, and Stefan Lee. 2023. ”Generating Data Augmentation Queries Using Large Language Models”, *Joint Proceedings of Workshops at the 49th International Conference on Very Large Data Bases (VLDB 2023)*.
*Also presented at the 2nd NeurIPS Table Representation Learning Workshop, December, 2023.*

```BibTeX
@inproceedings{buss2023generating,
  title = {Generating Data Augmentation Queries Using Large Language Models},
  author = {Buss, Christopher and Mousavi, Jasmin and Tokarev, Mikhail and Termehchy, Arash and Maier, David and Lee, Stefan},
  numpages = {5},
  url = {https://ceur-ws.org/Vol-3462/LLMDB3.pdf},
  crossref = {LLMDB23}
}

@proceedings{LLMDB23,
  booktitle = {Workshop on Databases and Large Language Models (LLMDB)},
  year = {2023},
  number = {3462},
  series = {CEUR Workshop Proceedings},
  address = {Aachen},
  issn = {1613-0073},
  url = {https://ceur-ws.org/Vol-3462/},
  venue = {Vancouver, BC},
  eventdate = {2023-09-01},
  title = {Joint Proceedings of Workshops at the 49th International Conference on Very Large Data Bases (VLDB 2023)}
}
```