---
layout: seminar
title: "A Medley of Event-Based Modality and Role Question Generation"
speaker: "Valentina Pyatkin"
affiliation: "Bar Ilan University (Israel)"
time: 2pm
series: nlp # emtti, nlp, mldl, dh 
image: null 
---

### Abstract
In the talk I’ll present two papers.  The first paper is called “The Possible, the Plausible, and the Desirable: Event-Based Modality Detection for Language Processing” (ACL 2021): Modality is the linguistic ability to describe events with added information such as how desirable, plausible, or feasible they are.  Modality is important for many NLP downstream tasks such as the detection of hedging, uncertainty, speculation, and more.  Previous studies that address modality detection in NLP often restrict modal expressions  to a closed syntactic class, and the modal sense labels are vastly different across different studies, lacking an accepted standard. Furthermore, these senses are often analyzed independently of the events that they modify. This work builds on the theoretical foundations of the Georgetown Gradable Modal Expressions (GME) work by Rubinstein et al. (2013) to propose an event-based modality detection task where modal expressions can be words of any syntactic class and sense labels are drawn from a comprehensive taxonomy which harmonizes the modal concepts contributed by the different studies.  We present experiments on the GME corpus aiming to detect and classify fine-grained modal concepts and associate them with their modified events.  We show that detecting and classifying modal expressions is not only feasible, but also improves the detection of modal events in their own right.
 
In the second part of the talk I will present “Asking It All: Generating Contextualized Questions for any Semantic Role” (EMNLP 2021): Asking questions about a situation is an inherent step towards understanding it.  To this end, we introduce the task of role question generation, which, given a predicate mention and a passage, requires producing a set of questions asking about all possible semantic roles of the predicate. We develop a two-stage model for this task, which first produces a context-independent question prototype for each role and then revises it to be contextually appropriate for the passage. Unlike most existing approaches to question generation, our approach does not require conditioning on existing answers in the text. Instead, we condition on the type of information to inquire about, regardless of whether the answer appears explicitly in the text, could be inferred from it, or should be sought elsewhere. Our evaluation demonstrates that we generate diverse and well-formed questions for a large, broad-coverage ontology of predicates and roles.

### Speaker's bio
Valentina Pyatking is a PhD Student at the Computer Science Department of Bar-Ilan University, supervised by Prof. Ido Dagan and Prof. Reut Tsarfaty. She received her BA from the University of Zurich and her MSc in AI from the University of Edinburgh. Her research focuses on discourse phenomena, of which many implicit, for example by representing semantic and discourse information via question and answer pairs; generating questions for explicit, implicit and missing arguments; and classifying event-based modality senses. 

Website: [https://valentinapy.github.io/](https://valentinapy.github.io/)
