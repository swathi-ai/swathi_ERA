### ERA Session 5
This Session was mainly focussed on pytorch concepts and modularization of the code

#### Description
**Pytorch** concepts like data loading, building custom data, data loading, model creation, training, testing, 
optimization, auto grad and learning rate scheduler were practiced. Pytorch is python hence it is easy to implement.
Also, modularization of the code was done like moving code to specific files which was written in single file.
Three files **utils.py, model.py** and **S5.ipynb**  were used.

#### Getting Started
The three files in this project are:
  - utils.py
  + model.py
  * S5.ipynb

The file S5.ipynb is the main file from which we run the code. This file has imports of utils.py and model.py
In S5.ipynb,  first the data has been rerieved and stored in data loader both test and train then we ran the model and shown the results.
The model has got an accuracy of **99.19%** with a **loss of 0.0211** 

utils.py file has all the common functionality that is repeated multiple times

model.py file has model defined in it with all the layers like convolution and max pool and relu activation function.


