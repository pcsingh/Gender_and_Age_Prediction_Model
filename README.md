# Age and Gender Prediction

In this project, I have used the model architecture given in this report [Convolutional Neural Networks for Age and Gender Classification](http://cs231n.stanford.edu/reports/2016/pdfs/003_Report.pdf) by Ari Ekmekji and the dataset from [here](https://www.kaggle.com/ttungl/adience-benchmark-gender-and-age-classification), also shared the notebook under this dataset.

Dataset consists of discrete age of people and I mapped them into the 8 different ranges and used one-hot encoding for both the age and gender prediction model. I used `tensorflow` and `keras` the main tools for this project.

### Future work
This can be improved after adding one step which extracts the face from the images and that data is used for the training that might increase the performance, and also the project can be extended further for video type data.
