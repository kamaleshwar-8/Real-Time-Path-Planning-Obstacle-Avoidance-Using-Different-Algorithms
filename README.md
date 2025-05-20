## Overview

This repository contains the implementation of a real-time, autonomous robotic navigation system capable of efficient path planning and obstacle avoidance in a grid-based environment. Built using the ESP32 microcontroller, the robot interfaces with a Wi-Fi-enabled HTTP server, allowing users to remotely issue commands, define destination coordinates, and select navigation algorithms through a web interface. The video shows live navigation of the robot and the images show the results of some path planning algorithms.

## Key Features

- Multiple Path Planning Algorithms: Implementation of A* (A-Star), Breadth-First Search (BFS), Viterbi, Probabilistic Roadmap (PRM), Q-Learning, and Rapidly-exploring Random Tree (RRT)
- Web-Based Control Interface: Wi-Fi-enabled HTTP server for remote command issuing, destination selection, and algorithm choice
- Real-Time Obstacle Avoidance: Dynamic navigation around obstacles placed in the environment
- Grid-Based Movement: Discretized grid layout navigation with step-wise movement and orientation correction
- Visual Monitoring System: Browser interface displaying current position, direction, and selected algorithm

## Results

![A*](https://github.com/user-attachments/assets/de2e400a-b3e7-45f7-bb68-93a9f9cf2a86)


![PRM](https://github.com/user-attachments/assets/6062fb0d-a016-4ee3-bfb4-1208d1dc0cb2)




https://github.com/user-attachments/assets/3c67320d-8280-4ce8-9c4c-c902043b8a61

