# Transfer-Learning-using-ResNet152-for-Car-Make-and-Model
The development of a computer vision application that can recognize a certain vehicle model from an image is an intriguing and difficult subject to solve. The difficulty with this issue is that different car models can often look remarkably similar, and the same vehicle can sometimes look different and difficult to identify depending on lighting, angle, and many other variables. To create a model that can recognize a specific vehicle model for this project, I choose to train a convolutional neural network (CNN) known as ResNet152 using Fast ai and PyTorch.


ResNet 152 Block Diagram:


<img width="451" alt="RESNET152" src="https://user-images.githubusercontent.com/94075388/204136623-7fe0b550-cac9-43b5-baef-4d0a35f5064d.png">

# Dataset
For the Dataset: https://ai.stanford.edu/~jkrause/cars/car_dataset.html

There are 16,185 photos of 196 different kinds of cars in the Cars collection. The data has been divided into 8,144 training photos and 8,041 testing images, roughly splitting each class 50-50. Classes are usually given in the Make, Model, and Years categories.

Visualising the Dataset:

![VGG16-DATA](https://user-images.githubusercontent.com/94075388/204136719-e5756ffd-84ca-407e-9bd4-2e87ea907992.png)


# Results

Accuracy obtained: 94%




![resnet152_fastai_plot](https://user-images.githubusercontent.com/94075388/204136797-7f463579-41d6-44fa-b9e0-48393270cca7.png)





