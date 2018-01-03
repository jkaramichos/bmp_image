# bmp_image

Brief Description of Project:

Write code to read, write, and crop BMP image files. 

test_bmp.c:
-this is the driver program containing the main function to call functions to read and write bmp images

bmp.c:
-this file creates the user defined functions to read and write bmp images

bmp.h:
-this file contains the BMPImage and BMPHeader structs that are used in bmp.c and test_bmp.c

input file: 
-airplane.bmp

output files:
-myairplane.bmp
  -this should be the same as the input file. The program will read the input file into a new image struct. Then write the newly created image into the file myairplane.bmp

-my_crop.bmp
  -this file is the cropped image
  
 **For full description of project: https://engineering.purdue.edu/ece264/17au/hw/HW15
