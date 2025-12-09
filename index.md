---
layout: default
---

## Abstract

Graph data with multimodal information is ubiquitous, from users posting content on social networks and customers buying products on e-commerce platforms to patients interconnected with diseases and drugs in electronic health records (EHRs). For these reasons, graph machine learning has gradually shifted from a unimodal to a multimodal paradigm over the past few years. Despite their effectiveness, these approaches may be greatly limited if such multimodal information is noisy or (even worse) missing---a quite common situation in real-world scenarios. This tutorial intends to provide one of the first formal and practical outlooks on established and recent techniques to impute missing multimodal information in graph machine learning. By first introducing traditional graph approaches to tackle missing information in unimodal settings, it then presents the current literature on imputation for multimodal data in graph machine learning. Moreover, the tutorial offers an overview on popular applicative scenarios where the missing information issue occurs, such as the recommendation and healthcare domains, highlighting how graphs can be the source of missingness (the former) or the tools to address the missingness of multimodal information (the latter). The applicative scenarios are further explored during a hands-on session, which presents and tests the complete experimental pipeline of two recent solutions.

## Tutorial schedule

**Date:** December 12, 2025 (11:30 - 14:00 MST)

**Tutorial duration:** 150 minutes

**Tutorial's type:** lecture style + hands-on   

* **Introduction and background** (15 min)
    * Introduction and motivations of the tutorial (5 min)
    * Basic concepts of imputation in machine learning (7 min)
    * Tutorial’s overview (3 min)
* **Graph machine learning with missing multimodal information** (65 min)
  * Missing information in unimodal graph machine learning (15 min)
    * Sources of missing information: node attributes, node features, edges
    * Models’ taxonomy: impute on or through graph, robustness vs. imputation
    * Main existing techniques
  * Multimodal graph learning (20 min)
    * Integrating multimodal information in the graph learning pipeline
    * Notable applications: recommendation and healthcare
  * Missing information in multimodal graph machine learning (30 min)
    * How to define missing multimodal information on graphs
    * Models’ taxonomy: impute on or through graphs, robustness vs. imputation, node similarity vs bipartite graphs
    * Dealing with missing modalities in multimodal recommendation
    * Handling missing multimodal information in healthcare
* **Hands-on session: tackling missing multimodal information in personalized recommendation and healthcare** (50 min)
  * An imputation pipeline for missing multimodal information in recommendation (25 min)
  * Multimodal processing and training with missing information in healthcare (25 min)
* **Closing remarks, current challenges, and future directions** (10 min)
* **Q&A session** (10 min)

## Useful material

**Slides:** [**[pdf]**](https://drive.google.com/file/d/1knU_mgo3i_5kD5GuOls6zPD5IBodmpig/view?usp=sharing)  

**Tutorial's paper:** [**[pdf]**](https://log-centralesupelec.github.io/missing-multimod-gml-log2025/Graph_Machine_Learning_with_Missing_Multimodal_Information.pdf)  

**Hands-on #1:** [**[notebook]**](https://drive.google.com/file/d/1gFfGvJLvGensD1qBLCnnyK_RkfqigTfa/view?usp=sharing)  

**Hands-on #2:** [**[notebook]**](https://drive.google.com/file/d/1ggysCRkb0f7NBo6AGQdegpAyveOKX3QQ/view?usp=sharing)

## Tutorial speakers

### Daniele Malitesta

_Postdoc researcher at Université Paris-Saclay, CentraleSupélec, Inria (Gif-sur-Yvette, France)_

Email: [daniele.malitesta@centralesupelec.fr](mailto:daniele.malitesta@centralesupelec.fr)

Website: [https://danielemalitesta.github.io/](https://danielemalitesta.github.io/)

<img src="https://danielemalitesta.github.io/images/profilo_new.jpeg" alt="Daniele Malitesta"  width="200"/>

### Fragkiskos D. Malliaros

_Professor at Université Paris-Saclay, CentraleSupélec, Inria (Gif-sur-Yvette, France)_

Email: [fragkiskos.malliaros@centralesupelec.fr](mailto:fragkiskos.malliaros@centralesupelec.fr)

Website: [https://fragkiskosm.github.io/](https://fragkiskosm.github.io/)

<img src="https://media.licdn.com/dms/image/v2/C4E03AQFCLZOLp2dFvQ/profile-displayphoto-shrink_400_400/profile-displayphoto-shrink_400_400/0/1650112432140?e=2147483647&v=beta&t=vQGyoD3ZJDVUwSlw1ge0rzyqzMEoEYYoH_kjrBjNG7Q" alt="Claudio Pomo"  width="200"/>
