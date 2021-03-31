# Blossom

Blossom is a model trained to identify the flower from the image. Currently, the model is using the transfer learning method to achieve a better result. The dataset used for this model is flower photos from TensorFlow.

To run the model, you can open it from `Main.ipynb` then click the button `Open in Colab`. 

## Step by Step Process
1. Data Preprocessing
   
   Preprocessing consists of downloading data, dataset slicing, dataset configuration for performance, and data augmentation.

2. Creating Base Model from Pre-Trained Model

   The base model for this model is using MobileNetV2.
 
3. Feature Extraction

   To extract all features from the base model, we need to do freezing, combine it with a defined layer, model compiling, and model training orderly.

4. Fine Tuning

   As you get the accuracy and loss result from the previous step, you may need to make some adjustments to the model to improve the performance by unfreezing, compile, and continue the model training. 

5. Predicting Result

   The model has been tested to predict the image from the test dataset and user input.

> You can check the result from `Main.ipynb`