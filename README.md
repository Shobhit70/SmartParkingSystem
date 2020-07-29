<h1>Smart Parkimg System</h1>
This Problem statement was given at TechGig Code Gladiator Finale round hosted at Reliance Navi mumbai office.
Traffic congestion caused by vehicle is an alarming problem at a global scale and it has been growing exponentially. Car parking problem is a major contributor and has been, still a major problem with increasing vehicle size in the luxurious segment and confined parking spaces in urban cities. Searching for a parking space is a routine (and often frustrating) activity for many people in cities around the world and contributes to loss of time and money, stress for the drivers as well environmental impact due to unnecessary fuel burning. 
Smart Parking systems can be a boon in such scenarios. They can be deployed to obtain information about available parking spaces in a particular geographic area and process in real-time to place vehicles at available parking spots. With the help of smart parking system, there would be no congestion in parking lot because the available slot is given by our smart parking app.
As part of this challenge we have tried to built a brain for a smart parking app using image processing and machine learning using python libraries. Our project takes the image of a parking lot and at any time can provide the list of total parking spaces and how many available for parking.

<h1>Problem at hand</h1>
Develop a model to identify the parking slots, its vehicle occupancy, vehicle color and pose from a given image/images.
The model should take an image as input and return all detected parking slots in the image in Json format.
<ul>Each detection result from the model should be a list of 5 (cx,cy,v,c,p) values:
<li>First two should represent the centre coordinates cx, cy of the detected parking slot
<li>Third value should represent the vehicle occupancy v in the parking slot. It should be 1 if the vehicle is present in the parking slot and 0 otherwise.
<li>Fourth value should represent the color_code c (0-8 values for White-0, Silver-1, Black-2, Grey-3, Blue-4, Red-5, Brown-6, Green-7, Others-8)
<li>Fifth value should represent the pose p (0 for front facing i.e front of the car is looking at the camera, 1 for back, back of the car is looking at the camera)
</br>
<img src="https://github.com/Shobhit70/SmartParkingSystem/blob/master/test.jpg" width="800", height="800">
</br>
<img src="https://github.com/Shobhit70/SmartParkingSystem/blob/master/result.png" width="800", height="800">


