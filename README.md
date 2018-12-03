# Image-Processing-Assignment
MATLAB code for the four assignment tasks

Lincoln School of Computer Science

Assessment Component Briefing Document
Title: CMP3108M Image Processing,
Assessment Item One – Image Processing

Indicative Weighting: 50%

Learning Outcomes:

On successful completion of this component the student will have demonstrated competence in
the following areas:
• [LO1] critique the theoretical knowledge of image processing, including how to process and
extract quantifiable information from images.
• [LO2] apply image processing techniques to solve practical problems.

Requirements
This assessment comprises two assessed components, as detailed in the following page.
1. A file containing all functions written in the MATLAB code with clear comments along with
the requested figures for all individual tasks. Weighting: 25% of this assessment.
2. A viva demonstration in one of the designated workshops 75%
Useful Information

This assessment is an individually assessed component. Your work must be presented according to
the Lincoln School of Computer Science guidelines for the presentation of assessed written work.
Please make sure you have a clear understanding of the grading principles for this component as
detailed in the accompanying Criterion Reference Grid.
If you are unsure about any aspect of this assessment component, please seek the advice of a member
of the delivery team.

Submission Instructions
The deadline for submission of this work is included in the School Submission dates on Blackboard.
You must make an electronic submission of all source code files in the ZIP format, along with the test
and outcome images by using the assessment link on Blackboard for this component. It should be
submitted through TurnItIn and the zip file should be uploaded as supporting material. You must
attend the lectures for further details, guidance and clarifications regarding these instructions.
DO NOT include this briefing document with your submission.

Task: Image Processing Assignment
Download and unzip the file ‘Assignment_Input.zip’ from Blackboard. You should obtain:
• Four input images
• Four MATLAB script m-files named ‘Task1.m’ to ‘Task4.m’.

Complete the MATLAB m-files to perform the corresponding tasks described below. As a guide, a
few command lines for performing Task1 have already been added to the script. You need to add the
command lines to implement the other steps. Please add appropriate comments to your code to
briefly explain what each section is doing.


Assessed Component 1: Code (25%)
You must make an electronic submission of all four MATLAB m-files along with required output
images, as supporting materials, which produce the desired results and display the outputs. Make sure
the MATLAB scripts do not throw any error or display any error message. Your code should be
presented in a neat, structured way with brief comments for all tasks. Put all the files (including the
input images in a folder, and compress the folder into a zip file for submission. Name your zip file
and PDF report using this format: LastName_FirstName_StudentNo (for example:
janan_faraz_12345678). The report will have images produced by your code for all stages of the
assessment solution, where each image will have a caption/title to explain what it is. No further
explanation is required in the report. During the viva you will be asked to download your code,
explain your solution and reproduce those images again.


Assessed Component 2: Viva/oral exam (75 Marks):
In order to test your understanding of your implementation, you will be asked a series of technical
questions in one of the designated workshops (you will know about this later) for this module. The
examiner will ask you to download your code, and output images, from your blackboard submission
and run it. You have to satisfy the examiner on how you implemented the code and solved the
problem. The merit of your implementation and your understanding will decide the mark you achieve
for this assessment component. You should have implemented the following individual tasks in your
assessment:

Task1 – Interpolation (25 pts)
Complete the MATLAB script to load the image 'Zebra.jpg' and convert it to grey-scale. Then resize
the image from its original size of 556×612 to an enlarged size of 1668×1836 by interpolation.
Implement both nearest neighbour and bilinear interpolation. Display both re-sized images in your
report. Also add at least one close-up (zoomed-in section) to you report where the difference between
the two interpolation techniques is clear. Discuss the differences you notice between the two
techniques in viva. For this task, you CANNOT use the MATLAB built-in functions ‘imresize’ and
‘interp2’.

Task2 – Neighbourhood Processing (25 pts)
Complete the MATLAB script to load the image ‘Noisy.png' and convert it to grey-scale. Then
implement smoothing filters using averaging and median filters with a kernel (mask) size of 5
(neighbourhood of 5×5). Use zero-padding to deal with pixels on the edges of the image. For this 
task, you CANNOT use the MATLAB built-in functions ‘fspecial’, ‘imfilter’, ‘conv2’, ‘medfilt2’ and
‘filter2’. However, you CAN use any other built-in function, if necessary. Discuss the differences
you notice between the effects of the application of two filters on the image in viva. Display both
filtered images in your report.

Task3 – Object Recognition (25 pts)
Complete the MATLAB script to load the image ‘Starfish.jpg’ and, through a series of image
processing techniques you choose, generate a binary image where zero means no starfish detected
and a non-zero value means that the pixel belongs to a starfish as shown in the figure below. For this
task, you CAN use any built-in function.
In your viva, you will be asked to fully explain each step you have taken and justify the methods you
have used. Illustrate the outcome of each processing stage by displaying figure(s). For example, if
you used a particular type of spatial filtering, you need to explain why you have chosen it and discuss
its effect by showing the figures of the original and filtered images.

Task 4: Shape Description (25 pts)
While implementing task 4, you will have to describe and differentiate shape of the star fish from
other objects. To do this, you will need to devise a method that can interpret shape of a give binary
object. You are expected to produce ‘shape signature’ for a star fish and demonstrate how it is
different from any other object in the image. You will need to do some basic research in order to
understand how to describe shapes; moreover, there will be discussion about this in one of the
lectures.



