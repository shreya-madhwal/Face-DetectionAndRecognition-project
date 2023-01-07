# Face-DetectionAndRecognition-project

Steps Taken:

Face Detection:
1. Install required libraries and import them.
2. OpenCV is used  to apply its deep neural networks (dnn) module.
3. Here we’ll loop over the detections and draw boxes around the detected faces and confidence of those faces are mentioned.
4. For webcam detection I have imported three additional packages- VideoStream , imutils , and time.


Face Recognition:
1. I have first detected faces.
2. Now computing 128-d face embeddings to quantify a face
3. Training a Support Vector Machine (SVM) on top of the embeddings
4. Recognizing faces in images and video streams


RESULT

We have successfully performed face detection and recognition task.
Below are the attached images as a result we got from our system.

Face Detection

Detection in image: blocks are showing detected faces
![image](https://user-images.githubusercontent.com/84977514/211156176-055e10c7-a548-42b4-a777-a6d08fb9f773.png)
![image](https://user-images.githubusercontent.com/84977514/211156186-51973e05-f566-41f3-9f80-f33f6b10c219.png)

Detection in webcam: blocks are showing detected faces

![image](https://user-images.githubusercontent.com/84977514/211155924-0c2d6073-606b-40fb-ad54-cc3d3667736b.png)
![image](https://user-images.githubusercontent.com/84977514/211155932-1e95af24-42b0-4278-9dd6-b65cd70343c9.png)

Face Recognition
Recognition in image: blocks are showing Recognized faces with there names and confidence

![image](https://user-images.githubusercontent.com/84977514/211155966-6ca370d1-3079-4f2e-8a6d-ffe10c1ed073.png)
![image](https://user-images.githubusercontent.com/84977514/211155972-2c2ce638-c2f0-4718-81cd-e95cc63cf908.png)

Recognition in webcam: blocks are showing Recognized faces with there names and confidence

![image](https://user-images.githubusercontent.com/84977514/211155988-0a3cef21-b2f2-4640-8987-15c2d5efd6af.png)
![image](https://user-images.githubusercontent.com/84977514/211155996-3177fb04-df5d-4ad6-96ce-6dc39039d595.png)


