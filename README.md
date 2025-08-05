# 🧠 Custom Neural Network Module with PyTorch

This repository presents a modular and reusable Neural Network (NN) implementation built using PyTorch, applied on the Breast Cancer dataset for demonstration purposes. The core objective of this project is to design and structure a customizable NN module, decoupled from dataset-specific logic, suitable for adaptation across different machine learning tasks.

---

## 🔧 Focus: Neural Network Architecture

The heart of this project is a flexible neural network module with the following design principles:

- *Modularity*: Easy to plug and play different layer configurations.
- *Parameterization*: Supports dynamic definition of input size, hidden layers, output size, and activation functions.
- *Reusability*: Abstracted away from specific datasets for portability.
- *Clean Structure*: Organized to separate model logic from training and data handling.

📚 Dataset Context

While the Breast Cancer Wisconsin dataset is used here, the architecture is dataset-agnostic. The dataset serves solely as a use case to validate the model structure and performance.


---

✨ Key Components

nn_model.py: Contains the CustomNN class defining the neural network module.

train.py: Basic training loop to validate model performance.

dataset_loader.py: Minimal loader for the breast cancer dataset (can be swapped easily).

utils.py: Utility functions for training (e.g., accuracy computation, seed setting).

🎯 Project Intent

This repository is designed for those interested in:

Building neural networks without relying on high-level APIs

Understanding PyTorch module design patterns

Creating reusable model components for experimentation and deployment



---

🧩 Extensibility

The current implementation can be extended to include:

Custom weight initializations

Dropout or batch normalization layers

Support for regression tasks

Model checkpointing and evaluation metrics
