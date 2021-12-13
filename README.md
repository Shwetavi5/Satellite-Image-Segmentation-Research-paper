# Satellite-Image-Segmentation-Research-paper

### Objective

The main goal or objective of this project is to classify the objects in the satellite images by generating the masks for those objects. As shown in Figure 2, we are segmenting and assigning different colors to each class in the satellite image (Buildings, Roads, Trees, Crops, and so on) (Nowaczynski, 2021). Our model should be able to segment both binary and multiclass satellite images. The number of mask categories is the same as the number of objects detected in the given model. A simple binary classifier would classify only two classes of objects. The training datasets will consist of images and labels. The labels are nothing but images with only the masks for the objects that need to be recognized. All other objects that do not need to be recognized will fall into a single category of the mask (background mask or class).

Solving the Satellite Image Segmentation problem using semantic segmentation technique where satellite images are segmented by classifying each pixel of the object. To do this 6

process, the project uses some of the state-of-the-art deep learning models like Fully Convolutional Networks (FCN), U-NET, and LinkNet.

**Figure 2** 
 Images illustrate what satellite image segmentation looks like after building a model.
# ![image](https://user-images.githubusercontent.com/89550139/145770394-10789009-e4c9-4a0b-8c53-807f82fca64f.png)


Note. Image shows before and after segmentation results of satellite images. Adapted from Cookie and Privacy Settings. Deepsense.Ai by Nowaczynski, A. (2021). (https://deepsense.ai/deep-learning-for-satellite-imagery-via-image-segmentation). Copyright 2021 by Deepsenseby.AI
