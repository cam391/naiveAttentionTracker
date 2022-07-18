# naiveAttentionTracker
 Naive Attention Tracking Tool using the Viola-Jones Algorithm.
 
 This project is a quick exploration into the Viola-Jones Algorithm, which is a machine learning algorithm for face detection.

My original hope was to create an application which could track whether a user was paying attention to their screen. While the algorithm doesn't work particularly well for things like tracking pupils, it can be hacked into a "naive attention tracker" if we define a user's "attention" to be the same as the user's face being detected by the software. With some tuning of the detection algorithm, we can reach a point where the program can detect the user's attention (ie detecting their face), or their inattention (if they turn or look away to the point that the program can nolonger detect their face).

I do not advocate for the use of such tools in industry or education. However, they are very interesting, and could be promising tools for a number of valid/non-dystopian reasons (driver safety, clinical psych/neuro studies, etc.).

A large amount of this code was sourced from: https://www.geeksforgeeks.org/opencv-python-program-face-detection/
Pretrained classifier from: https://github.com/Itseez/opencv/blob/master/data/haarcascades/haarcascade_frontalface_default.xml
Sound file from: www.FesliyanStudios.com.mp3
 
 
