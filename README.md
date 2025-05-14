# Diabetic Retinopathy Analysis
Diabetic Retinopathy (DR) Analysis refers to the examination and assessment of retinal images to detect, classify, and monitor damage caused by diabetes. This is crucial because early detection can prevent vision loss.
Find more details in health datascience presentation file.

🔬 Project Summary – Diabetic Retinopathy Detection with Deep Learning
This project focuses on the early and accurate diagnosis of Diabetic Retinopathy (DR) by automating the segmentation of pathological retinal features using ultra-wide OCTA scans. We implemented both FCN-ResNet50 and UNet++ architectures to detect:

🧬 Intraretinal Microvascular Abnormalities (IRMA)

🔒 Nonperfusion Zones

🌱 Neovascularization

The training pipeline was built using PyTorch, with custom dataloaders, extensive preprocessing, and GPU optimization. The model achieved:

Dice Score: 82%

IoU: 75%

Training Set: 500+ images

Loss Function: Cross Entropy

Training Time: ~50 epochs

To improve robustness, we introduced data augmentation techniques (random rotation, denoising filters) and memory monitoring tools (GPUtil) to keep the training efficient.

This work aims to support scalable and explainable integration of AI in ophthalmology workflows.
