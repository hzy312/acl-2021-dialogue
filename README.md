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

Joint optimisation with a simulator(JOUST)

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

