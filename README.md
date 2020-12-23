# X-ray CNN

This program uses Convolutional Neural Networks, using Keras, to predict if a chest X-Ray 
shows any sign of pneumonia

# Data

The data used comes from https://data.mendeley.com/datasets/rscbjbr9sj/2
The dataset used was the "ChestXRay2017" which is structed in the format of

```bash
chest_xray
|
|___test
|   |
|   |___NORMAL
|   |   |
|   |   |__images...
|   |
|   |___PNEUMONIA
|       |
|       |__images...
|
|___train
    |
    |___NORMAL
    |   |
    |   |__images...
    |
    |___PNEUMONIA
        |
        |__images...


```

*Note: The data file containing the pictures of the X-Rays have been omitted in this github repository, 
since it is over 1GB*
