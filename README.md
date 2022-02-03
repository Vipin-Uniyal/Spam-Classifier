
<p align='center'><img height='200' width='200' src='https://user-images.githubusercontent.com/31500911/143222349-cec3a8c3-dd01-4d6b-87bb-f590eee880c7.png'></p>

<h1 align='center'> Model deploy using Streamlit on Heroku platform</h1>
<h3 align='center'>https://email-spam-classifier-vipin.herokuapp.com/</h3>
<br>
<p>In this project I built a model for classifying the Email/SMS into <b>Spam</b> or <b>Ham</b> through the text of Email/SMS using standard classifiers.</p>
<br>
<h2> What it does :</h2>
<p align='center'><img src='https://user-images.githubusercontent.com/31500911/143223698-ce619b5d-ec93-4725-9945-31c36273cdd6.png'</p>
<br>
<h2>Live Demo :</h2>
<p align='center'><img src='https://user-images.githubusercontent.com/31500911/143228104-d5c25e1f-606f-4eb1-8848-3916650082ee.gif'></p>
<br>
<h2>How it does : </h2>
<p>Extract the text and the target class from the dataset. Extract the features of the test using TF IDF vectorizer for the input features.  Use standard classifiers to classify the data into spam or ham.</p>
<br>
<p align='center'><img src='https://user-images.githubusercontent.com/31500911/143228853-d59b05e8-4765-48ef-afec-fe91ec4cebcb.png'></p>
<br>
<h2>Prerequisites :</h2>
<ul>
  <li>Python</li>
  <li>scikit-learn/sklearn</li>
  <li>Pandas</li>
  <li>NumPy</li>
  <li>nltk</li>
  <li>Matplolib</li>
  <li>Jupyter/Spyder/Pycharm</li>
</ul>
<br>
<h2>Dataset :</h2>
<p>You can collect raw dataset from <a href ="https://github.com/Vipin-Uniyal/Spam-Classifier/blob/main/Dataset/spam.csv">here</a>. The files contain one message per line. Each line is composed by two columns:
<ul>
  <li>Class(v1)- contains the label (ham or spam)</li>
  <li>Message(v2) - contains the raw text.</li>
</ul>
<br>
<h2>Model Pipeline :</h2>
<p align='center'><img src='https://user-images.githubusercontent.com/31500911/143231312-a5cd9b57-895a-48b4-96eb-9652d561eeaf.png'></p>
<br>
<h2>Accuracy Result :</h2>
<p align='center'><img src='https://user-images.githubusercontent.com/31500911/143232140-06367c4c-ce52-4a70-990a-b2133571f456.jpg'></p>
<p>Considering overall performance of Precision and Accuracy</p>
<p>Since NB has the best Accuracy and Precision, <b>Naive Bayes</b> is the model.</p>


