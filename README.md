# Simple_colour_detection
Colour detection is the process of detecting the name of any colour of the objects in the image. This project can detect the major colour of an object.
This will neglect the minute colour details in object and presents the major colour as the colour of whole object 
#How to use
Add target images in the INPUT_IMAGES folder
Run the colour detector and enter the name of image in INPUT_IMAGES that you want to work on 
Enter the name of image with extension
The output will be displayed in separate window and that output will be saved in Results folder with the name "marked"+image name 
#How it works
First the image will be blurred for some extent so that the minute details will be covered
As for colour detection that image will be converted to hsv colour space 
Then different colour masks will be applied to the image to filter specific colours
After that contours will be detected for each colour masked part 
based on the area some of the unwanted contours will be neglected and for remaining a bounding box will be drawn along with the colour name in the original image
