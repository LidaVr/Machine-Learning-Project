# Machine Learning and Content Analytics Project
Msc. Business Analytics, AUEB, 2022-2023

Professor: Haris Papageorgiou

Assistant Professor: George Perakis

Team Members:
- Kalamara Katerina, p2822211
- Konstantinos Velissaris, p2822204
- Lida Vratsanou, p2822207


## Machine Learning Project Repository

Waste Classification 

#### All the scripts available in Github, along with the data folders and final model weights are all available in our [Google Drive](https://drive.google.com/drive/folders/1urVhqK5nDfZzLGhPScMxFY_cBKNHjzlH?usp=drive_link)


### 0.Data Extraction
This script is used to extract all of the images from the zip file, containing 7 folders, one for each category.

### 1.Rename Images
The purpose of this script is to rename all of the images so that they share the same naming convention. For each category (already 7 folders) we rename the images as such: {class_name}_{4 digit image_number}.{image format}

### 2.Data Preprocessing
The purpose of this script is to make all the necessary transformations to the images so that we can consume them during the model building.

### 3.Data Split
The purpose of this script is to split the images into 3 sets of data: Train, Test and Validation. Each set will contain random pictures from each category (keeping the same folder structure). Based on the size (7,838 images) of our dataset we decided on using the following ratios: 70%Train, 15%Test, 15%Validation.

70% Training: This is the portion of the dataset that our model will learn from. It's important to have a sufficiently large training set to allow the model to generalize well and learn the underlying patterns in the data.

15% Testing: The testing set is used to evaluate the model's performance on data it hasn't seen during training. This helps us understand how well our model is likely to perform on new, unseen data.

15% Validation: The validation set is used to fine-tune hyperparameters and monitor the model's performance during training. It helps prevent overfitting by allowing us to make adjustments based on validation performance.

### 4.Data Info
The purpose of this script is to visualize the different classes of waste.

### 5.Final Model
This is the script used to build the final model for waste segregation.

### 6.Initial Model
This script includes the initial model that we built, which was not used in the end.
