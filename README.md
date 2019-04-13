# deep_learning_gun_detection

Run all the programs from research folder.

# Data

The data is in the folder research/object_detection/gun_dataset, in TFRecord format (train and validation set).

The file label.pbtxt contains the names and ids of the classes (here, there is only one class which is "handgun").

# Train

The program train.py allows us to launch the training. 

# Model

The program export_inference_graph exports the graph in a chosen folder.

We have multiple trained models, with different hyperparameters.
