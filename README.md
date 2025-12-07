
# Understanding CNN Feature Extraction: Visualising Filters and Feature Maps on MNIST

This repository contains the code, tutorial PDF, and supporting materials for the assignment:
**“Understanding CNN Feature Extraction: Visualising Filters and Feature Maps on MNIST”.**

The project demonstrates how Convolutional Neural Networks (CNNs) learn hierarchical visual features by **visualising filters, feature maps, and training behaviour** using PyTorch.

---

## 📂 Repository Structure
\`\`\`
├── notebook.ipynb                # Complete Jupyter notebook with code & visualisations
├── CNN_Feature_Extraction_Tutorial.pdf   # Final tutorial (PDF version)
├── images/                       # Auto-generated images from the notebook
│   ├── conv1_filters.png
│   ├── featuremaps_conv1.png
│   ├── featuremaps_conv2.png
│   ├── orig_and_conv1_grid.png
│   ├── training_loss.png
│   └── training_accuracy.png
├── README.md                     # Project documentation
├── LICENSE                       # Open-source license (MIT recommended)
\`\`\`

---

## 📘 Project Description

This project provides an educational walkthrough of:
- How CNNs extract features from images  
- What convolutional filters learn  
- How feature maps evolve across layers  
- How training affects model performance  

Using the **MNIST dataset**, we train a small CNN in PyTorch, then visualise:
- Learned filters (Conv1)
- Feature maps from Conv1 and Conv2
- Combined grids showing how the input transforms through the network
- Training loss and accuracy curves

The goal is to make CNN internals **interpretable** and **visually intuitive**, supporting effective teaching and learning.

---

## 🧠 Key Learning Objectives
- Understand convolutional filters  
- Observe hierarchical feature extraction  
- Learn how hooks capture activations  
- Explore practical interpretability techniques  
- Implement a full training pipeline in PyTorch  

---

## 🛠️ Technologies Used
- Python 3  
- PyTorch  
- Matplotlib  
- Torchvision  
- NumPy  

---

## 📊 Dataset
MNIST is downloaded automatically using torchvision.  
It contains:
- 60,000 training images  
- 10,000 test images  
- 28x28 grayscale handwritten digits  

---

## 🚀 How to Run the Notebook

1. Install dependencies:
   \`\`\`
   pip install torch torchvision matplotlib
   \`\`\`
2. Open the notebook:
   \`\`\`
   jupyter notebook notebook.ipynb
   \`\`\`
3. Run all cells.  
All visualisation images will be saved automatically in the `images/` folder.

---

## 📄 Tutorial PDF
The full tutorial is available in the repository:

📎 **CNN_Feature_Extraction_Tutorial.pdf**

---

## 📚 References
Key references used:
- LeCun et al. (1998)  
- Goodfellow, Bengio & Courville (2016)  
- PyTorch Documentation  
- MNIST Dataset Website  

Full references included in the PDF.

---

## ⚖️ License
This project is released under the **MIT License**.
