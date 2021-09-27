# Hybrid Model of Quantum Transfer Learning with ResNet-18 and Basic Entangler Layers to Classify Face Images with a COVID-19 Protective Mask
![NN_BEL](https://user-images.githubusercontent.com/77866708/134839571-c4933f7e-facc-4d45-94bf-f7a26a5ee386.png)
The objective of this paper was to classify images of faces using protective masks of COVID-19, in the classes identified as correct mask, incorrect mask, and no mask, with a Hybrid model of Quantum Transfer Learning. For this purpose, a dataset of 660 people of both sexes (male and female), with ages ranging from 18 to 86 years old. The classic transfer learning model chosen was ResNet-18; the variational layers of the proposed model were built with the Basic Entangler Layers template for four qubits, and the optimization of the training was carried out with the Stochastic Gradient Descent with Nesterov Momentum. A 99.05\% accuracy in the classification was obtained using the Pennylane quantum simulator in the tests carried out.

## Team
- Christian Soto, Universidad Nacional de San Agustín, csotopa@unsa.edu.pe
- Jose Sulla, Universidad Nacional de San Agustín, jsulla@unsa.edu.pe

## Dataset
A dataset of more than 250,000 images of faces using masks is provided, it consists of high-quality images 1024x1024, these images were not edited by computer, so real people are shown as is using masks of 4 different ways.
- Roman Kucev, https://www.kaggle.com/tapakah68/medical-masks-part2/metadata
