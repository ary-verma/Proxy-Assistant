# Proxy Assistant
Detection of students faces in class using computer vision and counting how many students there are to check if there was any false attendance/proxy marked.

## Introduction
Artificial intelligence is the theory and development of computer systems able to perform tasks normally requiring human intelligence, such as visual perception, speech recognition, decision making, and translation between languages. This is a project made under the domain of artificial intelligence that is deep learning. Deep learning is an artificial intelligence (AI) function that imitates the workings of the human brain in processing data and creating patterns for use in decision making. Deep learning is a subset of machine learning in artificial intelligence that has networks capable of learning unsupervised from data that is unstructured or unlabelled. Also known as deep neural learning or deep neural network. I have used computer vision to implement this project which provides output according to the problem statement.

## Problem Statement 
Nowadays taking attendance in class can be a chore for teachers. The hassle of counting the number of students after taking attendance to check if there were any proxies can be tiring, especially for a full-time working teacher. Create an artificial intelligence that counts the number of students in class. 

## Proposed Solution
Use of the computer vison convolutional neural networks library to detect faces in the photograph and print how many students are present in the class. In addition to this, save the cropped photos of the faces in a folder for the teacher to double check. This will help the teacher to compare the actual number of students with the number of students he/she marked in the attendance sheet. This will inform them of any extra unwanted attendances marked in the sheet.

## Input Image
![image](https://user-images.githubusercontent.com/64376922/114841905-f7826b80-9df5-11eb-9887-19593db060c4.png)

## Output
#### Faces Detected
![image](https://user-images.githubusercontent.com/64376922/114842397-6cee3c00-9df6-11eb-92aa-6ddd4505893e.png)

#### Boxes on faces that are detected
![image](https://user-images.githubusercontent.com/64376922/114842481-81cacf80-9df6-11eb-8551-244b9b8cfef1.png)

#### Images saved in folder test_faces
![image](https://user-images.githubusercontent.com/64376922/114842525-8becce00-9df6-11eb-856b-42174718efcb.png)

## Result
This project which used the MTCNN library detected the faces in the photograph and stored it in the test_faces folder for double checking. It successfully displayed faces in boxes and gave the number of students present in the classroom to help out the teacher while taking attendance.

## Conclusion
Taking attendance can be a cumbersome task that looks easy. With the help of this project attendance taking will become easier and more accurate. Hence, the problem was solved using this program.  
