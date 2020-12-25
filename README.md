# X-ray CNN

This program uses Convolutional Neural Networks, using Keras, to predict if a chest X-Ray 
shows any sign of pneumonia.

So far I have achieved around 89.7% accuracy on the unseen testing data.

# Future plans

- [x] Use Keras tuner to get higher accuracy 
![Structure](./images/X-rayCNNStruc.PNG)
- [ ] Get graphs of accuracy vs epochs 
- [ ] Create an interface with visualizations of the model going through the images and evaluating them 

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
