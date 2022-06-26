# Sign-Langauge-Recognition

Project Description - 

The proposed system implements the sign language recognition using CNN. It has been 
designed for the two-way communication. Dataset is created on our own for 10 different 
alphabets. Initially server starts running and the client connects to the server using IP and 
port. After the connection is established, both the system starts receiving the video frames. 
I have used socket programming to implement the server-client architecture. The webcam 
captures the image of the gesture from the bounding box created on the screen. Then the 
image undergoes pre-processing stages like cropping, conversion of RGB to HSV color 
space and finally applying mask operation on it. Then the masked image is given to the 
CNN model for features extraction. Finally, the predicted gesture will be displayed on the 
screen.

10 alphabets classified - 

![image](https://user-images.githubusercontent.com/70657455/175822125-77362a6f-e39b-4541-a0b6-35f29e483c10.png)

Overall Design - 

![image](https://user-images.githubusercontent.com/70657455/175822037-692da08d-a6ed-413f-9e96-79fd8376888c.png)

Results - 

![image](https://user-images.githubusercontent.com/70657455/175822186-362a2b46-3de5-4421-8a29-01d8f5fa536b.png)

