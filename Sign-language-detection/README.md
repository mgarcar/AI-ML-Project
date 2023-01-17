## SIGN LANGUAGE DETECTION

Two different notebooks were programmed, one to collect the images to train our model (Collecting the images.ipynb) and the second one (Program.ipynb) to built the program itself.
The TensorFlow folder contains additional folders. The first one (labelImg) was cloned from the official github repository with which package we were able to label the collected images.Then we also included a folder called protoc which is a package needed to run our program. 
We also have included the python file to generate a tfrecord inside a folder called script. You will need this when executing the notebook. 
Furthermore, we downloaded official pretrained models from the TensorFlow library, by cloning the official TensorFlow object detection library. These models were originaly stored in the folder models, however given their size their were not uploaded to this repository. If you were to run all the program it would be necessary to dowload those models again.
When continue navigating through the directory we come up with a folder called workspace. In there we have included all the material we used to build and run our program. 





