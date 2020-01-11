# Entry_Task_Sudoku
_this git repository contains code and dataset that are used to build a machine learning model.<br>
the model should detect and recognize Sudoku Puzzle from newspapers images and return the detected Sudoku in an array._
## Implementation Technique 

 _the implementation of this model is splitted into 2 parts_:
  - first : _various image processing techniques such as Hough Transform and Contour Detection are used to detect the grid and digits
  of the Sudoku puzzle_. 
  - second  :  _create **Convolutional Neural Networks model CNN** model using **Keras API** to recognize each digit_.

_the reason for choosing this techniques is :_
 - _to build a Tensorflow model from scratch to detect the whole sudoku puzzle directly is hard in our case because we need to label more images with diffrent font style and diffrent quality, because for such a task 200 images are not enough.that's why i have decided to do image processing first to detect cells and use **Keras** which is also a **Tensorflow API** to recognize each digit_.
<br>**Note**: _due to the already mentioned techniques of implementation i exported the model as '.h5' file format_.

my implementation is based on the following research papers which when creating the sudoku dataset used to train the model : 
 - <a href="http://ieeexplore.ieee.org/xpl/articleDetails.jsp?tp=&amp;arnumber=7007986" rel="nofollow">Camera-based Sudoku recognition with deep belief network</a>
 
