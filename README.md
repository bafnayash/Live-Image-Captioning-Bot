# Live-Image-Captioning-Bot
In this project, I have built a live image captioning bot. The dataset used for this project was
Flicker8k dataset. The raw data was first pre-processed and all the captions related to a
particular image id were stored in a dictionary. InceptionV3 architecture was used for
encoding the images and 300-D GloVe vectors were used for word embeddings. LSTM was
used for training the model. The model was trained for 30 epochs and the learning rate of
the adam optimizer was reduced regularly after definite number of epochs to improve the
performance of the model. While decoding the caption from the output of the model, beam search was used, to improve the performance of the model. Finally, the
trained LSTM model was used to caption a live video using opencv.
