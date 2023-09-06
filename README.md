# German-Traffic-Signs
### About
This project contains a full training and evaluation pipeline for a recognition model based on VGG-16 architecture.

### Dataset
The model is trained on the [GTSRB dataset](https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign), which contains 50,000 images of 43 different classes.

### Model
![VGG-16](https://camo.githubusercontent.com/da2483399a34157f4ce5b807ee2fe983c49876e737cbcbae8d1f16f21c1f23b1/68747470733a2f2f7777772e63732e746f726f6e746f2e6564752f7e66726f73736172642f706f73742f76676731362f76676731362e706e67)

This project implements the VGG-16 model, modified to accept 32x32x3 images.

## Results
The model reaches ~0.96 accuracy on the test set and ~0.97 on the validation set.


