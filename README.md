# Mellowmax-RL
When a softmax operator is used, it acts as an intermediate between the average
function and the maximum function. Usually, the softmax operator is used in settings
where maximising utility is necessary but using a single maximum utility decision
may not be a wise choice. In such cases, the Boltzmann softmax operator is the
most widely used softmax operator. However, we give examples and show that it is
prone to misbehaviour. An alternative to this softmax operator is discussed, and the
performance of this operator is compared to that of Boltzmann softmax operator in
various domains. It is shown that the alternative operator performs favourably in
practice.

Implementation of [Paper](https://arxiv.org/pdf/1612.05628.pdf)
