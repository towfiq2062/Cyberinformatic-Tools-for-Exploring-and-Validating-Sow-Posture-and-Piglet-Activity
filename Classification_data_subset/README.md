# Nursing Behavior Classification Dataset

This repository contains a small dataset of images for training and validating a classification model to detect nursing behavior of sow within farrowing crate. The dataset is organized into two main folders: Train and Val. Each of these folders contains 12 subfolders, corresponding to different classes.

**Folder Structure**

- Train/
  - Lying_Left_Not_Nursing/
    - image1.jpg
    - image2.jpg
    - ...
    - image8.jpg
  - Lying_Left_Nursing/
    - image1.jpg
    - image2.jpg
    - ...
    - image8.jpg
  - Lying_Right_Not_Nursing/
    - image1.jpg
    - image2.jpg
    - ...
    - image8.jpg
  - Lying_Right_Nursing/
    - image1.jpg
    - image2.jpg
    - ...
    - image8.jpg
  - Sitting_Not_Nursing/
    - image1.jpg
    - image2.jpg
    - ...
    - image8.jpg
  - Sitting_Nursing/
    - image1.jpg
    - image2.jpg
    - ...
    - image8.jpg
  - Standing_Not_Nursing/
    - image1.jpg
    - image2.jpg
    - ...
    - image8.jpg
  - Standing_Nursing/
    - image1.jpg
    - image2.jpg
    - ...
    - image8.jpg
  - Sternal_Lying_Partially_Left_Not_Nursing/
    - image1.jpg
    - image2.jpg
    - ...
    - image8.jpg
  - Sternal_Lying_Partially_Left_Nursing/
    - image1.jpg
    - image2.jpg
    - ...
    - image8.jpg
  - Sternal_Lying_Partially_Right_Not_Nursing/
    - image1.jpg
    - image2.jpg
    - ...
    - image8.jpg
  - Sternal_Lying_Partially_Right_Nursing/
    - image1.jpg
    - image2.jpg
    - ...
    - image8.jpg

- Val/
  - Lying_Left_Not_Nursing/
    - image1.jpg
    - image2.jpg
  - Lying_Left_Nursing/
    - image1.jpg
    - image2.jpg
  - Lying_Right_Not_Nursing/
    - image1.jpg
    - image2.jpg
  - Lying_Right_Nursing/
    - image1.jpg
    - image2.jpg
  - Sitting_Not_Nursing/
    - image1.jpg
    - image2.jpg
  - Sitting_Nursing/
    - image1.jpg
    - image2.jpg
  - Standing_Not_Nursing/
    - image1.jpg
    - image2.jpg
  - Standing_Nursing/
    - image1.jpg
    - image2.jpg
  - Sternal_Lying_Partially_Left_Not_Nursing/
    - image1.jpg
    - image2.jpg
  - Sternal_Lying_Partially_Left_Nursing/
    - image1.jpg
    - image2.jpg
  - Sternal_Lying_Partially_Right_Not_Nursing/
    - image1.jpg
    - image2.jpg
  - Sternal_Lying_Partially_Right_Nursing/
    - image1.jpg
    - image2.jpg

- Test_Images/
    - image1.jpg
    - image2.jpg
    - image3.jpg
    - image4.jpg

**Note:** To effectively train the classification model, only the `Train` and `Val` folders are necessary. The `Test_Images` folder comprises four new images intended to evaluate the model's performance and its capability to detect previously unseen images.

To facilitate the training of the classification model using this dataset, you may utilize the [Sow_Nursing_Behavior_Classification.ipynb](Sow_Nursing_Behavior_Classification.ipynb) Google Colab notebook.

As an alternative, a code-free approach to training a classification model for learning purpose is available through [this website](https://tm.gen-ai.fi/image/general). On this platform, you can simply upload your images and train the model. Upon entering the website, you will find options to add image samples under Class 1 and Class 2. You may add the names of the `Train` and `Val` folders and images respectively. Furthermore, the interface allows you to add more classes by clicking on the "Add a class" button. Additionally, you can assess the model's performance using the images from the `Test_Images` folder.

The interface of the website includes the following sections:
- **Training Data**: Here, you can add image samples for each class by either uploading from your device or using a webcam. 
- **Class 1 and Class 2**: These are the default classes where you can add your training and validation images. More classes can be added by using "Add a class" option just below the Class 1 and Class 2.
- **Training**: After adding sufficient samples, you can train your classifier.
- **Input**: Options to test the model using images from your device, webcam, or other sources.
- **Classifier**: You must train your classifier before it can be used to make predictions.

This user-friendly interface simplifies the process of creating and training a classification model without needing to write any code.



