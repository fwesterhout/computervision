
# *Computer vision by Deep Learning*

Authors: Mahir Sabanoglu & Frederik Westerhout

Code used for blog can be found on Google Colab https://colab.research.google.com/drive/1NpgQPukwVPzuIOUyX_Ct1K0FnIlhF6TB?usp=sharing
The code which was used for the preprocess of the original dataset is a Jupyter Notebok file (.ipynb) and can be found in this repository as preprocess.ipynb. We chose to work with Jupyter Notebook for the preprocess as the original dataset was to large to upload to the Google Drive without waiting hours. 

Datasets:

Due to the file-size limit of 25 Mb we have only added the datasets which suffice this limit. The original dataset can be found at https://data.mendeley.com/datasets/v3kry8gb59/1. 
The uploaded datasets have the following structure to make it compatible with the dataloader: 	
                     

			dataset/
                       
       test/    <------------------>	 train/

    mask<--------> no_mask          mask <----------> no_mask


Abstract Blog:

In this blog, we propose a neural network architecture that is able to differentiate whether people are wearing face masks in a real-time setting. This can be potentially used to monitor if individuals are not wearing face masks in a crowd, which can be useful for many different applications, like research on contagiousness of the virus and supervision. An approach is shown how to practically train and test a neural network model with a non-standard self-augmented dataset in the topic of image recognition in computer vision. The steps taken considering the choice of the network architecture, the processing and ordering of the data and the implementation and results of the training process are shown.

Link to blog post:

https://fwesterhout.medium.com/a-deep-learning-approach-to-detection-and-classification-of-face-masks-in-surveillance-dataset-55a21e9efbce

