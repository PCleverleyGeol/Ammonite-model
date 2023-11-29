# Ammonite-model
This is an Ultralytics YOLO V6.0 machine vision model for detecting fossil ammonites
It was created by labelling 300 images of ammonites, over 800 annotations in total using Datature's online free trial version
This was used via deep (transfer) learning to build a machine vision YOLO model
The model can be used on a Smartphone in VisionDetector which you will find in the App store. 
Download the Vision Detector App, then download the model and load the model in the Vision Detector App
Its accuracy varies depending on what you are pointing your Smartphone camera at.
Using the Vision Detector App you don't have the option to apply a cutoff (e.g. 0.6) so it tends to detect even low probability ammonites as 1.0.
You can of course build your own Smartphone App that may give greater control on only showing detections above a cerain confidence.
You can also simply apply it using Python to photographs.
It is mainly a bit of fun for children and adults to start getting interested in the Geology and AI topic, with possibilities for the visually impaired. 
It is not a scientific tool.
