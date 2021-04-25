# YOLOV5_BoundingBox-BinarizationOf_ROI(mean-or-median-pixels)
#Algorithm to detect tactile paving
Here I edited detect.py file, Then extract bounding boxes. From bounding box coordinates, I find the middle point 
and around it, I calculated the mean or median pixel of RGB and I use that pixels for binarization.

Edited part of detect.py
![image](https://user-images.githubusercontent.com/57138931/115990924-e78e3700-a600-11eb-9436-6e784463eed8.png)
Orginal image:
![image](https://user-images.githubusercontent.com/57138931/115990947-fd9bf780-a600-11eb-8a0e-ae26031fbc1e.png)
Binarized image:
![image](https://user-images.githubusercontent.com/57138931/115990980-215f3d80-a601-11eb-8db7-56bfa63c430d.png)
masked image:
![image](https://user-images.githubusercontent.com/57138931/115990999-34720d80-a601-11eb-9f07-f741542d03cf.png)
All together:
![image](https://user-images.githubusercontent.com/57138931/115991017-4489ed00-a601-11eb-9dca-4462d8f1bc21.png)
