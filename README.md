# Welcome to Moodify!
Moodify is an intelligent song recommendation system built using TensorFlow, OpenCV, and Keras. It can recognize your emotions using the webcam and then automatically recommend songs based on your mood. The model can classify 3 Moods - Happy, Neutral, and Sad pretty accurately. It then generates a personalized playlist for the predicted mood on Spotify by taking your listening history into account.
The frontend was built entirely using html, css, and javascript, while the backend was built using Flask.

Dataset used for training the model: [Fer2013](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data) cleaned and cut down to three classes - Happy, Neutral and Sad 

Model: VGG16 (Used Transfer Learning)


## Instructions to download and run the application:
**It is recommended you install the dependencies in a python virtual environment**

* Install dependencies using `pip install -r requirements.txt`
* Assign the FLASK_APP environment variable
    *  macOS/Linux: `export FLASK_APP=app.py`
    * Windows: `set FLASK_APP=app.py`
* Run the server using `flask run`
* Access the home page on `http://127.0.0.1:5000/`
