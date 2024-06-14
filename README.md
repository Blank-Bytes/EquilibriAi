# Equilibri Ai
<img src="yoga.png"/>
<h1>Description</h1>
Hi welcome to this deep learning project "Equilibri AI ". This project as the name suggests can predict the yoga poses; which can even be trained by you or your teacher.<br>
This project comprise of three python scripts namely,<br>
Data Collection<br>
Data Training<br>
And finally Inference script.<br>
As all of the name suggest do there respective work.<br>

For this project mediapipe pose detection is implemented to detect the human body pose and after that is created into a model with simple Dense network using keras and trained the model on the data. After that the inference file is executed to for prediction.<br>

<h1>Requirements</h1>
<code>pip install mediapipe</code><br>
<code>pip install keras</code><br>
<code>pip install tensorflow</code><br>
<code>pip install opencv-python</code><br>
<code>pip install numpy</code><br>
<code>pip install kivy</code><br>
<code>pip install kivymd</code><br>

<h1>How to Run?</h1>
<h2>Adding Data</h2>
  To add data you have to run <b>python data_collection.py</b> and  have to provide the name of asana you want to add.
 <h2>Training</h2>
  To train just run <b>python data_training.py</b> to train the model on newly added data.
  <h2>Running</h2>
  To Run just run <b>python inference.py</b> and new window will pop up which will be running the predictions.

  
