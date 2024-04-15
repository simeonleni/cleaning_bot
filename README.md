# Home Cleaning Robot Navigation System

## Overview

This project is about making a smart navigation system for a home cleaning robot. The robot should be able to clean all parts of a house efficiently, avoiding obstacles like furniture.

## Project Structure

### 1. Modelling the Environment

We use a grid-like map to represent the robot's environment. Each square on the grid is a small part of the floor where the robot can go. We also define where the robot can be and what it can do, like moving forward or turning.

### 2. Cost Function and Heuristic

We figure out how much effort each action takes for the robot. For example, moving over carpet might be harder than on a hardwood floor. We also use a smart guess (heuristic) to help the robot plan its route quickly.

### 3. Implementation and Testing

We write code using the A* search method to find the best way for the robot to clean the entire house. Then, we test this code with different house layouts to see how well it works.

### 4. Visualization

We create a tool to show how the robot moves around the house and cleans. This helps us understand if our plan is working and if the robot is efficient.

## How It's Done

I've used Jupyter Notebook to organize and describe my code step by step. It's like writing a story about how the robot navigates and cleans.

## Contribution

If you have ideas or improvements for this project, feel free to share them. Your input can make the robot even better at cleaning homes!
