---
title: "IQ-VQA: Intelligent Visual Question Answering"
excerpt: "A model independent framework that increases the consistency and robustness of any VQA model without degrading its performance.<br/> [Github](https://github.com)
<br/><img src='/images/Hardware_Design.png' width='350' height='350'>"
collection: portfolio
---

## Abstract
Even though there has been tremendous progress in the field of Visual Question Answering, models today still tend to be inconsistent and brittle. To this end, we propose a 
model-independent cyclic framework which increases consistency and robustness of any VQA architecture. We train our models to answer the original question, generate an implication 
based on the answer and then also learn to answer the generated implication correctly. As a part of the cyclic framework, we propose a novel implication generator which can 
generate implied questions from any question-answer pair. As a baseline for future works on consistency, we provide a new human annotated VQA-Implications dataset. The dataset 
consists of ~30k questions containing implications of 3 types - Logical Equivalence, Necessary Condition and Mutual Exclusion - made from the VQA v2.0 validation dataset. 
We show that our framework improves consistency of VQA models by ~15% on the rule-based dataset, ~7% on VQA-Implications dataset and robustness by ~2%, without degrading their 
performance. In addition, we also quantitatively show improvement in attention maps which highlights better multi-modal understanding of vision and language. <br/>

## Architecture
<img src='/images/Screenshot%20from%202019-08-02%2015-40-24.png' width='480'><br/>
[Github](https://github.com)

[Download Paper here](https://arxiv.org/pdf/2007.04422.pdf)