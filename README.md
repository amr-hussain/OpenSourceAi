# A Transfer Learning on ASL-Alphabet

In this repository, I utilized the MobileNet deep neural network (DNN) architecture and pre-trained weights on a new dataset called **ASL-Alphabet**.

## Project Overview

This project applies transfer learning to recognize American Sign Language (ASL) alphabet signs using the MobileNet model. The pre-trained MobileNet model was adapted by replacing its final activation layer with a new **softmax** layer tailored to suit the ASL-Alphabet dataset. The softmax layer allows classification into 29 categories representing different ASL signs.

## Model Adaptation

The following changes were made to the MobileNet architecture:
- The original classification layer of MobileNet was removed.
- A new softmax layer was added to match the ASL-Alphabet dataset.
- The model was then fine-tuned on the new dataset.

## Dataset

The ASL-Alphabet dataset consists of images representing hand signs for each letter in the American Sign Language alphabet. This dataset was used to retrain the modified MobileNet model.

## Trying the model

! the part of manual testing on new images isn't ready yet
