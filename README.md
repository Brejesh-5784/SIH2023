Platform Proximity Project Documentation

1. Overview

The Platform Proximity project involves real-time video processing to enhance platform safety by utilizing advanced computer vision technologies. The system integrates object detection, distance measurement, fall detection, and emergency response protocols to ensure passenger safety and streamline incident management.

2. Technology Stack

Computer Vision Library:
OpenCV: For real-time video processing and distance measurement.
YOLO (You Only Look Once): For object detection.
YOLO Version 8: For optimization.
YOLO Version 4/V4-tiny: For speed and lower GPU usage.
3. System Components

3.1 Real-Time Video Processing
Objective: To process video feeds continuously to monitor platform edges and detect objects.
Tools: OpenCV for video processing; YOLO for object detection.
3.2 Object Detection
Objective: To identify and classify objects near the platform edge using bounding boxes.
Tools: YOLO V6 or alternative versions based on requirements (V4/V4-tiny).
3.3 Distance Measurement
Objective: To measure the distance of objects from the edge of the platform.
Tools: OpenCV for calculating distances.
3.4 Background Subtraction
Objective: To determine accurate train states by differentiating moving objects from the background.
Tools: OpenCV.
3.5 Fall Detection
Objective: To detect passengers falling onto the tracks and trigger alerts.
Tools: Pose estimation model in OpenCV.
3.6 Time Frame for Alerts
Objective: To reduce logistical costs by avoiding alerts if a person returns to Level 0 within a set time frame.
4. Event Categorization and Protocols

4.1 Levels of Alerts
Level 1: Object on the yellow line and within 40% of the edge
Response: Verbal alerts via PA systems in the specific sector.
Level 2: Object between the 40% mark and the edge
Response: More aggressive verbal alerts via PA systems, and the Control Room is alerted with a normal state.
Level 3: Object over the edge of the platform
Response: The control Room is alerted to an emergency state, and nearby personnel are dispatched to assist and rescue.
5. Use Cases

Platform Safety Monitoring:
Continuous monitoring to alert passengers who venture too close to the edge, minimizing accident risks.
Fall Detection and Assistance:
Immediate detection of passengers falling onto tracks and alerts to station personnel and train drivers for swift action.
Emergency Evacuation Support:
Identification of crowded areas to assist in guiding passengers to evacuation routes during emergencies.
Incident Reporting and Investigation:
Documentation and timestamping of incidents for post-incident investigations and security improvements.
Platform Announcements and Alerts:
AI-driven systems trigger announcements and digital signage alerts for safety measures and emergency procedures.
6. Challenges

Blind Spots: Existing CCTV networks may have blind spots that could impact the system’s effectiveness.
Changing Regulations: Adapting to evolving safety and privacy regulations.
CCTV Video Quality: The quality of CCTV video can affect detection accuracy.
GPU Processing: Higher versions of YOLO (e.g., V7) have high GPU requirements, whereas older versions (e.g., V3, V4, V4-tiny) offer lower GPU processing but may have reduced accuracy.

In an intense internal hackathon, my team and I successfully secured a position among the top 10 teams, which was a significant achievement considering the level of competition. Our project was not only technically sound but also innovative, which garnered positive recognition from our mentors. They acknowledged our ability to think creatively, solve problems under pressure, and work effectively as a team.

This experience was particularly rewarding as it highlighted our strengths in collaboration and quick decision-making. The feedback from our mentors emphasized the quality and impact of our work, and their recognition has been a strong endorsement of our potential.

Securing a top 10 spot and earning praise from our mentors has not only been a morale booster but also a key milestone in my professional development. It demonstrates my ability to thrive in fast-paced, competitive environments and to deliver high-quality results, further solidifying my commitment to continuous learning and growth in my field.
