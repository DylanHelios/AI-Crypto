# Artificial Intelligence

## Loss 

## TQDM 

TQDM is a librairy that show a progression bar 

## PyTorch 

PyTorch is an open source librairy for DeepLearning developed by Meta. 
It is used to create, train, and test neural networks for tasks such as :

- **Computer Vision** (images, videos)
- **Natural Language Processing - NLP** (text, translation)
- **Reinforcement learning - RL**

## Computer Vision

### Torchvision

**Torchvision** is a **PyTorch** library designed for computer vision projets : 

It provides : 

- **Dataset** already made 
- Efficient data preprocessing :  
→ **Normalization**, **cropping**, **resizing**, **rotations** and more.
- Leverage pretrained models  
→ **ResNet**, **VGG**, **MobileNet**, **ViT**  
→ These ImageNet-trained models can be used directly or fine-tuned for new tasks (**Transfer Learning**).
- Manipulate images and videos  
→ Loading, saving, transformations
- Advanced tools for **detection** & **segmentation**.  
→ **NMS** (Non-Maximum Suppression), **Rol Align**, and more.

### Algorithme 

#### NMS (Non-Maximum Suppression)

When a dectection model an object, it generates bounding boxes overlapping around the same object. **NMS** keeps only the best bounding box (the one with the highest probability) and removes the others. 

#### RoI Align (Region of Interest Align)

**RoI Align** is used in **dectection** and **segmentation models**. It is designed to extract a small region of the image corresponding to a detected object. Unlike simple cropping, **RoI Align** avoids precision loss by correctly handling fractional pixel coordinates.
