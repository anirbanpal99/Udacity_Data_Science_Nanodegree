<h3>For Data Preparation</h3>
<ul>
  <li><b>ETL Pipeline:</b> This notebooks is for data preparation - [Extraction, Transformation & Loading]</li>
  <li><b>ML Pipeline:</b> This notebook is for message classification of the data </li>
</ul>
<h3>Data Set</h3>
<p>All the neccessary data sets are give within <b>Workspace_nw->data</b></p>
<h3>Web App</h3>
<p> After doing the ETL & ML pipeline, go into <b>workspace_nw</b></p>
<ul>
  <li>First go to <b>data->process_data.py</b></li>
  <li>Then go to <b>model->train_classifier.py</b></li>
  <li>After successfull execution of all the things, go to <b>App</b> then type `python run.py`</li>
</ul>
<h3>Conclusion</h3>
At last, you will able to classify any message in a web app, which is very helpfull for analyzing the classification of disaster message

<h3>Notes:</h3>
<p>In the ML pipeline part I have used Linear Support Vector Classifier. If any one want to do this by KNeighbourClassifier, they can do it, all the neccessary lines are added with <b>train_classifier.py</b> in comments. You can also do it by RandomForest, Logistic Regression. But Among them I found <b>LinearSVC</b> is efficient for me, so I have used it</p>

<h3>Output</h3>
The output of the web app is given below
<img src="https://drive.google.com/uc?export=view&id=1EdBxzFcYccze8e962t7fdaahRzm6aEtV" alt="image1">
<br>
<img src="https://drive.google.com/uc?export=view&id=1S8yazy2M6hjzegJ65pH7HQByNU3d6Lj4" alt="image2">
<br>
<p>If you cannot see the image, you can vistit https://drive.google.com/uc?export=view&id=1EdBxzFcYccze8e962t7fdaahRzm6aEtV for image 1 and https://drive.google.com/uc?export=view&id=1S8yazy2M6hjzegJ65pH7HQByNU3d6Lj4 for image 2</p>
