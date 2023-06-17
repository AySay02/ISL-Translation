# ISL-Translation
> -- Sample Model to detect and translate ISL (Indian Sign Language).\
> -- Data images were collected using OpenCV2, and body posture landmarks were scanned and recorded using MediaPipe Holistics.\
>**NOTE:-** The data was collected and recorded by myself only, which is not publicly available, so the model had a problem with Data Leakage, (ie. the training and testing data set contained almost similar images), but it can be trained on other self-made data-set too.\
> -- I've added functions that'll convert your .jpeg images to NumPy arrays of landmarks (Using mediapipe holistics) which can be stored directly to your respective google drive folder.\
> -- The model is RNN model containing stacked LSTM layers.\
**Note:-** The errors shown in the notebook are because I made my own changes in my system, they should be present in other system if data folders in google drive are properly sorted.
