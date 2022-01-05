# Develop the program to perform linear transformation on a image
from PIL import Image
 
  
img = Image.open("ross.jpg") 
 
rotate_img= img.rotate(45)
 
rotate_img.show() 

![image](https://user-images.githubusercontent.com/97161557/148202334-51456f1a-7607-4240-850d-a8e421bdaa13.png)
