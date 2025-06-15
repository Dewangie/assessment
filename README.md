
Plan Of Action

For 
Seamlessly integrating person into a scene 
6th March,2025
 
Prepared by:  Dewangie Gautam 


Data Science cluster
School of Computer Science
UNIVERSITY OF PETROLEUM & ENERGY STUDIES,
DEHRADUN- 248007. UttarakhandTable of Contents




Assignment: Seamlessly Integrating a Person into a Scene
Objective
The objective of this assignment is to implement a step-by-step process to place a person into a given scene and seamlessly blend them to make the result look photorealistic. You need to do the research and make a plan of action on how this can be achieved. A few of the steps have been provided, follow these steps. Some steps might be missing, add those steps to complete the Algorithm.

Task 1: Capturing and Preparing the Person's Image
S1.I captured my image using a phone’s back camera with well lit environment as background.
S2.To remove the background of image, I used remove.bg without any disturbance to the image.
Task 2: Analyzing Shadows and Lighting of the BG image
S1.To create masks for the image I used OpenCV due to its wide range and accessibility to do minor changes for the shadows
S2.To detect hard shadows I converted it to grayscale and then I implemented thresholding to differentiate between hard and soft shadows then I refined it manually too for more difference.
Task 3: Determining Light Direction
S1: In my case my background had soft light incoming from right side and wasn’t affecting the shadows behind the person.
S2: I pasted my picture in layer above the background using photopea and adjusted the drop shadows to mimic shadows in the person for blending in.
Task 4: Coloring and Blending
S1: Using saturation and contrast I edited my person over the background and added color to person to match the background

