Here I am Sharing one of my projects from Bachelor's in Biomedical engineering. I have applied the deep learning in diagnosis of Acute Lymphoblastic Leukemia diagnosis.
The overall process starting from the microscopic image taken as input and then classifying them as either ALL or Non-ALL cell is shown in the below block diagram.
![Screenshot 2025-01-03 173440](https://github.com/user-attachments/assets/20ee34d5-c086-4502-9e33-95383f05b5c1)

As shown above, the process begins with taking hematology image as input, and then as we can see that the input image is having many other cells other than a lymphocyte and also in a single image we can encounter two or more lymphocytes and hence the next stage is to segment 
a lymphocyte cell using color-based k-means clustering as it provides more efficient result when it comes to blood cell segmentation. K-means algorithm identifies k number of centroids, and then allocates every data point to   the 
nearest cluster while keeping the centroids as small as possible. And as a result of segmentation, we will be ended with an image containing a single lymphocyte which will be used for further processing. The deep learning model imitates the work of humans to process data and develops 
a pattern to make decisions. Convolution Neural Networks (CNN) is specially designed to process pixel data and thereby used for image recognition. In this project, I have used INCEPTION V3, a type of deep CNN which is widely used for image recognition tasks.
