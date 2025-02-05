---
title: "Effective Entity Augmentation By Querying External Data Sources" 
date: 2023-07-01
lastmod: 2023-07-01
tags: ["data integration", "databases", "online learning", "reinforcement learning", "information retrieval", "large language models", "machine learning"]
author: ["Christopher Buss", "Jasmin Mousavi", "Mikhail Tokarev", "Arash Termehchy", "David Maier", "Stefan Lee"]
description: "This paper describes the a framework for minimizing expert attention in data integration systems. It leverages online learning and empirically evaluates how models perform under this framework. This paper was accepted and presented at VLDB 2023." 
summary: "Users often need to integrate information from multiple data sources. This paper proposes autonomous systems that progressively discover and integrate relevant information from multiple data sources while requiring minimal expert intervention. The proposed systems leverage end users' feedback to learn how to retrieve information relevant to each entity in a dataset from external data sources. Our empirical evaluation shows that our approach learns accurate strategies for delivering relevant information quickly."
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

+ [Paper](entityaugmentation_pvldb23.pdf)
+ [Code + Datasets](https://github.com/bussch/QueryBasedEntityAugmentation)
+ [Recording](https://www.youtube.com/watch?v=mHr67fg9ldA)
+ [Slides](effective_entity_augmentation-vldb23.pdf)
+ [Poster](effective_entity_augmentation-poster-vldb23.pdf)

---

##### Abstract

Users often want to augment and enrich entities in their datasets with relevant information from external data sources. As many external sources are accessible only via keyword-search interfaces, a user usually has to manually formulate a keyword query that extract relevant information for each entity. This approach is challenging as many data sources contain numerous tuples, only a small fraction of which may contain entity-relevant information. Furthermore, different datasets may represent the same information in distinct forms and under different terms (e.g., different data source may use different names to refer to the same person). In such cases, it is difficult to formulate a query that precisely retrieves information relevant to an entity. Current methods for information enrichment mainly rely on lengthy and resource-intensive manual effort to formulate queries to discover relevant information. However, in increasingly many settings, it is important for users to get initial answers quickly and without substantial investment in resources (such as human attention). We propose a progressive approach to discovering entity-relevant information from external sources with minimal expert intervention. It leverages end users' feedback to progressively learn how to retrieve information relevant to each entity in a dataset from external data sources. Our empirical evaluation shows that our approach learns accurate strategies to deliver relevant information quickly.

---

##### Citation

**Christopher Buss**, Jasmin Mousavi, Mikhail Tokarev, Arash Termehchy, David Maier, and Stefan Lee. 2023. ”Effective Entity Augmentation by Querying External Data Sources”, *Proc. VLDB Endow. 16, 11 (July 2023)*, 3404–3417.

```BibTeX
@article{buss2023effective,
  author = {Buss, Christopher and Mousavi, Jasmin and Tokarev, Mikhail and Termehchy, Arash and Maier, David and Lee, Stefan},
  title = {Effective Entity Augmentation by Querying External Data Sources},
  year = {2023},
  issue_date = {July 2023},
  publisher = {VLDB Endowment},
  volume = {16},
  number = {11},
  issn = {2150-8097},
  url = {https://doi.org/10.14778/3611479.3611535},
  doi = {10.14778/3611479.3611535},
  abstract = {Users often want to augment and enrich entities in their datasets with relevant information from external data sources. As many external sources are accessible only via keyword-search interfaces, a user usually has to manually formulate a keyword query that extract relevant information for each entity. This approach is challenging as many data sources contain numerous tuples, only a small fraction of which may contain entity-relevant information. Furthermore, different datasets may represent the same information in distinct forms and under different terms (e.g., different data source may use different names to refer to the same person). In such cases, it is difficult to formulate a query that precisely retrieves information relevant to an entity. Current methods for information enrichment mainly rely on lengthy and resource-intensive manual effort to formulate queries to discover relevant information. However, in increasingly many settings, it is important for users to get initial answers quickly and without substantial investment in resources (such as human attention). We propose a progressive approach to discovering entity-relevant information from external sources with minimal expert intervention. It leverages end users' feedback to progressively learn how to retrieve information relevant to each entity in a dataset from external data sources. Our empirical evaluation shows that our approach learns accurate strategies to deliver relevant information quickly.},
  journal = {Proc. VLDB Endow.},
  month = {jul},
  pages = {3404-3417},
  numpages = {14}
}
```
