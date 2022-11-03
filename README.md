We use the start_number command to start the picture from the desired number. In this way, we can perform the registration process starting from the desired number. 

ffmpeg -i video1.mp4 -vf fps=1 resimler/%d.png
 
ffmpeg -i video1.mp4 -vf fps=1 -start_number 55 resimler/%d.png

Below is the result of recording between 1-54 and 55-108 by splitting 54-second video frames per second.

![image](https://user-images.githubusercontent.com/6264787/199658800-089e779d-78e5-4760-9b5c-94a07ce7bcd7.png)
