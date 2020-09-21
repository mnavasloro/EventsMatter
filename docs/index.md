## Extraction of Events from Court Decisions
#### A work by Erwin Filtz, María Navas-Loro, Cristiana Santos, Axel Polleres and Sabrina Kirrane

Welcome to the webpage of our work Events Matter: Extraction of Events from Court Decisions. Here you will be able to find the code and the resources from it. If you have not read it, here is an abstract of our work; a paper with more details has been submitted to JURIX 2020, and hopefully we will have soon a paper reference for it!

> The analysis of court decisions and associated events is part of the daily life of many legal practitioners. Unfortunately, court decisions can often be long and complex, stating all types of facts relating to a case, which makes reading and understanding them a time-consuming task. Automated court decision timeline generation could provide a visual overview of what happened throughout a case by representing the main legal events, together with relevant temporal information. A necessary first step is to develop tools and technologies that can extract events from court decisions. Towards this end, in this paper we compare the effectiveness of three different extraction mechanisms, namely deep learning, conditional random fields, and rule-based, when it comes to the extraction of events and their components (i.e., the event type, who was involved, and when it happened). In addition, we provide a corpus of manually annotated decisions of the European Court of Human Rights, which serves as a gold standard not only for our experiments, but also for the research community for comparison and further experimentation.


## Corpus

The corpus consists of 30 decisions of the Eurpoean Court of Human Rights (ECHR) extracted from [the HUDOC database](https://hudoc.echr.coe.int/). The guidelines, along with discussion on some interesting cases found during the annotation process and the statistics of the corpus, is available [here](Guidelines.pdf).

Please visit [the corpus Zenodo entry](https://doi.org/10.5281/zenodo.4032617) to download the dataset itself, and to refer it until the work gets published.

## Code
To extract events and their componentes from raw text we tested different approaches, namely deep learning models, CRF and a rule-based approach. They are all available in the links below :

- Please visit [EventsMatter repository](https://github.com/efiltz/EventsMatter) for the code of the deep learning and CRF approaches.
- Please visit [WhenTheFact repository](https://github.com/mnavasloro/WhenTheFact) for the code of the rule-based approach.

## Use Case: Timeline Generation

Please visit [our Demo page](https://whenthefact.oeg-upm.net/) for a demonstration of the timeline generation, where the rule-based approach is used.

