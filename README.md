# TIL 2020
## Using AI and Robotics on Disaster Rescue
A project organised by DSTA.

## Problem statement

The year is 3000. Earth has been ravaged by war and the robots have taken over. The fields are barren, the situation is dire, and barely any human survivors can be found. Nevertheless, we must press on, and we must look for human survivors who may be injured and needing our help. This is where we need to use AI to our own advantage and save ourselves!

One of the problems is in saving victims within the wreckage. However, we want to save only a specific victim, and all we have is their description. Not to fear, however! For with the power of AI, that is all we need to save our victim!

Your job is to create 2 models to facilitate the robot's detection. The first part is in processing the written description of the victim, otherwise known as Natural Language Processing (NLP). Once provided the statement, the robot should be able to break it down to classify the words and identify various aspects key to saving our victim, such as their gender as well as their clothes.

The second problem is the detection of our victim using Computer Vision (CV). For this task our robot should be able to take in a picture, that may or may not contain our victim, and be able to draw bounding boxes indicating where in the picture there are clothes, as well as what kind of clothes they are, such as trousers or dresses. From there on, if the clothes in the box match up to the written description, the robot will know that it has identified the victim, and will proceed to save it using its arm.
