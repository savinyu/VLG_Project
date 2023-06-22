# VLG_Project
This is my repo for AI generated Image Detection - an open project under VLG(IITR). 

This project aims to perform AI generated image detection. It utilizes a dataset containing labeled images for training and evaluates the model's performance using the F1 score metric. The trained model is then used to make predictions on unseen test images and save the results to an output.csv file.

Used CNN for the model architecture. Also tried ResNet50 and VGG19 pretrained models but I got better f1-score on the self-trainned CNN model.

The file "Code.ipynb" contains the code for the solution to the problem statement using CNN model.
"my-output.csv" contains the output file.
The GDrive link for the Dataset folder : https://drive.google.com/drive/folders/16yfqE9z5lucXq6lBGqxeRBJZRa2iBP2-?usp=drive_link

The Dataset contains two files : 'test.csv' and 'train.csv'
