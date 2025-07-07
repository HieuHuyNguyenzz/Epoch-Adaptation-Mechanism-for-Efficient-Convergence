# Epoch-Adaptation-Mechanism-for-Efficient-Convergence
**Abstract** - Federated Learning (FL) is well-suited for the In-
ternet of Things and Cloud Computing due to its ability to
preserve data privacy, handle large-scale deployments, work
with resource-constrained devices, and integrate with edge com-
puting architectures. However, practical FL often encounters
heterogeneity problems that stem from the different nature of
device resources and user usage patterns. These issues can slow
down model convergence, requiring the model to undergo more
communication rounds to reach final convergence and causing
the training time of a communication round to be prolonged.
In this paper, we propose a new Epoch Adaptation Mechanism
for Efficient Convergence framework for the FL mechanism to
address these heterogeneities. By calculating a suitable number
of local epochs for each client based on its computation and
communication time in a training round, our method can mitigate
the waiting time caused by system heterogeneity by increasing the
number of epochs in faster clients. This strategy helps accelerate
model convergence without extending the training time in each
round. In addition, a double-sided mechanism is applied to our
framework to prevent the possibility of overfitting during the
training stage. Experimental results show that our framework
can boost the convergence of the global model in statistical
heterogeneity by up to 80% in EMNIST dataset and 35% in
CIFAR-10 dataset.

Published at 2025 IEEE Information Reuse and Integration for Data Science
