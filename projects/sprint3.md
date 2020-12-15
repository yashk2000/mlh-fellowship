---
title: Sprint 3 Project
layout: page
---

# 🖼️ Sneaky Sketchers

## 🙋 What is Sneaky Sketchers?

Have you ever taken a photo in which there is some unneeded object in the background, ever taken a photo and someone just walked behind you, and now you feel the photo is not as good as it could have been? 📷 

If so, worry not! This desktop application allows you to select the areas in a photo you want to remove by drawing on them. Once you're done, the app will erase the objects you drew on, and generate a new photo which would look as if those obejcts were never present! 🔥

You can also use this application for having some fun. Ever wondered how you would look without a moustache, or with spectacles? Or wondered how your face would like with different features? Well draw over your face, and let the app do the magic! 👦 👧

## 💻 What did we use?
Sneaky Sketchers is built completely in [Python](https://www.python.org/). We have created [Jupyter Notebooks](https://jupyter.org/) on [Google Colab](https://colab.research.google.com/) to train our models and the desktop app is built using [PyQt5](https://pypi.org/project/PyQt5/) 🐍

## 🔨 Installation 

For setting up the desktop app, head over [here](https://github.com/yashk2000/SneakySketchers/tree/main/application).

## 🪜 Folder Struture 

Each folder has it's own dedicated readme on what it's contents do, how to set them up and use them. 

- [`InPainting Notebook`](https://github.com/yashk2000/SneakySketchers/tree/main/InPainting%20Notebook): This folder contains the jupyter notebook we trained on Google Colab. 
- [`application`](https://github.com/yashk2000/SneakySketchers/tree/main/application): This folder contains the main PyQt5 desktop application.  
- [`inpainting`](https://github.com/yashk2000/SneakySketchers/tree/main/inpainting): This folder contains python scripts that can be used for training a model, or making predictions. They can directly be imported into your own project. 

## 🕒 Training Time

The paper which we referred to has trained the model on 3 different datasets, for a period of 14 days. Where as with the resources we had(thanks to Google Colab), we just trained our model on a subset of the Places2 dataset for one night. Based on this limited amount of training, the model does not match the performance given by the original implementation, but it does a pretty good job. In future, should we get the time and resources to train the model completely, we would be able to improve our model a lot.  

## 📚 Resources 

- [https://github.com/MathiasGruber/PConv-Keras](https://github.com/MathiasGruber/PConv-Keras)
- "Image Inpainting for Irregular Holes Using Partial Convolutions", [https://arxiv.org/abs/1804.07723](https://arxiv.org/abs/1804.07723)

### Citation

```
@inproceedings{liu2018partialpadding,
   author    = {Guilin Liu and Kevin J. Shih and Ting-Chun Wang and Fitsum A. Reda and Karan Sapra and Zhiding Yu and Andrew Tao and Bryan Catanzaro},
   title     = {Partial Convolution based Padding},
   booktitle = {arXiv preprint arXiv:1811.11718},   
   year      = {2018},
}
```

```
@inproceedings{liu2018partialinpainting,
   author    = {Guilin Liu and Fitsum A. Reda and Kevin J. Shih and Ting-Chun Wang and Andrew Tao and Bryan Catanzaro},
   title     = {Image Inpainting for Irregular Holes Using Partial Convolutions},
   booktitle = {The European Conference on Computer Vision (ECCV)},   
   year      = {2018},
}
```

## Link to the Project

[https://github.com/yashk2000/SneakySketchers](https://github.com/yashk2000/SneakySketchers)