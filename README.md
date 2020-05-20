# Ghost_Writer

## Overview

A combination of 2 models i.e script generator and question answer model and we name our model as Ghost Writer. Ghost Writer can complete a story given to it by its own and then answer the questions given to it.

Script generator takes script or text,trains on it and then it produces further text which is our input to the question answer model in form of paragraph,questions and answers. QA model is then trained on the given data and then it is asked questions and it gives answers based on its training with some certainity of words.

## Library Used:

* Pytorch
* Keras
* Lstm Model
* Pickle
* Sklearn
* Numpy
* Matplotlib
* Jupyter Notebook

## Resources Used:

* Google Colab ( For model training)
* Git (For data and code updates)
* Facebook Research Paper
