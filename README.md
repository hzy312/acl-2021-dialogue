# Conversations Are Not Flat: Modeling the Dynamic Information Flow across Dialogue Utterances

* paper: https://aclanthology.org/2021.acl-long.11.pdf
* code: https://github.com/ictnlp/DialoFlow

```DialoFlow```: model the dynamic information flow in the whole dialogue history by addressing the semantic influence brought about by each utterance in the sequence

```FLow Score:```




$$
s_k = cos(<I^{'}_k,I_k>)\cdot length(I^{'}_k\cdot I_k)
$$

$$
Flow\_score = 2^{-\frac{1}{M}\sum_k^M \log(\frac{s_k+1}{2})}
$$



