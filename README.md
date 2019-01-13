# seizureAlgo
an algorithm that will read videos and determine the likelyhood of the video causing a seizure through it's accuracy. 
<br>
we used 2 videos to train the model. 1 for triggers:<br>
https://drive.google.com/file/d/1OWMRqe7vicKMpqWYfGgohuBp5SQEBEv_/view?usp=sharingand 
<br>another for non-triggers<br>
https://drive.google.com/file/d/17Rh7jr6A90oSz62YYKaQaUFVIqhAwbEO/view?usp=sharing<br>
<br>
This csv file is probably not much use to you, so if you want to see it in action, contact me to give you access to the AutoML link. Then, you would just add and image and the model will automatically classify that image as flashy or not flashy. This model will be used in websites with videos. It will pull frames from videos and classify them as flashy or nonflashy. If it finds 3 different examples of flashy images right next to each other in terms of time, with 80%+ accuracy, it will flag that image as likely to cause problems for people with photosensitivity.
<br>
<br>
Made with TensorflowJS and :heart: @ Starterhacks 2019
