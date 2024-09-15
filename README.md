# Mood-Classifier

This project is all about predicting moods from the images using Neural Networks. <br>

Observations: <br>

I collected my data from google using extension 'Download All Images'. This is easy to use but may contain some noisy data that should be eliminated mannualy. eg : search for photo of a man but some photo of women is also downloaded. A google search with this extension is enough to collect raw data. <br>
Resize the image so as to avoid dimensionality errors, also images can not be opened are removed. Also used Data Argumentation to be more generalized.<br>

I used CNN(Convolutional Neural Network) to predict the mood of a person. 3-Convolutional and 3-Dense Layers are used in Model that can be seen in 'model_structure.png' file. <br>

On testing the model, I got accuracy of 64.99%, while for live predictions model was performing very well.<br>

Due to hardware constraints it was not possible for me to make more dense layer network while it can be clearly observed from the 'Accuracy' and 'Loss' curve that more Dense and Convolutional layers are required.<br>

Stored my model as 'imageclassifier.h5'. <br>

We can collect our own dataset and save in 'data' directory and use this model for classification.
