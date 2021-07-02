# WiFi Voice Controlled Robot
The wifi voice controlled robot is a robot that can be controlled using a person's voice, through the use of an app. The robot is able to move forward, backward, turn left, or turn right. This project has 3 different aspects: coding, app development, and electrical engineering. 

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Alan Zeng | Monta Vista High School | Computer Science | Incoming Sophomore

![Headstone Image](https://user-images.githubusercontent.com/86128051/124319916-cb8ea080-db2f-11eb-9aba-01323f3ec5e4.JPG)

# Reflection
After finishing my project, I realized that I learned a lot during this whole process. I learned to plan ahead, so that I would be able to complete goals on time. I learned to Google search effectively, so I can find resources to learn about the different parts of my project. Most importantly, I learned to perserve and keep trying, because even if something doesn't work the first time, it eventually will. Additionally, I realized that I really enjoyed the hands on part of this project. Participating in this program and building this project has motivated me to continue learning more about the different fields of science, and I hope to build more hardware and software projects in the future!

# Demo Night Video
[![Demo Night](https://res.cloudinary.com/marcomontalbano/image/upload/v1625254996/video_to_markdown/images/youtube--ilxuLSfCmlk-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/ilxuLSfCmlk "Demo Night")
  
# Final Milestone
My final milestone is assembling the robot, and getting all of the different components to work together. I am able to control the robot's movements from my phone, through the app. The buttons in the app are able to control the robot, but I am also able to use my voice as well. One major problem I had during this last step was not having enough energy to power 4 motors at once. I solved this problem by using three seperate power sources. I used a 9V battery, a rechargable battery pack, and 4 additional 1.5V batteries. After connecting three power sources to power the entire robot, the robot is now easily able to move forward, backward, turn left, and turn right.

[![Final Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1625255208/video_to_markdown/images/youtube--XCr45KlUi9M-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/XCr45KlUi9M "Final Milestone"){:target="_blank" rel="noopener"}

# Second Milestone
My second milestone is creating the app that will eventually control the robot. I designed the layout of the app, as well as programmed the app to be able to send messages to the ESP32, a WiFi microcontroller, which then sends the commands to the L298N motor driver to control the motors. Currently, whenever the buttons in app are pressed, an error message appears. This is most likely due to the ESP32 not being set up yet, so there is no response after pressing the buttons. 

App file: [Voice_Controlled_Robot.zip](https://github.com/AlanZeng1/AlanZeng_BSE_Portfolio/files/6743677/Voice_Controlled_Robot.zip)

[![Second Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1625082876/video_to_markdown/images/youtube--WbiUeXMx3rQ-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/WbiUeXMx3rQ "Second Milestone"){:target="_blank" rel="noopener"}

# First Milestone  
My first milestone is connecting the L298N motor driver with the arduino and motors, and getting the motors working. At first, I really struggled with getting the motors to work, as I did not understand how the connections between the battery pack, arduino, and motor driver worked. Later on, I learned that the battery pack was supposed to provide energy for the motors/motor driver, and not the arduino. After realizing the problem, I was able to connect the battery pack with the motor driver and get the motors to work.   

[![First Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1624389374/video_to_markdown/images/youtube--ICdF0UeNy_s-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/ICdF0UeNy_s "Alan's First Milestone"){:target="_blank" rel="noopener"}

![Motor Driver Diagram](https://i0.wp.com/www.teachmemicro.com/wp-content/uploads/2018/03/l298n-arduino-1-scaled.jpg?w=1236)
