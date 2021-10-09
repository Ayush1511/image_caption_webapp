# Image Captioning
## Description
This application will generate caption for the image uploaded using a LSTM based deep learning model.
The web application was developed using flask framework and deployed using heroku and the link for the application is https://image-caption-flask.herokuapp.com/

## How to use the application
<ul>
<li>The user has to upload image which can be  in any format by clicking on choose file button.</li>
<li>Then press the submit button</li>
<li>After which the deep learning model at the backend will generate caption for the image uploaded.</li>
</ul>

## Methodology
<ul>
<li>The dataset used for training the model is https://www.kaggle.com/adityajn105/flickr8k.</li>
<li>Reviews divided into positive ,negative and neutral based on the score in datset.Score=0-2(Negative),Score=3(Neutral),Score=4-5(Positive)
<li>Tokenization,Stopwards Removal,Lemmatization ,Count Vectorization used for data preprocessing.</li>
<li>Random Forest Classifier model is used for classifying the review.</li>
</ul>

### Flowchart of Methodology
![](Flow_of_Methodology.JPG)

## I/O screenshots
### Input
![](/Screenshots/i2.JPG)
### Output
![](/Screenshots/o1.JPG)
### Input
![](/Screenshots/i1.JPG)
### Output
![](/Screenshots/o2.JPG)

## Authors
Ayush Goel

## License
[MIT](https://choosealicense.com/licenses/mit/)
