# Neural Networks & Learning

This repository hosts the mathematical modeling, simulation and visualization; training paradigms, and data processing pipelines spanning from traditional Artificial Neural Networks (ANNs) to advanced Spiking Neural Networks (SNNs). It is organized into the following core areas:

* **Neural Architectures & Dynamics:** Julia and Python implementations of both continuous ANN models and discrete SNN architectures. This includes mathematical derivations and reset mechanisms for advanced neuromorphic models, such as HyperLIF and Adaptive HyperLIF, to address dynamic stability.
* **Datasets & Data Loaders:** Custom processing pipelines designed for both standard and event-based high-dimensional datasets. Includes robust loaders for standard computer vision benchmarks (MNIST) as well as neuromorphic equivalents (N-MNIST, DVS128 Gesture).
* **High-Performance Computing (HPC):** Batch submission scripts and optimized training pipelines designed to train these networks at scale and replicate paper results efficiently within cluster environments.
