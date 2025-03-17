# Image-Classification-with-ResNeXt-on-CIFAR-10
This project implements a modified ResNeXt architecture for image classification on the CIFAR-10 dataset. It explores residual blocks, grouped convolutions, and compares optimization techniques like Stochastic Gradient Descent (SGD) and Adversarial Model Perturbation. The aim is to achieve high accuracy while keeping computational complexity low.

README.md
markdown
Copy
Edit
# Image Classification with ResNeXt on CIFAR-10

## 📌 Project Overview
This project explores the **ResNeXt** architecture for image classification on the **CIFAR-10** dataset. It compares **Stochastic Gradient Descent (SGD)** and **Adversarial Model Perturbation (AMP)** optimization techniques to improve accuracy while maintaining computational efficiency. The goal is to optimize deep learning models for better generalization and robustness.

## 🔍 Key Features
- **ResNeXt Architecture**: A variant of ResNet with grouped convolutions for better performance.
- **Comparison of Optimizers**: Evaluates **SGD** vs. **AMP** to determine the best model performance.
- **Data Augmentation**: Includes transformations like cropping, flipping, and normalization.
- **Training & Evaluation**: Implements deep learning techniques to classify images efficiently.

## 📂 Project Structure
Deep-Learning-Mini-Project/ │── amp.py # AMP optimizer implementation │── resnext_amp.ipynb # Training ResNeXt using AMP │── resnext_sgd.ipynb # Training ResNeXt using SGD │── summary.ipynb # Model evaluation and results │── loss_accuracy_plot.png # Graph comparing loss and accuracy │── training_sgd.png # Training results using SGD │── testing_sgd.png # Testing results using SGD │── ckpt_sgd.pth # Trained model checkpoint │── README.md # Project documentation │── Mini Project_Report.pdf # Detailed project report

bash
Copy
Edit

## 🛠 Installation & Setup
1. **Clone the Repository**
   ```bash
   git clone https://github.com/dstirumalasetty/Deep-Learning-Mini-Project.git
   cd Deep-Learning-Mini-Project
Install Dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the Notebook Open and run the resnext_amp.ipynb or resnext_sgd.ipynb Jupyter Notebook for training.

📊 Results
AMP Optimizer: Achieved 90-91% accuracy with improved robustness.
SGD Optimizer: Achieved 89-90% accuracy but with slightly lower generalization.
Loss & Accuracy Plots: Available in the repository (loss_accuracy_plot.png).

🔗 References
ResNeXt Paper
CIFAR-10 Dataset

📢 Contributors
Divya Sai Tirumalasetty
Pranav Doma
Prathyusha Kadali
