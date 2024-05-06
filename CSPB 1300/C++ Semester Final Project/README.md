CSPB 1300 Final Project (C++) - Spring 2024

This Directory contains the resuls of my final project for my CSPB 1300 course (Computer Science 1: Starting Computing) Spring 2024 semester. 

The objective of the project was to create an application using the C++ language, that can take a raw bitmap image, manipulate it and return a new image based on the user's desired image type. For the project, the class was provided a series of 10 algorithms for image processing in the Python language. We were to convert the python into C++ and then build a user interface, which allowed the user to enter the name of the input image names and select the desired process. The application allows for the user to graciously exit the program by selecting a letter to quit.  

The image processes in python initially provided to the class were as follows:
1. Vignetter
2. Clarendon
3. Grayscale
4. Rotate 90 Degrees
5. Rotate Multiple 90 Degrees
6. Enlarge
7. High Contrast
8. Lighten
9. Darken
10. Black, White, Red, Green, Blue

In addition to these required processes in the project, I've added a few additional elements to the program:

1. User input validation has been for all points of user interaction. Program will continue to operate in the event the user inputs an incorrect value and will notify the user of the error and continuously prompt user to input a new value until a correct value is provided.
2. Additional image processes were added:
  1. Sepia Tone
  2. Sobel Edge Detection
  3. High Pass (Sharpen)
  4. Image Blend

Files included within the directory:
1. lassiter_main.cpp - This contains the overall application
2. sample.bmp - this is the bitmap image used for grading purposes of the class and provided to students for use in development of our application.
3. blackbuck.bmp - this was an additional bitmap image downloaded from the Universiy of South Carolina (https://people.math.sc.edu/Burkardt/data/bmp/bmp.html)



Sample Images:




