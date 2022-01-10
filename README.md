# TIPS

* This repo collects the paper and corresponding official code from acl-2021 in dialogue domain
* TOPICS:  ```dialogue response generation```   ```dialogue summarization```   ``` dialogue emotion detection```   ```task-oritented dialogue system```  ```dialogue relation extraction``` ```dialogue contradiction detection```

* 

# Conversations Are Not Flat: Modeling the Dynamic Information Flow across Dialogue Utterances

* **generation-based dialogue system**

* paper: https://aclanthology.org/2021.acl-long.11.pdf
* code: https://github.com/ictnlp/DialoFlow

```DialoFlow```: model the dynamic information flow in the whole dialogue history by addressing the semantic influence brought about by each utterance in the sequence

```FLow Score:```

<img src="https://latex.codecogs.com/svg.image?s_k&space;=&space;cos(<I^{'}_k,I_k>)\cdot&space;length(I^{'}_k&space;\cdot&space;I_k)" title="s_k = cos(<I^{'}_k,I_k>)\cdot length(I^{'}_k \cdot I_k)" />

<img src="https://latex.codecogs.com/svg.image?2^{\frac{-1}{M}\sum_k^M&space;\log(\frac{s_k&plus;1}{2})}" title="2^{\frac{-1}{M}\sum_k^M&space;\log(\frac{s_k+1}{2})}" />

# Dual Slot Selector via Local Reliability Verification for Dialogue State Tracking

* **dialogue state tracking**

* paper: https://aclanthology.org/2021.acl-long.12.pdf
* code: https://github.com/guojinyu88/DSSDST

```dual slot selector```: based on current turn dialogue

```slot value generator```: based on the dialogue history

# Transferable Dialogue Systems and User Simulators

* dialogue systems with reinforcement learning

* paper: https://aclanthology.org/2021.acl-long.13.pdf
* code: https://github.com/andy194673/joust

Joint optimization with a simulator(JOUST)

# BoB: BERT Over BERT for Training Persona-based Dialogue Models from Limited Personalized Data

* persona-based dialogue system(in low-resource personalized-data scenario)

* paper: https://aclanthology.org/2021.acl-long.14.pdf
* code:  https://github.com/songhaoyu/BoB

task1 : consistency understanding using non-dialogue inference corpus to train

task2: dialogue generation(could use persona-sparse dataset to train)

# SocAoG: Incremental Graph Parsing for Social Relation Inference in Dialogues

* social relationship inference from dialogue

* paper: https://aclanthology.org/2021.acl-long.54.pdf
* code: https://github.com/Liang-Qiu/SocAoG-dialogues

model social relation as an attributed And-Or graph

# Learning from Perturbations: Diverse and Informative Dialogue Generation with Inverse Adversarial Training

* dialogue response generation( focusing on avoiding the generic response and generating diverse, consistent response with **Inverse Adversarial Training**)

* paper: https://aclanthology.org/2021.acl-long.57.pdf

* code: NULL

conventional adversarial training wants to keep the output un-changed while undertaking the perturbations

```Inverse Adversarial Training``` aims to generate different response while small perturbations in the dialogue history

# Increasing Faithfulness in Knowledge-Grounded Dialogue with Controllable Features

* knowledge-grounded dialogue system

* paper: https://aclanthology.org/2021.acl-long.58.pdf
* code: NULL

adding controllability in the dialogue model: ```control code features ```    and    ```control resampling```

# Language Model as an Annotator: Exploring DialoGPT for Dialogue Summarization

* dialogue summarization
* paper: https://aclanthology.org/2021.acl-long.117.pdf
* code: https://github.com/xcfcode/PLM_annotator

```keyword extraction```    ``` redundancy detection```    ``` topic segmentation```

![image-20220107161008540](https://github.com/hzy312/acl-2021-dialogue-papers/blob/main/images/dialogue-annotator-summarization.png)

# Topic-Driven and Knowledge-Aware Transformer for Dialogue Emotion Detection
* dialogue emotion detection
* paper: https://aclanthology.org/2021.acl-long.125.pdf
* code:  http://github.com/something678/TodKat

topic-driven

# I like fish , especially dolphins : Addressing Contradictions in Dialogue Modeling

* dialogue contradiction detection
* paper: https://aclanthology.org/2021.acl-long.134.pdf
* code: https://parl.ai/projects/contradiction

```DECODE```: DiloguE COtradiction DEtection task

# Dialogue Response Selection with Hierarchical Curriculum Learning

* dialogue response selection
* paper: https://aclanthology.org/2021.acl-long.137.pdf
* code: https://github.com/yxuansu/HCL

# Discovering Dialogue Slots with Weak Supervision

* task-oriented dialogue system(dialogue slots discovery)
* paper: https://aclanthology.org/2021.acl-long.189.pdf
* code: https://github.com/vojtsek/joint-induction

automatic domain-generic annotation

identify domain-relevant slots based on the previous annotation

# Comprehensive Study: How the Context Information of Different Granularity Affects Dialogue State Tracking?

* dialogue state tracking
* paper: https://aclanthology.org/2021.acl-long.193.pdf
* code: https://github.com/yangpuhai/Granularity-in-DST

# OTTers: One-turn Topic Transitions for Open-Domain Dialogue

* one-turn topic transition

* paper: https://aclanthology.org/2021.acl-long.194.pdf
* code:  https://github.com/karinseve/OTTers

natural language generation according to one-turn topic transition

# Towards Quantifiable Dialogue Coherence Evaluation

* automatic dialogue coherence evaluation
* paper: https://aclanthology.org/2021.acl-long.211.pdf
* code:  https://github.com/James-Yip/QuantiDCE

dialogue coherence: fluent , consistent and context-related

multi-level ranking(**MLR**) pre-training and knowledge distillation(**KD**) fine-tuning

```QuantiDCE```: Quantifiable Dialogue Coherence Evaluation

# Novel Slot Detection: A Benchmark for Discovering Unknown Slot Types in the Task-Oriented Dialogue System

* slot detection in ToD
* paper: https://aclanthology.org/2021.acl-long.270.pdf
* code: https://github.com/ChestnutWYN/ACL2021-Novel-Slot-Detection

**Novel Slot Detection(NSD)**: detect the unknown or out-of-domain slot types based on the in-domain corpus

dataset: Snips-NSD    ATIS-NSD

evaluation metric: Span-F1 Token-F1

# NeuralWOZ: Learning to Collect Task-Oriented Dialogue via Model-Based Simulation

* dialogue generation
* paper: https://aclanthology.org/2021.acl-long.287.pdf
* code:  https://github.com/naver-ai/neuralwoz

# Semantic Representation for Dialogue Modeling

* amr(abstract meaning representation) graph for dialogue modeling
* paper: https://aclanthology.org/2021.acl-long.342.pdf
* code: https://github.com/muyeby/AMR-Dialogue

introduce amr graph to better model the dialogue and help the downstream dialogue task

task1: dialogue relation extraction

task2: response generation

# Structural Pre-training for Dialogue Comprehension

* 
* paper: https://aclanthology.org/2021.acl-long.399.pdf
* code: https://github.com/cooelf/SPIDER

```SPIDER```:**Structured PretraIned DialoguE Reader**

additional training objective: utterance order restoration        sentence backbone regularization

dialogue related features: speaker role, continuity and consistency