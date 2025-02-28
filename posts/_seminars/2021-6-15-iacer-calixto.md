---
layout: seminar
title: "Wikipedia Entities as Rendezvous across Languages: Grounding Multilingual Language Models by Predicting Wikipedia Hyperlinks"
speaker: "Dr Iacer Calixto"
affiliation: "University of Amsterdam"
time: 5pm
series: mldl # emtti, nlp, mldl, dh 
image: null 
---

### Abstract

Masked language models have quickly become the de facto standard when processing text. Recently, several approaches have been proposed to further enrich word representations with external knowledge sources such as knowledge graphs. However, these models are devised and evaluated in a monolingual setting only. In this work, we propose a language-independent entity prediction task as an intermediate training procedure to ground word representations on entity semantics and bridge the gap across different languages by means of a shared vocabulary of entities. We show that our approach effectively injects new lexical-semantic knowledge into neural models, improving their performance on different semantic tasks in the zero-shot cross-lingual setting. As an additional advantage, our intermediate training does not require any supplementary input, allowing our models to be applied to new datasets right away. In our experiments, we use Wikipedia articles in up to 100 languages and already observe consistent gains compared to strong baselines when predicting entities using only the English Wikipedia. Further adding extra languages lead to improvements in most tasks up to a certain point, but overall we found it non-trivial to scale improvements in model transferability by training on ever increasing amounts of Wikipedia languages.

### Speaker's bio

Iacer Calixto is a Marie-Sklodowska Curie Global Fellow at the University of Amsterdam and a visiting postdoctoral fellow in the Center for Data Science in New York University. He is interested in modelling human language production and understanding in a broad sense. In so doing, his research focuses on meaning as a function of the interaction between language, visual perception, commonsense, and structured knowledge. Some of the concrete questions he has been working on include how general-purpose (vision and) language models generalise, and also how to make use of Wikipedia entities to improve neural language models (the topic of our talk).
