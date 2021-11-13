# Team-TEAL-REVA-HACK-2021
#REVA HACK 2021
#REVA HACK</> 2021 
#Elevator Pitch 

#TEAL 

Anusha B Kandikere
Neeyal D
Sujnan MP 

#BLINKY
12th November, 2021 
Overview (What problem are you trying to solve) 

Here we are using vision-based eye-blink monitoring systems to solve many  possible problems like fatigue monitoring, human–computer interfacing and lie detection and many more.


#Goals (How are you solving the problem stated) 

Here in the project, we will use the python language along with the OpenCV library for the algorithm execution and image processing respectively to solve the problems faced during the process


#Working Methodology (Summary on how your project is going to work/solve the problem stated) 

First of all, our blink detector starts the process by  performing an facial landmark detection to localize the eyes in a given frame from a video stream. 
Once we have the facial landmarks for both eyes, we compute the eye aspect ratio for each eye, which gives us a singular value, relating the distances between the vertical eye landmark points to the distances between the horizontal landmark points.

Once we have the eye aspect ratio, we can threshold it to determine if a person is blinking — when the eyes are open and then will rapidly approach zero during a blink, then increase again as the eye opens 


#Specifications (Tech Stack Used - Hardware + Programming Languages) 

We are detecting the blink of the human eye using the feature mappers knows as haar cascades.
The primary programming language used is PYTHON along with imported libraries such as Numpy and OpenCV .

 

Instructions: 
1. Read all the Instructions carefully as not following them will impact your overall points. 
2. Remove all the small braces and their contents in the heading before submission as it is for team’s reference only 
3. Goals should include what are you doing in your project which will help solve the stated problem 
3. Don’t include stuff like i5 processor or 16GB ram in hardware specs. If you’re solving an IoT or AR/VR Problem then mention the hardware used. 
4. Pitch should not take more than 1 minute to read. It is advised to read the pitch before submitting to make sure it’s not taking more than a minute. 
