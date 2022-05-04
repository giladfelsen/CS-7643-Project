# CS-7643-Project
Links to Code used in Project.

Link to github readme [CLICK HERE](https://github.com/giladfelsen/CS-7643-Project/blob/main/README.md)

There are a total of 4 folders that were used to execute code. The first three folders all build off/execute the code from [this repo](https://github.com/kekmodel/FixMatch-pytorch), which is an unofficial implementation of the Fixmatch algorithm in pytorch. 
The last foldre builds off/executes the code from [this repo](https://github.com/torchssl/torchssl), which is the official implementation of Flexmatch algorithm in pytorch (and also includes implementations of other SSL algorithms).

# Code uploads

## Folder 1: 
This first [folder](https://drive.google.com/drive/folders/1noE3Yw8UsVrf52lTDN2uw-8yqpxf_bne?usp=sharing)  
(FixMatch-pytorch-master) links to the folder where we ran the original Fixmatch algorithm, as well as the General Weighted Loss model mentioned in our paper. There are also various edits to the types of data augmentations performed during training. 

## Folder 2:
This second [folder](https://drive.google.com/drive/folders/1Ld8VhfzUere53EZLtpMUS-XvIwfUcBJe?usp=sharing) 
(FixMatch-pytorch-master)links to the implementation of the Fixmatch algorithm with various changes to the data augmentation process. Some of these changes include methods that were left out of our paper due to lack space. For example, we wrote code that added additional Datasets and DataLoaders that performed different types of augmentations (various permutation of weakly/strongly augmented images).  


## Folder 3:
This third [folder](https://drive.google.com/drive/folders/1ejnX-3fG9JEDOu0o4KzfkJ3SCOHcInUl?usp=sharing)
(FixMatch-pytorch-master-newloss) links to the implementation of the Per-Class Weight Loss models mentioned in our paper.  
In addition to editing the code for the loss function we added additional code to track various metrics throughout training.
Most of the significant changes to the code are in the train.py file.


## Folder 4:
This fourth [folder](https://drive.google.com/drive/folders/1L9deRxt47KY0P0wt50-3bIquxZ5CXpTv?usp=sharing)
(TorchSS-main) links to the implementation of the Flexmatch algorithm. The majority of edits to the files in this folder were to including various metrics such as per-class accuracy and confusion matrices throughout training.

# Animations:

Below are Animations of the confusion matrices for Flexmatch (top) and Per-Class-Loss (Bottom) for 40 labels




https://user-images.githubusercontent.com/31493465/166673399-c94047a4-bf84-41ce-8867-9021ab114f69.mp4




https://user-images.githubusercontent.com/31493465/166673425-ea621086-4331-4a20-91ec-3301369ba7a8.mp4






