# PyTorch Learning Journey 🚀

<p align="center">
  <img src="https://github.com" alt="PyTorch Code Validation Status" />
</p>

Welcome to my repository dedicated to mastering **PyTorch** and **Deep Learning** from scratch! This space serves as a central hub for all my code implementations, hands-on exercises, notebook practices, and core concepts as I progress through the world of Artificial Intelligence.

## 📌 Roadmap & Topics Covered
- [x] **Day 1: Introduction to Tensors**
  - Understanding PyTorch Tensors (`torch.tensor`)
  - Tensor initializations, shapes, and data types
  - Basic operations and manipulation
- [x] **Day 2: Autograd & Computation Graphs**
  - Understanding PyTorch Autograd for gradient calculation
  - Dynamic computation graphs and `requires_grad=True`
  - Backpropagation fundamentals using `.backward()`
- [x] **Day 3: Simple Neural Network (Breast Cancer Classification)**
  - Implemented an end-to-end binary classification training workflow
  - Experimented with manual workflow layers and architectural elements
  - Optimized hyperparameters, boosting validation accuracy from **53.69% to 97.37%** 🔥
- [x] **Day 4: nn.Module & torch.optim (Building Blocks)**
  - Constructing custom layers and model topologies using `torch.nn.Module`
  - Configuring state-of-the-art optimization routines via `torch.optim` (SGD, Adam)
  - Integrating automated weight updates and explicit gradient resetting (`optimizer.zero_grad()`)
- [x] **Day 5: Data Pipeline & Datasets (Dataset & DataLoader)**
  - Utilizing `torch.utils.data.Dataset` for structured custom data parsing
  - Implementing `torch.utils.data.DataLoader` for streamlined mini-batch generation
  - Managing shuffling, data batching pipelines, and multi-process data loading execution
- [x] **Day 6: ANN / MLP on Fashion MNIST Dataset**
  - Designing an Artificial Neural Network / Multilayer Perceptron (MLP) structure for multi-class image handling
  - Processing pixel matrix dimensional inputs using flattening components (`nn.Flatten`)
  - Tracking multi-class loss trends utilizing Cross-Entropy loss functions and dynamic hidden layer activations
- [x] **Day 7: Optimizing Neural Networks**
  - Implementing network regularization strategies to combat overfitting configurations
  - Applying Dropout layers (`nn.Dropout`) and structural normalization techniques
  - Experimenting with advanced hyperparameter tuning and optimization scheduler logic
- [x] **Day 8: Hyperparameter Tuning via Optuna Trials**
  - Defining dynamic objective functions for autonomous neural network parameter evaluations
  - Implementing Optuna study trials to automate optimal learning rates and layered nodes selection
  - Maximizing evaluation accuracy using automated trial tracking and optimization architectures
- [x] **Day 9: CNN Architecture (Convolutional Neural Networks)**
  - Understanding structural spatial filtering using 2D Convolution layers (`nn.Conv2d`)
  - Implementing Max-Pooling modules (`nn.MaxPool2d`) to scale down feature dimensions
  - Constructing end-to-end computer vision feature extractors integrated with dense classifiers
- [x] **Day 10: RNN Architecture (Recurrent Neural Networks)**
  - Understanding sequential input tracking and recurrent cell mechanics using `nn.RNN`
  - Mapping Recurrent Forward Propagation mathematical matrices and hidden states (\(h_t\)) tracking
  - Processing sequence predictions, input token matching, and targeted hidden output generations
- [ ] **Computer Vision (Advanced CNNs) & NLP (RNNs/Transformers)**
- [ ] **Model Deployment & Evaluation**

## 💻 Tech Stack & Tools
- **Language:** Python 🐍
- **Framework:** PyTorch 🔥
- **Environment:** Google Colab / Jupyter Notebooks
- **Libraries:** NumPy, Pandas, Matplotlib, Seaborn

## 🛠️ Project Structure
```text
├── .github/workflows/
│   └── code_validation.yml                             # Automated CI/CD execution script for pipeline quality
├── 01_Tensors_in_pytorch.ipynb                         # Comprehensive guide to Tensor fundamentals
├── 02_PyTorch_Autograd.ipynb                           # Code and concepts regarding Autograd & Backpropagation
├── 03_Neural_Network_Breast_Cancer_Classification.ipynb # End-to-end binary classification (97.37% Accuracy 🎯)
├── 04_Building_Blocks_of_Neural_Networks.ipynb         # Structural deep dive into nn.Module & torch.optim
├── 05_PyTorch_Data_Pipelines_and_Datasets.ipynb        # Custom dataset creation and mini-batch loading
├── 06_FashionMNIST_Classification_MLP.ipynb            # Image classification using MLP and cross-entropy loss
├── 07_Optimizing_Neural_Networks.ipynb                 # Regularization, Dropout, and network tuning executions
├── 08_Automated_Hyperparameter_Tuning_Using_Optuna.ipynb # Automated hyperparameter optimization trials
├── 09_Convolutional_Neural_Networks_CNN.ipynb            # Spatial feature extraction and CNN layer structural design
├── 10_Recurrent_Neural_Networks_RNN_Architecture.ipynb   # Sequential modeling, forward tracking, and hidden states 🎯
└── README.md                                           # Repository documentation
```

## 🎯 Career Goals
My objective is to build a robust foundation in machine learning theory and mathematical concepts (Linear Algebra, Calculus, Statistics) to transition effectively into full data systems, Advanced NLP, and becoming a **Lead AI Engineer / Researcher**.

---
*Feel free to explore the notebooks and star ⭐ this repository if you find it helpful!*
