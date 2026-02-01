# Smart AI-Powered Scarecrow System – Requirements

## 1. Introduction
The Smart AI-Powered Scarecrow System is designed to help farmers protect crops from birds and animals using Artificial Intelligence and IoT. The system continuously monitors agricultural fields and automatically triggers deterrent mechanisms when an intrusion is detected.

## 2. Problem Statement
Traditional scarecrow systems are ineffective and require manual monitoring. Farmers face significant crop losses due to birds and animals, especially in rural areas where affordable and automated solutions are limited.

## 3. Objectives
- Detect birds in real-time using computer vision.
- Automatically trigger deterrent actions and produce a deterrent sounds when birds are detected.
- Reduce human effort in crop monitoring.
- Provide a low-cost and scalable solution for farmers.
- Works completely offline. No need for internet services.
- Its just a plug and play , doesn't require any computer or laptop.
- Its portable.

## 4. Functional Requirements
FR1: The system shall capture live video from a camera.  
FR2: The system shall detect birds using a trained AI model (YOLO).  
FR3: The system shall activate a speaker to produce sound when a bird is detected.  
FR4: The system shall rotate a servo motor to simulate scarecrow movement.  
FR5: The system shall operate continuously in real-time.

## 5. Non-Functional Requirements
NFR1: The system should be low-cost and affordable for farmers.  
NFR2: The system should work in outdoor environments.  
NFR3: The system should consume minimal power.  
NFR4: The system should provide fast response (< 2 seconds).

## 6. Use Case
Actor: Farmer  
Scenario:
1. Farmer installs the system in the field.
2. Camera monitors the crops.
3. A bird enters the field.
4. AI detects the bird.
5. Speaker plays sound and servo rotates.
6. Bird is scared away.

## 7. Constraints
- Hardware resources are limited.
- System must be simple to maintain.

## 8. Future Enhancements
- Detection of animals and intruders.
- Mobile app for farmers.
- Cloud-based monitoring dashboard.
- SMS alerts.
