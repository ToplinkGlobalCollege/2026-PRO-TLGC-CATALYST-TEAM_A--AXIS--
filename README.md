# Engineering materials
This repository contains engineering materials of a self-driven vehicle's model participating in the PRO Future Engineers competition in the season 2026

## Introduction
This document presents the technical specifications and design details of the TLGC Catalyst Future Engineer's Team's autonomous vehicle robot for the 2026 Philippine Robotics Olympiad.

# Content
**docs**- Contains all documentation for the project, including robot architecture, programming flow, assembly instructions, improvement logs, and team information.

**hardware**- Contains EV3 hardware related files such as chassis designs, wiring layouts, and parts lists.

**media**- Contains visual assets such as robot photos, design diagrams, wiring schematics, and video recordings.

**software**-  Contains all source code for the EV3 robot. This includes the main control program developed using LEGO Mindstorms, which manages motor control and sensor input to perform tasks and navigate the environment.

> [!NOTE]
> This README.md doesn't contain all the information, some details are inside the folders

## TLGC Robotics Catalyst Team
Our team consists of two dedicated members who carefully manage the key aspects of our autonomous vehicle’s development. Representing Toplink Global College, the Future Engineers Team is a passionate group committed to optimizing the essential electromechanical systems that drive our fully autonomous robot.


**John Matthew G. De Leon**

[![Facebook](https://img.shields.io/badge/Facebook-Follow-1877F2?style=flat&logo=facebook&logoColor=white)](https://www.facebook.com/matthew.deleon.969300)

**Kate Asly S. Gabuat**

[![Facebook](https://img.shields.io/badge/Facebook-Follow-1877F2?style=flat&logo=facebook&logoColor=white)](https://www.facebook.com/kate.gabuat.2025)

> [!NOTE]
> The team information is at the docs folder
# Materials
Our autonomous self-driving car was developed using the LEGO Mindstorms EV3 Education Set (45544), the LEGO Mindstorms Education EV3 Expansion Set (45560), the LEGO Education Spike Prime Set (45678), and the LEGO Education Spike Prime Expansion Set (45681).

![45544-1-0-removebg-preview](https://github.com/user-attachments/assets/7b6e5ab7-0c0d-43d3-89e1-20ac8d9be258) 
<img width="500" height="500" alt="Lego Mindstrom Expansion Set " src="https://github.com/user-attachments/assets/54831924-3041-4191-8ca0-946f1caf6f2f" /> 
<img width="500" height="500" alt="Untitled_design__1_-removebg-preview (1)" src="https://github.com/user-attachments/assets/17d61d32-e4d8-476a-b13b-c25a3b605029" />
<img width="500" height="500" alt="Untitled_design__2_-removebg-preview" src="https://github.com/user-attachments/assets/2fd129e9-4cd0-489d-a3e3-3dafb21b0e60" />

> [!NOTE]
> The list of the materials used in our robot is inside the hardware folder

# Chassis

## Selection Of Wheel
<img width="2048" height="1542" alt="596521804-fbfb1a14-e590-4450-976d-681aac965f25" src="https://github.com/user-attachments/assets/d823c948-3639-4ca7-9778-ef7043c8207b" />

We selected the Wheel 44309 with Rim 56145 at the front and the Wheel 49295 at the rear to optimize our robot’s performance on a mat field. The front wheels are lightweight and have a low friction, narrow profile, which allows for quick, smooth turns with minimal resistance perfect for precise navigation on a smooth surface. Their design supports agile repositioning during autonomous routines where accuracy and responsiveness are critical. This configuration delivers an ideal balance of maneuverability at the front and powerful drive at the back, allowing the robot to move efficiently, accurately, and reliably on a mat based competition field

## Execution of Motors And Its Engineering Factor

### Motor Used For Steering
<img width="2048" height="1542" alt="594414053-a6c4d65e-ab59-4484-84a5-0a2e977df07a" src="https://github.com/user-attachments/assets/1ac0db55-e897-42b9-8a1d-b3b9a9f6fd75" />

The medium motor is small and fast, which makes it perfect for turning the front wheels quickly and smoothly. This helps the robot steer accurately when changing direction or making turns on the mat.

### Motor Used For Power
<img width="2048" height="1542" alt="594414248-f7a48b5f-f4c7-4444-87a5-85981c1d42be" src="https://github.com/user-attachments/assets/1d083879-5234-4376-906b-91fe42a8e205" />

The medium motor at the back gives the robot its main driving power. It provides strong and steady movement, allowing the robot to move with good speed and stability. This setup—steering in the front and power in the back—keeps the robot balanced and allows it to move smoothly, turn precisely, and stay in control on the mat field during the competition.

## Engineering Principle

Based on a simple engineering principle "Use the right tool for the right job". Steering doesn’t need a lot of power instead it needs to be quick and light. That’s why we chose the medium motor. It’s smaller, faster, and helps the robot turn smoothly without slowing it down. Driving the robot forward, on the other hand, needs speed and stability. That’s where the medium motor comes in. It’s more powerful and gives the robot the force it needs to move across the mat with steady speed and control. Putting it at the back also helps the robot stay balanced and keeps the rear wheels from slipping.

This setup follows the principle of separating movement and control we use a light motor for turning and a also a light motor for moving. It makes the robot easier to steer, stronger when driving, and overall more reliable during the competition.

## Execution Of Steering
<img width="1748" height="1542" alt="594416686-4500c59e-d3fb-4212-8533-50a6d324cdd0" src="https://github.com/user-attachments/assets/f1f75765-4633-4745-8326-f916322daeb4" />

Our robot uses a front steering mechanism inspired by the rack and pinion system to control its direction. Instead of a full gear rack, we used a half gear piece connected to a beam. When the gear rotates, it pushes the beam side to side, which turns the front wheels left or right. This setup allows the robot to steer smoothly and accurately, making it easier to change direction on the mat. The system provides controlled and stable movement during turns, helping the robot navigate the field more consistently during competitions.

# Energy and Sensor Management
This section covers the power source of the self driving car and the sensors used to provide it with the necessary information to navigate various challenges. It explains the reasoning behind the selection of each sensor and how they are integrated into the car, along with details on power consumption. A wiring diagram is also included for reference.

## Energy Source
We’ve powered our self-driving car using the EV3 rechargeable battery, which provides a stable energy supply to ensure smooth and consistent operation. This battery serves as the main power source for our robot.

<img width="1335" height="1696" alt="465793506-5939e7b1-b03f-4d41-bfef-d27653e3c9d5" src="https://github.com/user-attachments/assets/2a172dfd-dd81-4514-ac34-a43ca2e60ee4" />

### Ultrasonic Sensor
Our robot uses  one ultrasonic sensors to measure how close it is to the wall of the field. These sensors send out sound waves and wait for them to bounce back. The time it takes tells the robot how far away something is.

<img width="2048" height="1542" alt="594418902-6b72debe-41e1-4fee-8b2b-fb9013fa1f6d" src="https://github.com/user-attachments/assets/d9e710c6-d39a-465f-8784-477d9d4a989a" />

At first, our robot used color sensor which detects colors on the sides of the field to know when to turn. If it detects a color, it would turn in that direction according to the color detected. This method worked at the start, but it wasn’t always reliable sometimes the colors were hard to detect due to lighting or faded markings. To make things more stable, we switched to using an ultrasonic sensor to guide the robot using the wall. This sensor measures how close the robot is to the wall. When it shows the correct distance, the robot stays centered. If it gets too close to the wall, it gently turns to correct itself. This wall following method made the robot more accurate and allowed it to turn smoothly without needing color lines at all.

### Gyro Sensor
<img width="2048" height="1542" alt="594418140-59d89c29-5980-4b46-9f31-eebf243698d9" src="https://github.com/user-attachments/assets/1c4c6fc9-b25c-4438-8220-0dc17f0249f0" />

A gyro sensor is attached, It helps the robot measure how many full turns or laps it has made. One full spin is 360 degrees, so the sensor keeps adding up the angle as the robot rotates. We programmed the robot to stop when it reaches 1100 degrees, which is just a little more than three full laps. This lets the robot turn around smoothly and return close to its starting point. Once it reaches that point, it stops, making sure it doesn’t over rotate or get off track.

### Pixy Camera 
<img width="2048" height="1542" alt="594418416-fad3422c-f138-49a5-b47d-026d1efa0f36" src="https://github.com/user-attachments/assets/cd4b55bd-6bbd-410d-ac02-33bbe63816cf" />

Our robot uses a pixy2 camera helps the robot detect colored objects in front of it. In our setup, it looks for two specific colors: green and red. These colors tell the robot which way to go when it sees an obstacle. If the Pixy2 sees a green object, the robot knows it should turn left. If it sees a red object, the robot will turn right. This helps the robot make quick decisions during the run and choose the correct path based on what color it detects ahead.

### Color Sensor
<img width="4080" height="3072" alt="595103639-ae417665-f607-4bf7-b835-8717617f7f4f" src="https://github.com/user-attachments/assets/be289be1-d90c-47c2-9187-d44cc08807f1" />

A color sensor is attached, helping the robot count laps by tracking colored lines on the track. As it drives, the sensor looks down at the floor to detect when the surface color changes. We programmed the robot to recognize the blue and orange lines, adding a lap to its counter each time it crosses them. This allows the robot to keep an accurate tally of its progress automatically. Once it reaches the target number of laps, it stops right on cue, ensuring it finishes its run precisely where it's supposed to.

# Code & Control Used
<img width="1127" height="578" alt="596419210-d2981cff-b953-4dc6-96d0-b0aa0891b07b" src="https://github.com/user-attachments/assets/31c0f878-8ed2-4523-81b7-1f6551e4b4a5" />

We used Python in Visual Studio Code to program our EV3 robot, managing motor control and sensor input to perform tasks and navigate its environment.


# Code Management
## Open challenge

<img width="1646" height="880" alt="image" src="https://github.com/user-attachments/assets/08d0403d-067c-4cea-a052-5c687eeebaed" />

## Obstacle Challenge

# Engineering Factor
We wanted our LEGO EV3 robot to have vision so it could follow lines, detect colors, and respond to objects. To do this, we used a PixyCam2 smart camera equipped with specialized LEGO firmware.

Because the EV3 uses proprietary ports that aren't natively compatible with the PixyCam's standard interface, we built a custom cable by cutting one end off a regular LEGO sensor cable to expose and splice the internal wires. We then coded the robot in Python, which allowed the EV3 brick to communicate with the PixyCam2 seamlessly, treating it just like any other standard LEGO sensor.


<img width="420" height="594" alt="595108374-e59a5707-6b38-432d-afe1-8f324c9f6016" src="https://github.com/user-attachments/assets/a1d3a76a-2382-45c7-abf4-d10f07a20dd5" />

Next, we attached the those wires to jumper wires compatible with the PixyCam2's small pin port. Referencing the Pixy LEGO firmware documentation, we matched the corresponding power, ground, and data lines, enabling the EV3 to recognize the PixyCam2 as a standard LEGO color or ultrasonic sensor. To prevent short circuits, we insulated the connections using electrical tape or heat-shrink tubing. Because both systems operate on a shared 5V power level, we did not need additional voltage conversion or protective circuitry to make it safe

<img width="433" height="577" alt="595111388-99acb471-f484-4434-b546-ef1eebb13a45" src="https://github.com/user-attachments/assets/6bdfa4cd-5234-4693-809b-9b5038155a83" />

Once everything was connected, our Python script established immediate communication between the EV3 brick and the PixyCam2. The camera continuously streamed real-time data—such as object locations and color signatures—which our Python code processed to dynamically control the robot's motors and actions. With this software-driven integration, our robot was able to follow lines, detect specific color targets, and track moving objects, delivering the high-performance responsiveness of an advanced machine using just a smart camera and LEGO parts.

To physically support this setup, we mounted the PixyCam2 using the small, L-shaped metal bracket that comes with the camera. By fastening it through the built-in screw holes, we were able to lower the camera's point of view, allowing it to focus sharply on the area directly in front of the robot. We manually adjusted the tilt before tightening the screws to lock it into position; even though this mounting setup wasn't motorized, it kept the camera perfectly stable during operation without requiring any extra parts.

# Improvements

We upgraded the robot by switching from a single large motor to two medium motors for driving, which gives the robot better control and a more compact design. We also reduced our setup from two ultrasonic sensors down to just one ultrasonic sensor, making enough physical space to fit both a color sensor and a gyro sensor for better navigation. Regarding the vision system, we moved the camera from the top of the robot to the front, positioning it right above the steering motor for a clearer view. Lastly, we changed the steering wheel to a smaller size and kept the larger rear wheels, giving the robot improved turning precision, better traction, and smoother overall movement on the mat.

# 1

<img width="1920" height="977" alt="595277154-474108b9-01db-4ac6-a90a-78ae508b93c5" src="https://github.com/user-attachments/assets/b20fc9d6-2b52-44e0-ab5c-5418745a9e2c" />
<img width="1920" height="786" alt="595277944-77e89656-e265-4cda-91a9-88b4fc2cec4f" src="https://github.com/user-attachments/assets/be660767-d935-4423-a3e5-1b4594a494d2" />
<img width="1920" height="975" alt="595278541-e171b5dd-8923-4dd2-9b3f-bd833cd16563" src="https://github.com/user-attachments/assets/33d46dac-539e-45ba-a011-e126d31e853d" />
<img width="1920" height="957" alt="595279086-8e07244a-f7e0-48da-b779-4b3fc7239896" src="https://github.com/user-attachments/assets/66c441f5-2d32-4c1d-b9a0-ff913e7d7ef1" />
<img width="1920" height="957" alt="597301863-02ecadeb-1ecf-4c09-b3fb-0b44c70fd7f3" src="https://github.com/user-attachments/assets/a534ebaa-edce-40fa-9aad-79139438701c" />
<img width="1920" height="957" alt="595279374-9bc576e6-3e48-49a7-b212-0bd46aeb0fd8" src="https://github.com/user-attachments/assets/e2483adf-ce1b-40b7-8aef-089bf7834c4d" />



# Credits

We are proud to represent our school (Toplink Global College Inc.), which continues to support our passion for robotics and innovation. We are also deeply thankful to our beloved coach, whose patience, guidance, and encouragement inspired us throughout this journey. Finally, we would like to express our heartfelt appreciation to LEGO Mindstorms for providing the robotics set that made this project possible; the high quality components and flexible design of the EV3 kit allowed us to explore, build, and learn through hands on experience.






