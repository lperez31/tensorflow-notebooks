# Full TensorFlow input and training pipeline for large datasets with data augmentation

In TensorFlow documentation, there are many examples of specific tasks. But I haven't found any full example which could be used as a starting point for my real life Deep Learning projects.

Thus, the purpose of this notebook is to show an example of a full Deep Learning workflow with TensorFlow:

1. Read large training data from files
2. Apply data augmentation
3. Train the model
4. Compute validation loss
5. Send logs to TensorBoard
6. Save and restore model
7. Use trained model for prediction

For reading data, we will use the new high level Dataset API. With this API, we will not need queues.

We will show how to use the Dataset API for:
* loading multiple files for each input example,
* data augmentation.

## Usage

Please look at the notebook here:
[tensorflow-dataset/Large_datasets_with_data_augmentation.ipynb](tensorflow-dataset/Large_datasets_with_data_augmentation.ipynb)
