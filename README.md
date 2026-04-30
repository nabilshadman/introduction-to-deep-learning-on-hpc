# Introduction to Deep Learning (on HPC)
> A comprehensive introduction to deep learning — from neural network fundamentals to advanced architectures including CNNs, RNNs, Transformers, and multi-GPU training.

[![Course](https://img.shields.io/badge/Course-Nov%202025-blue)](https://events.asc.ac.at/event/207/)
[![Level](https://img.shields.io/badge/Level-Beginner%20Friendly-green)]()
[![License](https://img.shields.io/badge/License-CC%20BY--SA%204.0-orange)](https://creativecommons.org/licenses/by-sa/4.0/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-FF6F00?logo=tensorflow)]()

Comprehensive course materials from the **Introduction to Deep Learning** training by AI:AT – AI Factory Austria and ASC – Austrian Scientific Computing. This repository contains lecture slides and hands-on Jupyter notebooks covering fundamental and advanced deep learning concepts.

## 📚 Course Overview

A two-day intensive course covering neural network fundamentals through advanced architectures including CNNs, RNNs, LSTMs, and Transformers. The course emphasizes practical implementation using TensorFlow and includes multi-GPU training techniques.

**Instructor:** Simeon Harrison (AI:AT – AI Factory Austria)  
**Prerequisites:** Basic Python programming and Linux command line skills  
**Level:** Beginner-friendly (no prior deep learning knowledge required)

## 📂 Repository Structure

```
├── lecture_slides/
│   ├── 01_ANNs.pdf                              # Artificial Neural Networks
│   ├── 02_CNNs.pdf                              # Convolutional Neural Networks
│   ├── 03_Recurrent_Neural_Networks.pdf         # RNNs and LSTMs
│   └── 04_Transformers.pdf                      # Transformer Architecture
│
└── notebooks/
    ├── 01_Welcome.ipynb
    ├── 02_Introduction_to_Tensorflow.ipynb
    ├── 03_Introduction_to_Tensorflow_exercises.ipynb
    ├── 04_NN_regression_in_tensorflow.ipynb
    ├── 05_NN_regression_in_tensorflow_exercise.ipynb
    ├── 06_Regression_larger_example.ipynb
    ├── 07_Preprocessing_evaluation.ipynb
    ├── 08_NN_classification_in_tensorflow.ipynb
    ├── 09_Image_classification.ipynb
    ├── 10_Image_classification_exercise.ipynb
    ├── 11_Image_classification_solution.ipynb
    ├── 12_CNN.ipynb
    ├── 13_CNN_exercise.ipynb
    ├── 14_Transfer_learning.ipynb
    ├── 15_RNNs.ipynb
    ├── 16_RNN_exercise.ipynb
    ├── 17_multi_GPU_horovod.ipynb
    └── 18_TF_distributed.ipynb
```

## 🎯 Topics Covered

### Day 1: Foundations
- **Neural Network Fundamentals**
  - Weights, biases, and activation functions
  - Loss functions and optimizers
  - Backpropagation and gradient descent
- **TensorFlow Implementation**
  - Regression and classification tasks
  - Data preparation and preprocessing
  - Metrics and model evaluation
- **Convolutional Neural Networks (CNNs)**
  - Convolution operations and feature extraction
  - Pooling layers and architectures
  - Computer vision applications (VGGNet)

### Day 2: Advanced Architectures
- **Transfer Learning**
  - Leveraging pretrained models
  - Fine-tuning strategies
- **Recurrent Neural Networks (RNNs)**
  - Sequence processing and temporal data
  - Long Short-Term Memory (LSTM) networks
  - Applications in text and speech
- **Transformers**
  - Attention mechanisms
  - Encoder-decoder architecture
  - Large Language Models (LLMs)
- **Distributed Training**
  - Multi-GPU training with Horovod
  - TensorFlow distributed strategies

## 🚀 Getting Started

### Prerequisites

```bash
# Core requirements
python >= 3.8
tensorflow >= 2.x
jupyter notebook
numpy
pandas
matplotlib
```

### Installation

```bash
# Clone the repository
git clone https://github.com/nabilshadman/introduction-to-deep-learning.git
cd introduction-to-deep-learning

# Install dependencies
pip install tensorflow jupyter numpy pandas matplotlib scikit-learn

# Launch Jupyter Notebook
jupyter notebook
```

### Running the Notebooks

1. Navigate to the `notebooks/` directory
2. Start with `01_Welcome.ipynb` for course introduction
3. Follow the numbered sequence for a structured learning path
4. Complete exercises before viewing solutions

## 📖 Learning Path

**Beginners:** Follow notebooks 01-11 for foundational concepts
- Introduction to TensorFlow
- Regression and classification basics
- Image classification fundamentals

**Intermediate:** Continue with notebooks 12-16 for advanced architectures
- CNN implementation and design
- Transfer learning techniques
- RNN and LSTM applications

**Advanced:** Explore notebooks 17-18 for distributed training
- Multi-GPU parallelization
- Production-scale model training

## 🔬 Hands-On Exercises

The repository includes several exercise notebooks with corresponding solutions:

- **TensorFlow Basics** (Notebook 03)
- **Neural Network Regression** (Notebook 05)
- **Image Classification** (Notebooks 10-11)
- **CNN Architecture** (Notebook 13)
- **RNN Implementation** (Notebook 16)

## 🛠️ Hardware Requirements

Original course delivered on ASC systems with GPU access (A100/A40). For local execution:
- **Minimum:** CPU with 8GB RAM
- **Recommended:** NVIDIA GPU with CUDA support for faster training

## 📝 License

This course material is licensed under **CC BY-SA 4.0** (Attribution-ShareAlike).

Original materials developed by Simeon Harrison for AI:AT – AI Factory Austria and ASC – Austrian Scientific Computing (development started in 2023 within EuroCC Austria).

## 🔗 Additional Resources

- **Original Course Repository:** [GitLab - TU Wien](https://gitlab.tuwien.ac.at/vsc-public/training/introduction-to-deep-learning)
- **Course Information:** [EuroCC Austria Training Portal](https://events.asc.ac.at/event/207/)
- **TensorFlow Documentation:** [tensorflow.org](https://www.tensorflow.org/)

## 📧 Contact

For questions, contributions, or error reporting regarding the original course materials:
- Email: training@asc.ac.at

For issues with this repository:
- Open an issue on GitHub

## 🙏 Acknowledgments

This course received funding from the European High-Performance Computing Joint Undertaking (JU) under grant agreement No 101101903 and No 101253078. The JU receives support from the Horizon Europe Programme and participating member states.

**Organizations:**
- AI:AT – AI Factory Austria
- ASC – Austrian Scientific Computing (TU Wien)
- EuroCC Austria

## 📖 Citation

If you use these materials in your work, please cite:

```bibtex
@course{intro_deep_learning2025,
  title        = {Introduction to Deep Learning},
  author       = {Harrison, Simeon},
  organization = {AI:AT -- AI Factory Austria and ASC Research Center, TU Wien},
  year         = {2025},
  month        = {November},
  url          = {https://events.asc.ac.at/event/207/},
  note         = {Course materials originally developed within EuroCC Austria (2023)}
}
```

---

⭐ **Star this repository** if you find these materials helpful for your deep learning journey!
