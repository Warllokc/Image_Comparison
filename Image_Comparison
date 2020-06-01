import cv2
import numpy as np

# GO TO THE PATH OF THE IMAGES
mypath ="C:\\Users\\apetricenco\\Desktop\\QA Classes\\Python\\STUDY"

# OPEN 2 IMAGES
image1 = cv2.imread('lyglw.jpg')
image2 = cv2.imread('lyglw1.jpg')

differences = cv2.subtract(image1,image2)

# IF DIFFERENCES ALL ARE 0 IT WILL RETURN FALSE
result =  not np.any(differences)  # after reverse will be TRUE
if result is True:
    print('The image are the same')
else:
    # CREATING NEW IMAGE WITH THE DIFFERENCE
    cv2.imwrite('result_black_white.jpg', differences)
    print('The images are diferent!!!')

