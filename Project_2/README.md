# CV - Assignment 2

## Required libraries

* matplotlib
* pytorch 1.11.0+cu113
* cv2 4.1.2
* numpy 1.21.6
* pandas 1.3.5
* seaborn 0.11.2 (used only for the theme of the graphs)
* sklearn
* kaggle (used to download the dataset on Colab, not need if the dataset is already in the working directory)

These libraries are already available on Google Colab

## Running the notebook

The FER dataset and the trained models have to be in the same folder of the notebook.

The first part of the notebook load that dataset and it is necessary to run it.

Then we define the models and also this part must be run.

Then we do the training and the testing. The testing loads the saved model so it is not necessary to run the training again.

The demo can use a saved video or the webcam. It uses one of the saved models but it cannot be run on Google Colab (maybe the saved video can).

The visualisation part is using the same model loaded from the demo.
