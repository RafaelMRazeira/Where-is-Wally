# Where-is-Wally

## Description

At the bottom of the sea? At the peak of the tallest mountain? Where might that Wally chap be? Is there a way to automatically determine Where's Wally?

A number of images with random backgrounds is provided. In each image, the same Wally picture was placed at a random position, with random rotation and a small perspective transform.
The following items are provided as `TrainSet` dataset:

- A collection of random images with Wally's picture at a random position
- The annotation json files (LabelMe standard), determining where Wally's picture is in each of the train images

The following items are provided as `TestSet` dataset:

- A collection of random images with Wally's picture at a random position

The following items are provided as `ReferenceData`:

- The original Wally picture
- A csv file containing the centroid of Wally's picture in each of the train images

## Objective

The objective of this test is to find a way to automatically detect Wally's picture in each of the `TestSet` images, giving the centroid of the picture in each image as the final answer.


## Run Solution

To run this solution please: 

1. Install the requirements.txt in python enviroment or not
2. Change the img_test_json_path variable to path of a image you wanna test
3. Change the img_train_path and test_path variables to path of train and test datasets respectively on your machine 
4. Open the Classify_Wally.ipynb file in jupyter notebook or vscode with python extension
