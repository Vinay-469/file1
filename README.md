# file1
import cv2
import numpy as np
from google.colab.patches import cv2_imshow

#read an image
img= cv2.imread("/content/sample_data/WIN_20231223_15_46_55_Pro.jpg")

#display an image
cv2_imshow(img)

#write an image
cv2.imwrite('vinay.png',img)

print(img.shape)
print("output image")
