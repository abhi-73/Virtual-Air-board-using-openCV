# Virtual-Air-board-using-openCV

The idea for this tool is a result of interest in digital drawing and smart photo recognition software. The initial motivation came when there was a need for a dustless class. We know that there are many ways like touch screens and more but what about the schools which can’t afford it to buy such huge large screens and teach on them like a T.V. OpenCV in python to draw on the screen using a virtual pen i.e. , any marker can be used to draw using the technique of contour detection based on the mask of the desired colored target marker s room for the students to study in. We know that there are many ways like touch screens and more but what about the schools which can’t afford it to buy such huge large screens and teach on them like a T.V. OpenCV in python to draw on the screen using a virtual pen i.e., any marker can be used to draw using the technique of contour detection based on the mask of the desired colored target marker.


   Digital art and traditional art are interrelated and interdependent.  In the present circumstances, digital art and traditional art are inclusive of the symbiotic state, so we need to systematically understand the basic knowledge of the form between digital art and traditional art. The traditional way includes pen and paper, chalk and board method of writing. The essential aim of digital art is of building gesture recognition system to write digitally.  In this system, we are using gesture recognition with the use of computer vision and machine learning algorithm by using python programming, which creates natural interaction between man and machine. 

## Methodology 

![image](https://user-images.githubusercontent.com/108227459/178095632-4ea31e2e-ce3f-4cc7-840f-4073013c9ea6.png)

## Algorithm:
1. Setting a trackbar function.
2. Creating the trackbars needed for adjusting the marker color.
3. These trackbars will be used for setting the upper and lower ranges of the HSV required for the specific color.
4. Initializing different arrays which will handle color points of diff colors.
5. These arrays will hold the points of the specific color.
6. They are then used to draw on the canvas.
7. Initializing indexes for all diff colours which will be used to mark position of pointers in the color arrays using a kernel for dilation purpose.
8. Creating an array "colors" which will be used for the drawing purpose.
9. Setting up a Canvas.
10. Loading the default webcam of PC.
11. Loop begin
12. Reading the frame from the camera.
13. Flipping the camera so that it is easy to see the same side of the user.
14. Getting the updated positions of the trackbar and setting the HSV values.
15. Adding the colour buttons to the love frame for colour access i.e if the trackbar moves on to blue the tracker becomes blue. Similarly for green red yellow and to clear the screen.
16. Identifying the pointer by making its mask.
17. Find contours for the pointer after identifying it.
      Loop end;
18. If (the pointers are formed) begin
19. Sort the contours and find the biggest one.
20. Get the radius of the enclosing circle around the found contour.
21. Draw a circle around the contour.
22. Calculating the centre of the detected contour.
       end
23.  Now we will check if the user wants to click on any button above the screen.              
       Begin
24. Clear button
25. end
26. Append the next deques when nothing is detected to avoid any mess.
27. Draw lines of all colors on the canvas and frame.
28. Show all the windows.(Tracking, paint, mask)
29. If (q is pressed): then we stop the application.
30. Release the camera and all other resources.


### Applications: 

•	Persons having hearing impairment - as people who can’t hear and listen communicate using sign language. So here it acts as a translator in between.

•	Paper wastage-As a lot of paper is wasted in writing, drawing, scribbling etc. and it is harming the environment. So, air writing can solve this issue to a great extent.

•	Dustless Classroom-Already there are many techniques using touch screens but what about schools who can’t afford to buy large screens. So, in this case virtual colouring 
will be very helpful.


### Advantages: 

•	First and foremost, OpenCV is available free of cost.

•	It is portable as OpenCV can run on any device that can run C.

•	Low investment

•	Doesn’t harm the environment

•	Effective usage of time


### Outcome:

•	Hand-Free drawing

•	OpenCV

•	Colourless lines

•	Display of work as well as save the final work


### Limitations:

•	Background should not have colour same as object otherwise it will detect it and it will draw anything randomly.

•	 Definite shape can’t be drawn i.e., no straight line can be drawn so no uniform shapes like square or rectangle can’t be drawn.

•	Should have good lightning condition.


