<p align="center">
<img alt="Helmet Detector title image" src="https://raw.githubusercontent.com/rishiraj-acharya/Helmet-Detector/master/logo.png" /> 
<br/><b><a href="https://rishiraj-acharya.github.io/Helmet-Detector/">https://rishiraj-acharya.github.io/Helmet-Detector/</a></b><br/><br/><a href="#contributing"><img alt="Contributions Welcome" src="https://img.shields.io/badge/contributions-welcome-brightgreen?style=for-the-badge&labelColor=black&logo=github"></a> <br/><img alt="GitHub License GPL-3.0" src="https://img.shields.io/github/license/rishiraj-acharya/Helmet-Detector?style=for-the-badge&labelColor=black&logo=github"> <a href="https://twitter.com/RishirajAcharya"><img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/RishirajAcharya?style=for-the-badge&color=09f&labelColor=black&logo=twitter&label=@RishirajAcharya"></a><br/><br/>Using Keras and TensorFlow to train a classifier to automatically detect whether a person is wearing a helmet or not by fine-tuning the <a href="https://arxiv.org/abs/1801.04381">MobileNet V2</a> architecture.

</p>

Run the ```train_mask_detector.py``` to accept the input dataset and fine-tune MobileNetV2 upon it to create the resulting serialized ```helmet_detector.model``` classification model.

Open up a terminal, and execute the following command:

```
$ python detect_helmet_image.py --image examples/example_01.png
[INFO] loading face detector model...
[INFO] loading face helmet detector model...
[INFO] computing face detections...
```

Launch the helmet detector in real-time video streams using the following command:

```
$ python detect_helmet_video.py
[INFO] loading face detector model...
[INFO] loading face helmet detector model...
[INFO] starting video stream...
```
