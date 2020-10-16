# DRL-for-Anomaly-Detection-on-credit-card-transactions-data

Overall project goal
We investigate the application of Deep Reinforcement Learning to Anomaly Detection in credit
card transactions data. Our goal is the use of Q-learning, a Deep Reinforcement Learning
technique to determine fraudulent credit card transactions.

Problem Description
Anomaly detection is the process of identifying unusual patterns that do not conform to
expected normal behavior. Its applications are found in intrusion detection, system health
monitoring, and fraud detection in credit card transactions. We would review Q-learning [1] and
support vector machine algorithms [2] literature.

Data
We adopt this kaggle dataset [3] to train and evaluate our models. It contains transactions made
by credit cards in September 2013 by Europeans. This dataset presents transactions that
occurred in two days, where we have 492 frauds out of 284,807 transactions.
Credit card transactions data

Approach
Our major approach is Q-learning, an algorithm that learns, overtime, to behave optimally in a
certain environment by interacting continuously in the environment. Due to the large space
presented by the number of possible states and actions, we adopt a function approximator,
Recurrent Neural Network (RNN), to try to approximate the Q-values. There are a lot of
implementations of this algorithm in other domains.

Baselines
We compare our model to a basic support vector machines (SVM) model that we will design.
Evaluation
We plan to primarily use the Area Under the Precision-Recall Curve (AUPRC) and F1 score to
measure how good our algorithm is . We anticipate we have to reconcile the cumulative regret used
to evaluate the Q-learning algorithm with SVM classification accuracy.

References
1. Watkins, C. J. C. H. & Dayan, P. Q-Learning, In: Proc. Machine Learning, pp.279-292 (1992)
2. Hearst, Marti A., et al. "Support vector machines." IEEE Intelligent Systems and their
applications 13.4 (1998): 18-28
3. Andrea Dal Pozzolo (2017) Credit card fraud detection Retrieved from Credit card
transactions data
