# Workshop-Working-On-Images
## AIM :
The image should be converted to gray scale and HSV and display the H, S and V planes.

## Software Required :
jupyter Notebook

## Algorithm :
## Step1:
Choose an image , the image should be a plant , Tree, flower or building.

## Step 2:
Save the image and the filename should be username.jpg

## Step 3:
Convert the image to gray scale and HSV

## Step 4:
Display the H,S and V planes.

## PROGRAM:
```
Developed By: D.B.V.SAI GANESH
Register No: 212223240025

import cv2
import numpy as np
image = cv2.imread("sai ganesh.jpg")
image = cv2.resize(image,(300,200))
gray = cv2.cvtColor(image, cv2.COLOR_BGR2GRAY)
hsv = cv2.cvtColor(image, cv2.COLOR_BGR2HSV)
h, s, v = cv2.split(hsv)
cv2.imshow("Hue (H)", h)
cv2.imshow("Saturation (S)", s)
cv2.imshow("Value (V)", v)
cv2.waitKey(0)
cv2.destroyAllWindows()
```
## OUTPUT:
![Screenshot 2024-02-29 101918](https://github.com/saiganesh2006/Workshop-Working-On-Images/assets/145742342/c0337a77-d882-4d8d-ab16-4d6287e76839)
![Screenshot 2024-02-29 101952](https://github.com/saiganesh2006/Workshop-Working-On-Images/assets/145742342/139ffca2-c40d-4221-bd89-cb747a64facc)
![Screenshot 2024-02-29 102033](https://github.com/saiganesh2006/Workshop-Working-On-Images/assets/145742342/976113ed-8c0d-43f1-83d0-9fa5696eb7e8)

## RESULT:
Thus the image is converted to gray scale and HSV using python and displayed successfully.


