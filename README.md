# Ode-to-Code
Task 2- Create a module(API based) that takes a hospital discharge summary as an image or pdf and predicts whether it’s a valid summary or not.

Here initially we are trying to read the image and convert the text in the image to string , and found a summary of the string. The summary of the paragraph is give as input to the TF-IDF technique to convert the word into a vector after converting it is given as input to the logistice regression classifier model which predicts whether the given image is valid or invalid. 

The accuracy of the model is 94.82.
