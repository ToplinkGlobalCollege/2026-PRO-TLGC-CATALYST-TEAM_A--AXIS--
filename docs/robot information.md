# Robot info
<img width="1024" height="768" alt="Axis_new" src="https://github.com/user-attachments/assets/185d9d19-7d39-4c91-9bef-6c0cffe624e1" />

**Name:** Axis 

**Weight:** 0.6 kg

**Size:** 215mm x 140mm with 225mm in height


> [!NOTE]
> Ever wonder why we chose the name Axis? It’s far more than just a name on a robot. For us, Axis is the central point where our backgrounds meet, our team unites, and what we aim to do as a team.

# A short trivia!
The Meaning of "Axis"
​In mathematics, an axis is a straight line used to reference coordinates, establish balance, and guide geometric direction. It plays a vital role, it doesn’t just exist in space, but it makes movement accurate, balanced, and perfectly aligned.

​But over time, the meaning of the word “axis” has grown far beyond graphs and geometry. In modern usage, especially in engineering, leadership, and life, an axis is:

​“A central support, a pivotal point, or a driving force that keeps everything aligned and moving forward.”

​In this context, an axis can be a core principle that guides a team, a focal point that unites different ideas, or a standard of precision that defines how things are done. An axis is something that holds the center, maintains perfect direction, and ensures steady progress, without needing to take the spotlight.

​So why did we name Our Robot Axis?

​First, it reflects our identity. ​Our team, TLGC Catalyst, proudly carries our heritage into the world of technology. In Filipino culture, we value strong foundations that keep us grounded and moving together as one. The name "Axis" was directly inspired by the mathematical concept because of how our robot drives: in a flawless, unwavering straight line. Naming our robot “Axis” connects our engineering journey to our local roots, reflecting the Filipino spirit of resilience, absolute discipline, and a clear, straight path forward.

​Second, it reflects our mission.

​We began training in April 2026, just two months ago. In that short time, we’ve learned, built, and grown rapidly. Like a true axis, our robot symbolizes stability under pressure, intelligent problem solving, and the ability to act as the pivot point for transformation in ourselves, in our community, and in the world of robotics.

​Driven by Precision

​Axis is not just a machine. It is a symbol of alignment, a driver of innovation, and a promoter of precision. Just as a mathematical axis gives order and direction to an entire dimension, our robot is designed to make systems smarter, paths straighter, and ideas come to life.

​With Axis, we don’t just move we align.
We don’t just wander we drive the way forward.

# Mobility

## Drive System Used
Our EV3 autonomous car uses two Medium Motors to drive forward, with each motor independently powering a main wheel. This dual-motor setup provides consistent speed for straight movement while allowing us to precisely control steering by varying the speed of each motor. By utilizing Medium Motors instead of a single Large Motor, the car gains a more compact design and faster rotational response, making it highly agile. Additionally, the built-in rotation sensors in both motors help us measure exactly how far each wheel rotates, allowing for precise tracking, smoother turning, and highly accurate autonomous navigation.

## Turning Strategy
Our EV3 robot uses a custom rack-and-pinion steering mechanism for the front wheels. Instead of a traditional gear rack, we attached a half-gear element to a beam to act as a simplified rack. When driven by the motor, this gear translates the beam laterally, pivoting the front wheels left or right. This mechanical linkage provides smooth, proportional steering, enhancing maneuverability and stability during precise turns and alignment tasks. By simplifying the setup, we reduced mechanical complexity while ensuring reliable performance during runs.

## Motors Used
### Medium Motor
<img width="333" height="333" alt="597100100-c9c5783b-2a71-4b0c-8473-82a2a08ac405" src="https://github.com/user-attachments/assets/e8fadf56-2edd-4755-9561-5e4595f5cc35" />

## Why we chose this system
We used two Medium Motors to drive our robot because they are compact, lightweight, and provide plenty of power when working together. Instead of using a separate motor just for steering, this dual-motor setup drives both wheels independently to move the robot smoothly across the mat and ensure precise straight driving. The Medium Motors are smaller and quicker than the Large Motor, which keeps the robot from becoming too heavy or bulky while still offering incredible control during turns. This combination of two agile motors helped make our robot both powerful and easy to maneuver.

# Power System
## Main Power Source
We’ve powered our self driving car using the EV3 rechargeable battery, which provides a stable energy supply to ensure smooth and consistent operation. This battery serves as the main power source for our robot.
<img width="1335" height="1696" alt="465793506-5939e7b1-b03f-4d41-bfef-d27653e3c9d5" src="https://github.com/user-attachments/assets/c4625758-a31d-4f06-9d3d-d635932a5730" />

## Voltage and Current Details
Our EV3 robot is powered by a 7.2V rechargeable lithium-ion battery with a 2050 mAh capacity. This allows it to deliver 2.05 amps of current for a full hour, though actual runtime varies based on the robot's power consumption. The battery simultaneously powers the EV3 brick, motors, and sensors while maintaining a stable voltage for consistent performance. Compared to disposable batteries, this rechargeable option is far more convenient and cost-effective, making it ideal for extended practice sessions and competitions.

## Power Safety & Management
To ensure the EV3 robot's safety and reliability, we implemented strict power management and insulation protocols. The rechargeable battery was fully charged before each run, and the EV3 brick was powered down immediately after use to conserve energy and prevent overheating. Additionally, we applied insulating materials to key connections, eliminating the risk of short circuits or accidental contact with exposed wiring. These proactive measures protected both the hardware and the team, ensuring the robot remained stable and competition-ready.

# Obstacle Avoidment

## Sensors Used for Detection
### Pixy Cam 2
<img width="645" height="634" alt="597102144-5753737b-6624-4d70-8d01-149ea59d3588" src="https://github.com/user-attachments/assets/b6dd1ca9-e413-4725-981c-38c08d7ff4fc" />

To improve our robot’s ability to detect visual markers and environmental cues, we mounted the Pixy Cam at the front of the robot, positioned directly above the ultrasonic sensor. This elevated position gives the camera a wider field of view, allowing it to detect obstacles from a greater distance and with fewer blind spots. Placing the camera higher also prevents it from being blocked by parts of the robot’s frame, which improves both its accuracy and response time during object recognition.

For navigation, we mounted the ultrasonic sensor and the Pixy Cam onto a single axle that is connected to a medium motor, allowing the robot to actively scan its surroundings by turning the sensors left, right, or straight ahead. This strategic configuration enables a single sensor to measure both forward and side distances to nearby walls without the added weight of multiple sensors. As a result, the robot receives reliable and consistent environmental data, helping it stay centered in narrow paths or corridors. By dynamically rotating the sensor assembly to compare left and right distance values, the robot can make precise steering adjustments to maintain a straight, balanced course critical for avoiding collisions and achieving consistent lap performance.

