---
layout: post
title: "Papers accepted at ACL-IJCNLP 2021 and NAACL-HWT 2021"
slug: "Congratulations to Dr Frédéric Blain who has had the following papers accepted at upcoming conferences."
image: null
---

**Title**: *Knowledge Distillation for Quality Estimation*

**Authors**: *Amit Gajbhiye, Marina Fomicheva, Fernando Alva-Manchego, Frédéric Blain, Abiola Obamuyide, Nikolaos Aletras and Lucia Specia*

**Abstract**: Quality Estimation (QE) is the task of automatically predicting Machine Translation quality in the absence of reference translations, making it applicable in real-time settings, such as translating online social media conversations. Recent success in QE stems from the use of multilingual pre-trained representations,where very large models lead to impressive results. However, the inference time, disk and memory requirements of such models do not allow for wide usage in the real world.

Attempts have been made at making pre-trained representations less resource-hungry by using knowledge distillation, but the resulting models remain prohibitively large for many usage scenarios.Instead of building upon distilled pre-trained representations, we propose to transfer knowledge from a strong QE teacher model to a much smaller model with a different, shallower architecture. In combination with a confidence-based data augmentation approach, we show that it is possible to create light-weight QE models that achieve comparable results to distilled pre-trained representations with 8x fewer parameters.

This paper should appear in the Findings of ACL-IJCNLP 2021 (see <https://2021.aclweb.org/>).

---

**Title**: *Backtranslation Feedback Improves User Confidence in MT, Not Quality*

**Authors**: *Vilém Zouhar, Michal Novák, Matúš Žilinec, Ondřej Bojar, Mateo Obregón, Robin L. Hill, Frédéric Blain, Marina Fomicheva, Lucia Specia, Lisa Yankovskaya*

**Abstract**: Translating text into a language unknown to the text’s author, dubbed outbound translation, is a modern need for which the user experience has significant room for improvement, beyond the basic machine translation facility. We demonstrate this by showing three ways in which user confidence in the outbound translation, as well as its overall final quality, can be affected: backward translation, quality estimation (with alignment) and source paraphrasing. In this paper, we describe an experiment on outbound translation from English to Czech and Estonian. We examine the effects of each proposed feedback module and further focus on how the quality of machine translation systems influence these findings and the user perception of success. We show that backward translation feedback has a mixed effect on the whole process: it increases user confidence in the produced translation, but not the objective quality.

This paper will appear at NAACL-HWT 2021 (<https://2021.naacl.org/>).

The paper can also be found here: <https://arxiv.org/abs/2104.05688>.


