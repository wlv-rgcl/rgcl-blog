---
layout: post
title: "Datasets annotated with signs of syntactic complexity"
slug: ""
image: null
---

In our paper:

> Evans, R., & Orasan, C. (2013). [Annotating signs of syntactic complexity to support sentence simplification](https://www.researchgate.net/publication/256547247_Annotating_Signs_of_Syntactic_Complexity_to_Support_Sentence_Simplification). In I. Habernal & V. Matousek (Eds.), Text, Speech and Dialogue. Proceedings of the 16th International Conference TSD 2013. Plzen, Czech Republic: Springer. pp. 92 – 104

we present the annotation of a dataset that is used by our syntactic simplification method to identify places where rewriting rules have to be applied in order to produce simpler sentences. 

The datasets are available in XML format as three independent files, each representing a different genre

- [news texts](http://rgcl.wlv.ac.uk/resources/SignsOfSyntacticComplexity/News.signTagged.xml)
- [health related leaflets](http://rgcl.wlv.ac.uk/resources/SignsOfSyntacticComplexity/Health.signTagged.xml)
- [literature](http://rgcl.wlv.ac.uk/resources/SignsOfSyntacticComplexity/Literature.signTagged.xml)

Each file contains a list of sentences annotated using the following format:

```xml
<S ID="2"><SIGN ID="2" CLASS="SSEV">That</SIGN> is 
<SIGN ID="3" CLASS="HELP">,</SIGN> a high-fibre diet, 
fluid <SIGN ID="4" CLASS="CLN">,</SIGN> etc.</S>
```

The sentences are marked using the **S** tag, whilst the signs by the tag **SIGN**. The type of sign is encoded by the attribute **CLASS**. The sentences were annotated in isolation, so the files above do not contain coherent texts, but sequences of sentences extracted from different files. 

To understand the difference between different classes and how the annotation process was carried out please consult the [annotation guidelines](http://rgcl.wlv.ac.uk/wp-content/uploads/2018/11/PotentialCoordinatorAnnotationGuidelines4.pdf). Specific questions about the annotation should be sent to Richard Evans. A demo of the sign tagger is available at <http://rgcl.wlv.ac.uk/demos/SignTaggerWebDemo/>. 

You can find out more about our approach for syntactic simplification in our recent paper:

> Evans, Richard, and Constantin Orǎsan. 2018. “Identifying Signs of Syntactic Complexity for Rule-Based Sentence Simplification.” Natural Language Engineering. <https://doi.org/10.1017/S1351324918000384>.

