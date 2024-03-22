# Image-Classification-for-local-categories

This code is designed to classify images into five distinct categories: bags, fashion, nutrition, calendar and planning, and card and board games. It employs pre-trained models like VGG16 and MobileNet for feature extraction and classification. Additionally, it addresses class imbalances using appropriate techniques.

# Code Structure
The code is divided into several sections, each serving a specific purpose:

# 1. Data Preprocessing and Splitting:

The script begins by organizing the data into training and validation sets, following an 80-20 split ratio.
It shuffles and moves images into corresponding directories for training and validation.
# 2.VGG16 Model:

Utilizes the pre-trained VGG16 model for feature extraction.
Implements data augmentation to enhance model generalization.
Sets up data generators for both training and validation sets.
Computes class weights to address class imbalances.
Defines a new model architecture, adding layers for classification.
Compiles and trains the model using the specified parameters.
# 3.MobileNet Model:

Similar to the VGG16 section, but employs the MobileNet architecture instead.
Performs data augmentation, sets up data generators, computes class weights, defines model architecture, compiles, and trains.
Instructions for Use
Data Preparation:

Organize your image data into directories according to class labels under the Data-slash directory.
Python Environment:

Ensure you have Python installed along with necessary libraries such as TensorFlow, scikit-learn, and others mentioned in the code.
Code Execution:

Run the provided Python script in your preferred development environment or terminal.
Model Training:

The script will train both VGG16 and MobileNet models sequentially.
Adjust the number of epochs and other hyperparameters as needed.
Model Evaluation and Saving:

After training, the models will be evaluated on the validation set.
Trained models will be saved with appropriate filenames (commented lines need to be uncommented to save the models).
Notes
Ensure your directory structure matches the expected structure as mentioned in the code comments.
Customize the code according to your specific dataset and requirements, such as adjusting model parameters, number of classes, or directory paths.
By following these instructions, you can effectively utilize the provided code for image classification tasks across multiple classes.

## Author: [Ehab Essam]

## Date: [3/22/2024]




