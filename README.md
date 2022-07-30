# colour_detection
Colour detection is the process of detecting the name of any colour of the objects in the image. This project can detect the major colour of an object.<br />
This will neglect the minute colour details in object and presents the major colour as the colour of whole object 
# How to use
Add target images in the INPUT_IMAGES folder<br />
Run the colour detector and enter the name of image in INPUT_IMAGES that you want to work on <br />
Enter the name of image with extension<br />
The output will be displayed in separate window and that output will be saved in Results folder with the name "marked"+image name <br />
# How it works
First the image will be blurred for some extent so that the minute details will be covered<br />
As for colour detection that image will be converted to hsv colour space <br />
Then different colour masks will be applied to the image to filter specific colours<br />
After that contours will be detected for each colour masked part <br />
based on the area some of the unwanted contours will be neglected and for remaining a bounding box will be drawn along with the colour name in the original image
# Here is a samle output
![alt text](https://github.com/Kashyap2502/Simple_colour_detection/blob/main/Results/markedballs.jpg?raw=true)
