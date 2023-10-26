# image_segmentation
Implemented an RGB to grayscale convertor. '\n'
Implemented a function to threshold an image by a treshold value t.
Implemented a function that plots the ROC(receiver operating characteristic) curve of the thresholding function under varying t.
Calculated the optimal threshold t (precision and recall weighted equally).
Created a better linear method to turn RGB into grayscale, by filtering the red colour, as the object our function was supposed to segment was an apple.
Replotted the ROC and recalculated the optimal threshold.
Better results can be noted, as the ROC curve is closer to the top left corner of the plot (the place where precision and recall are perfect).
Implemented a method to segment the image using k-means, using only color, and color and position as features.
Implemented a method to compare the input image and the clustered version by using the L2 distance and calculate the error.
Plotted error curves for both the color and color and position segmentation algorithm, under variying k (the number of clusters).
