# shredder-machine

Note that this not the original version of the code. This repo has the software implementation of the same application.

# Problem statement : To stop the shredder machine as soon as hand crosses a specified mark in order to prevent injuries to the operators' hands handling the shredder machine.
Note : Sensors like obstacle detecting sensor or PIR sensor could have been used. But sensors fail to classify between a hand and the garbage thus is not a practical solution for        the same.
Thus computer vision comes into the rescue where we can build hand detection model which detects hand and as soon as the hand crosses a specified mark.
# Dataset:
We have used custom dataset taken from the camera under different lighting conditions(day and night), varying distance. We have  taken into account the skin tone and also closed hand images were also considered for training.
# Project high level design
<img src="https://github.com/Shyam-AI/shredder-machine/blob/master/shredder-proj-plan.png" width="800px" height="auto">
