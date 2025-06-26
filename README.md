NEURAL STYLE TRANSFER – TASK 2 REPORT
Company: CODTECH IT SOLUTIONS
Intern Name: GOPA SAI KRISHNA
Intern ID: CT04DF217
Domain: Artificial Intelligence
Duration: 4 Weeks
Mentor: Neela Santosh
Description:
As part of my internship at CODTECH IT SOLUTIONS, I undertook the development of a Neural Style Transfer application using Deep Learning techniques in the field of Computer Vision. The goal was to implement a Python-based program that could apply the artistic style of one image (such as a famous painting) onto the content of another image (typically a photograph), thereby creating a visually compelling blend of art and photography.Neural Style Transfer (NST) uses convolutional neural networks (CNNs) to separate and recombine the content and style of images. This technique has gained popularity in digital art, advertising, and design, enabling artists and developers to create AI-generated art with minimal effort.Technologies Used
Programming Language: Python
Libraries & Tools: PyTorch, Torchvision, Matplotlib, PIL
Pretrained Model: VGG19 (from torchvision.models)
Editor/IDE: Visual Studio Code (VS Code)
Development OverviewIn this project, I used the VGG19 network, pre-trained on the ImageNet dataset, to extract features from the content and style images. The core idea was to compute content loss and style loss, then iteratively update a target image to minimize these losses using gradient descent.Basic Workflow:Load content and style images.Preprocess and convert them into tensors.Extract features using VGG19.Define content and style loss.
OUTPUT:
![WhatsApp Image 2025-06-21 at 12 20 26_fd506338](https://github.com/user-attachments/assets/bd715f47-c655-4c91-9d54-c07724ae84db)
