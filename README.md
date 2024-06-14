# Image_Classification_with_Machine_Learning
![](https://media.istockphoto.com/id/1265448899/tr/foto%C4%9Fraf/biyometrik-do%C4%9Frulama-ve-y%C3%BCz-alg%C4%B1lama.jpg?s=612x612&w=0&k=20&c=oTqGrKCfDATsWa4Kku_ETnCyeTvyJtJp6CTXKHNGqoQ=)

# Introduction

Hello everyone,

I created this project by following the this [project](https://youtube.com/playlist?list=PLeo1K3hjS3uvaRHZLl-jLovIjBP14QTXc&si=fLHnRNhDeBc1dvFl) series and wanted to share it with you. I hope you can benefit from reading it.
Since adding our original visual dataset directly to the project would increase the size of the project, I pulled it from the project's original git.hub repository.

I would like to tell you in general what we did in the steps, one by one. First, we included our images in the project and visualized our sample image.

Then we framed the face part from the picture and identified the eye objects within the frame. Then, we defined a function that cuts the face area in the image and saves it to a different file.

Then, we applied Wavelet transformation to these cut images to recognize the features more easily. And we combined the transformed and original images.

Then we moved on to the modeling phase. First, we created a pipeline for the SVC model. We evaluated the first model we created with SVC. And we moved on to the Hyperparameter step. In this step, we tried to find the best model and parameters among the parameters we gave with 3 different models(SVM,RandomForestClassifier,LogisticRegression).

Finally, by evaluating the model scores, we chose the SVM model as the best model.

Enjoyable reading.
