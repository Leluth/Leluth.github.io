---
layout: post
topmost: false
title: Pattern Recognition-Face Recognition
categories: MachineLearning MATLAB
description: Pattern Recognition-Face Recognition
keywords: MachineLearning
---

Time: Jan. 2019 - Feb.2019 &emsp; Location: Beijing, China

I finished this project at Chinese Academy of Science where I studied how to conduct face recognition via machine leaning methods.

First, I conducted face detection based on skin color model and used morphological processing method to improve it

![@2x](/images/posts/machinelearning/face-detection.png){:height="50%" width="50%"}

Then I adopted the PCA and EigenFace method to build face recognition system (The accuracy rate on Yale face database reached 77.7 percent).

![@2x](/images/posts/machinelearning/pca1.png){:height="30%" width="30%"}![@2x](/images/posts/machinelearning/pca2.png){:height="30%" width="30%"}

Moreover, I built Fully Connected Feed Forward Neural Network to implement face recognition and used logsoftmaxloss as the loss function which performed better comparing to softmaxloss in the research (The accuracy rate reached 96.67 percent on Yale face database and 95.00 percent on ORL database).

![@2x](/images/posts/machinelearning/FCN1.png){:height="50%" width="50%"}![@2x](/images/posts/machinelearning/FCN2.png){:height="50%" width="50%"}

Finally, I transformed FCN into CNN model and added pooling layer to prevent overfitting (The accuracy rate  reached 96.25 percent on Yale face database and 93.75 percent on ORL database).

![@2x](/images/posts/machinelearning/CNN.png){:height="50%" width="50%"}


