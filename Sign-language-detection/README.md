## REAL TIME SIGN LANGUAGE TRANSLATION

In the file presentation you will find a pdf with the whole explanation of the project.

Apart from that, two different notebooks were programmed, one to collect the images to train our model (Collecting the images.ipynb) and the second one (Program.ipynb) to built the program itself.
The TensorFlow folder contains additional folders. The first one (labelImg) was cloned from the official github repository in order to be able to label the collected images.The folder called protoc includes a package needed to run the program, and the script folder contains the python file to generate a tfrecord.
To make the program work official pretrained models from the TensorFlow library were downloaded, by cloning the official TensorFlow object detection library. These models were originaly stored in the folder models, however given their size their were not uploaded to this repository. If you were to run the program it would be necessary to dowload those models again.
When continue navigating through the directory we come up with a folder called workspace. In there all the material used to build and run our program were included.





