# Keypoint detection
An algorithm to detect keypoint in faces.

## Gist about the algorithm ##
  * Used 3 convolutional network
  * Opted MSELoss as a Loss Function
  * Used Adam optimizer
  
## Documentation ##

Dataset Used: [images](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/May/5aea1b91_train-test-data/train-test-data.zip)

Framework: Pytorch

Training Loss: 0.0819

Epoch:30

Batch_size:40

Libraries Used:
* Numpy
* Matplotlib
* torchwiz
* OpenCV

## Example ##

```visualize_output(images,output_pts,key_pts)```

![images](train.PNG)
