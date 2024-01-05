# Mutual Information in Continual Learning

This project was done as part of the Deep Learning: Theory and Data Science course at the University of Toronto by Nathan Gurrin-Simth and Prasanth YSS.

Continual learning problems are an important task for many real-world situations. In continual learning, models
are updated rather than retrained when new data comes along. Such an approach can be computationally more
efficient since it wouldn’t be necessary to run through an entire offline training process multiple times. Additionally,
on devices with smaller storage, it may be infeasible to store an entire data set to enable retraining, and so
a continual learning setup is essential. However, despite these benefits, continual learning faces several issues,
including catastrophic forgetting which could stand in the way of their inclusion in products. We investigate the
potential of using mutual information to understand catastrophic forgetting.

We show that the mutual information of the model decreases in the continual learning phase. We also observe
a strong correlation between model accuracy and it’s mutual information I(Y1,H). In the approaches where the
accuracy decreases in the online phases, mutual information also decreases. We also show that rehearsal
approaches like SIESTA are better at retaining the mutual information learned during the pre-training phase.
