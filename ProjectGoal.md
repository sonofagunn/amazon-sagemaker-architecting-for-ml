# Project Goal
Help Airbus locate all ships around the world for the purposes of monitoring for commercial interests and public safety.

# Datasets
## Ground truth
train_ship_segmentations_v2.csv - contains the ground truth for the training images. It is a dictionary of image names to run-length encoded masks of ships that were found.

# Training images
train_v2.zip - a set of .jpg files to train on

# Test images
test_v2.zip - a set of .jpg files for testing

# Modeling Strategy
Our strategy will be to convert the input dataset into the formats needed for SageMaker's object detection algorithm.

# End Goal
We aim to build a model that can be fed satellite images and identify locations of ships. Performance should be good enough to run daily on all new satellite images worldwide.
