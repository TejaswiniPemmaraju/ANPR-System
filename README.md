# ANPR-System

The increasing issue of forged or irregular license plate pose a problem for traffic law enforcement. A real time “Fake License Plate Recognition” would have many applications such as automatic vehicle surveillance, traffic management, and monitoring. Such a system captures images, identifies license plate numbers automatically. Then the system proceeds to identify the make and the model. The system algorithm is based on two processing stages:
•	Recognizing Alphanumeric characters 
•	Identifying and Extracting the License Plate

In the first step, we use Histogram of Gradient as feature descriptor in image processing for derivation of feature vector. We classify these feature vector using 2 classification algorithms; SVM and KNN.  
In the second step, License Plate is detected and segmented to identify each character in the plate.
The system faces irregularities as Indian License Plate System does not have a standard format. 

The  training was done on 268 digit images and 111 images containing alphabets. The testing was done 26 random images different from the training set. The classification algorithms that were used are: SVM; KNN. The SVM classification algorithm gave 96.1% accuracy and the KNN classification algorithm gave 76.9% accuracy. The whole system was tested on 30 car images containing license plates. The license plate was successfully detected in all the images, only some characters were correctly recognized in each plate due to varying fonts of Indian License Plate.    

This project was done in 2019 as part of my undergrad minor project work. Done in collaboration with other students.
