# Transet-Project
Crack detection and Crack Length estimation using Deep Neural Networks. Reference: Deep Learning-Based Crack Damage Detection Using Convolutional Neural Networks (Young-Jin Cha &amp; Wooram Choi)

This python code outlines step by step, the training and testing of a deep neural network model based on the architecture in the Reference: 
Deep Learning-Based Crack Damage Detection Using Convolutional Neural Networks by Young-Jin Cha &amp; Wooram Choi

The Training dataset for the data is saved in a folder :"Dataset" in the current working directory. The Dataset folder is expected to contain labelled images in subfolders. The number of subfolders indicates the number of classes while the name of the subfolders are the classnames.

Also includable in the current working directory is a "Test_Images" Folder containing Images with or without cracks for testing.
    
Libraries used: Pytorch, open CV, Tensorboard (optionally for viewing training progress, dataset and Network architecture)

Architecture: 

![Screenshot from 2021-05-17 19-49-13](https://user-images.githubusercontent.com/84150307/118573871-f9b74d00-b748-11eb-8290-788c47c46d25.png)

The training/validation accuracy would depend on the dataset used for the training. We achieved a 99 percent validation accuracy in our training.

This is a first task. The next goal is to ultimately expand this model to be able to classify a dataset consisting of more than two classes such as the SDNET2018 dataset  ehich consists of 6 classess.  

Results:

![tt](https://user-images.githubusercontent.com/84150307/118574082-5c104d80-b749-11eb-8e5b-0114985eae05.png)

![ty](https://user-images.githubusercontent.com/84150307/118574253-a85b8d80-b749-11eb-897f-87648daf00e3.png)

![yy](https://user-images.githubusercontent.com/84150307/118574293-bd382100-b749-11eb-90ea-3044f028f2ff.png)


