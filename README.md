# Classification of brain tumor in MRI image using deep learning

## What is brain tumor?
A brain tumor is an abnormal growth or mass of cells that can develop in the brain. These tumors can be benign (noncancerous) or malignant (cancerous) and originate from different types of brain cells. They can cause a range of symptoms depending on their size, location, and rate of growth, potentially affecting brain function and quality of life. 

## The significance of this project
Early detection of brain tumors may increase the chances of successful treatment and can help doctors to reading MRI images more efficiently.

## Dataset
This dataset contains 7023 images of human brain MRI images which are classified into 4 classes: glioma - meningioma - no tumor and pituitary. Dataset is organized into 2 folders (train ,test) and both train and test contain 4 subfolders. In train folder contains 5712 images. In test folder contains 1311 images.

## Method
To classify brain tumors using MRI images, begin by collecting a labeled dataset of brain tumor images from Kaggle. Preprocess the images by resizing them to a consistent resolution and normalizing the pixel values. Split the dataset into separate training and testing sets to assess the model's performance accurately. For this project, I used the VGG16 model for pre-trained convolutional neural network (CNN) model. Monitor the training process using metrics such as loss and accuracy to ensure effective model training. After training, evaluate the model's performance on the testing set using the confusion matrix. To enhance user interaction, consider creating a user-friendly interface using Gradio. Finally, the trained model can used to classify new brain tumor images by passing them through the model and obtaining predicted probabilities for each tumor type.

## Result
In this project have accuracy for test set = 0.9657, Recall for test set = 0.9629, loss on test set = 0.1160, F1 on test set = 0.9633, percision on test set = 0.9642 and IOU on test set = 0.9653



This project is partial fulfillment for the course Medical Signal processing and instrumentation (EGBE 601)
