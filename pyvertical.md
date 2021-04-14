## PyVertical: A Vertical Federated Learning Framework for Multi-headed SplitNN

**Abstract:** We introduce PyVertical, a framework supporting vertical federated learning using split neural networks. The proposed framework allows a data scientist to train neural networks on data features vertically partitioned across multiple owners while keeping raw data on an owner's device. To link entities shared across different datasets' partitions, we use Private Set Intersection on IDs associated with data points. To demonstrate the validity of the proposed framework, we present the training of a simple dual-headed split neural network for a MNIST classification task, with data samples vertically distributed across two data owners and a data scientist.


<picture>
    <source type="images/webp" srcset="/images/PyVertical_architecture.webp" />
    <source type="images/png" srcset="/images/PyVertical_architecture.png" />
    <img class="z-depth-1" src="/images/PyVertical_architecture.png" alt="PyVertical: A Vertical Federated Learning Framework for Multi-headed SplitNN">
</picture>

<br>

---


ICLR 2021 Workshop on Distributed and Private Machine Learning (DPML 2021); https://dp-ml.github.io/2021-workshop-ICLR/

For more details: [PyVertical: A Vertical Federated Learning Framework for Multi-headed SplitNN](https://arxiv.org/abs/2104.00489).
