#Adrishya

Adrishya is an AI-powered assistive smart cap designed to help visually impaired people better understand their surroundings, navigate safely, and move more independently.

The system combines a 180° rotating camera, ultrasonic sensors, computer vision, AI-based object detection, risk assessment, navigation, voice guidance, and directional haptic feedback into a single wearable system.

Key Features
1. Environmental Perception

A rotating camera scans the user's surroundings and captures real-time visual information. The system can detect objects such as:

People and children
Cars, buses, motorcycles, and cyclists
Animals
Traffic signs and signals
Obstacles and environmental hazards
2. Intelligent Risk Assessment

Adrishya is designed to avoid simply announcing every detected object. Instead, detected objects can be analyzed based on factors such as distance, movement, and relevance to the user's path.

This allows the system to prioritize potential hazards and provide alerts when they are important.

3. Safe-Path Guidance

The system analyzes the area in front of the user to determine whether the walking path is clear or blocked. When possible, it can recommend a safer direction.

Left vibration → move/consider moving left
Right vibration → move/consider moving right
Both/strong warning → path may be blocked; stop and reassess

If a safe direction cannot be determined, the system should prioritize warning the user rather than making an uncertain navigation decision.

4. Ultrasonic Obstacle Detection

Ultrasonic sensors provide an additional layer of close-range obstacle detection. This complements the camera-based perception system, particularly for nearby objects.

5. Voice Guidance

Important information can be communicated through voice, such as:

"Obstacle ahead."
"Move left."
"Path blocked."

The system is intended to prioritize important alerts and reduce unnecessary repeated announcements.

6. Navigation

Adrishya is designed to work with map-based navigation so that users can travel toward a selected destination while receiving environmental warnings and directional guidance.

7. Health Monitoring

A planned health-monitoring feature can monitor heart rate and, when a predefined critical condition is detected, trigger an emergency notification to a designated family member or contact.

Technology

The current software development focuses on:

Computer Vision
RF-DETR object detection
Grounding DINO for open-vocabulary hazard detection
Depth estimation
Object tracking and motion analysis
Risk assessment
Walkable-path analysis
Safe-direction planning
Voice guidance

The initial development and testing are being carried out using a laptop and webcam, with the system intended to later be adapted to portable hardware.

Project Status

Adrishya is currently under development. The core perception foundation is being developed first, followed by depth estimation, tracking, risk assessment, safe-path planning, navigation, and the final wearable integration.
