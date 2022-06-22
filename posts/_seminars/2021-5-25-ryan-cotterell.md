---
layout: seminar
title: "Two New Insights into Beam Search"
speaker: "Prof Ryan Cotterell"
affiliation: "ETH Zurich"
time: 5pm
series: mldl # emtti, nlp, mldl, dh 
image: null 
---

### Abstract

As a simple search heuristic, beam search has been used to decode models developed by the NLP community for decades. Indeed, it is noteworthy that beam search is one of the few NLP algorithms that has stood the test of time: It has remained a cornerstone of NLP systems since the 1970s (Reddy, 1977). As such, beam search became the natural choice for decoding neural probabilistic text generators—whose design makes evaluating the full search space impossible While there is no formal guarantee that beam search will return—or even approximate—the highest-scoring candidate under a model, it has repeatedly proven its merit in practice and, thus, has largely been tolerated—even embraced—as NLP’s go-to search heuristic. This talk further embraces beam search. We discuss two novel formal insights into beam search. In the first act, we discuss an algorithmic advance that allows beam search to be prioritized, i.e. it returns the best hypothesis (modulo the beam size) first. Our algorithmic extension yields a Dijkstra-ified beam search that provably emulates standard beam search. In the second act, we draw a connection between the uniform information density hypothesis from cognitive science and beam search’s efficacy as a search heuristic. We offer a linguistic reason why beam search may work so well in practice even though, as an approximation to the argmax, it may be arbitrarily bad. The work described in this talk is described in publications at TACL (2020) and EMNLP (2020) and won an honorable mention for best paper at the latter.

### Speaker's bio

Ryan Cotterell is an Assistant Professor of computer science at ETH Zurich. He is also affiliated with the Computer Laboratory (Department of Computer Science and Technology) at the University of Cambridge where he was an Assistant Professor (Lecturer in the UK system) from 2018 to 2020. His research papers have received best-paper awards at ACL 2017 and EACL 2017 and his papers were runners-up for best paper at NAACL 2016, EMNLP 2016, ACL 2019, EMNLP 2020, and EACL 2021. During his Ph.D., he was awarded fellowships from Facebook, Fulbright, DAAD, and NDSEG. He was also awarded the Jelinek fellowship at Johns Hopkins. At ETH Zurich, his group is jocularly called Rycolab; its web presence may be found here: [rycolab.io](https://rycolab.io).

