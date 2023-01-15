Head segmentation project Computer Vision and Deep learning Course.

Part of the code was initally inspired by tensorflow and keras image segmentation tutorial (https://www.tensorflow.org/tutorials/images/segmentation).
However, I then needed to create a custom dataset and things became a bit complicated while integrating that into the Dataset API from tensorflow. So I stopped using the dataset API.
The whole dataset filtering and data preprocessing is added by me. The only thing that was taken from the tensorflow tutorial is the model structure, the way the layers are ordered.