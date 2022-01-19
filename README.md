# Bachelor's Degree in Physics

This work presents the implementation of the track membrane evaluation approach using images made by electron-beam microscopy. The proposed method consists of two stages: using a machine learning model (convolutional neural network) to obtain binary image masks, in which white areas stand for the pores of the membrane, and black areas stand for the background. Subsequent processing of the obtained masks using classical computer vision algorithms implemented in the OpenCV library allows calculating the desired characteristics of the track membrane surface. Examples of such characteristics are porosity, pore density, or several pores. The use of binary masks obtained by image segmentation makes it possible to significantly simplify the algorithmic approach to calculating these characteristics. 

The work also provides a comparative analysis of the masks’ quality restored by the model, depending on the number of training epochs, the loss function, and the model architecture itself. Based on the results of this comparison, the best configuration was selected for further use. The masks obtained using the best configuration were later used to calculate the characteristics of the membrane. For the best configuration, learning curves and metrics values depending on the epoch was also obtained. The manual calculation of the track membrane characteristics is compared with the approach that uses a trained model. From this comparison, the limitations of using the proposed method were revealed.

In [code.ipynb](https://github.com/nikuznetsov/diploma/blob/main/code.ipynb "code.ipynb") it is possible to find all working code of the work.

In [dataset_segm.zip](https://github.com/nikuznetsov/diploma/blob/main/dataset_segm.zip "dataset_segm.zip") it is possible to find required dataset.

In [slides.pdf](https://github.com/nikuznetsov/diploma/blob/main/slides.pdf "slides.pdf") it is possible to find slides from the thesis defence.

In [text.pdf](https://github.com/nikuznetsov/diploma/blob/main/text.pdf "text.pdf") it is possible to find text of the whole work.

## **Published materials:**
1. Report thesis. 2nd conference on condensed matter physics, Chernogolovka. DOI: 10.26201/ISSP.2020/FKS-2.351
