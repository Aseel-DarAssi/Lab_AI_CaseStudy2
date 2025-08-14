# Case Study #2 – Experimenting with Transfer Learning

**Course:** Intelligent Systems Lab (ENCS5141)  
**Department:** Electrical and Computer Engineering – Summer 2025  

## case study Overview
In this case study, we apply **transfer learning** using two popular architectures: **AlexNet** and **VGG16** to classify images from the **CIFAR-10** dataset.  
The models start with **ImageNet pre-trained weights** and are trained on CIFAR-10 for **3 epochs** with a **batch size of 32**.

Two training setups are compared:
1. **Fine-Tuning** – All pre-trained weights are updated, along with the newly added classification layer.
2. **Fixed Feature Extractor** – All pre-trained convolutional layers are frozen, and only the final fully connected layer (with random initialization) is trained.


