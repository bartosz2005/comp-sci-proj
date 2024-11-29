# README for Derivative Learning Game

## Overview

This project is an interactive game built using Python's Pygame library that helps users learn about derivatives and practice differentiation through a simple user interface. The game includes a learning module that explains the concept of derivatives and a practice module where users can differentiate a given function.

## Features

Learn about Derivatives: Provides a definition and explanation of derivatives.
Practice Problems: Users can practice differentiating functions and receive feedback on their answers.
Graphing Functions: Visualize functions and their derivatives using Matplotlib.
User Interface: Simple and intuitive interface with buttons for navigation.

## Requirements

- Python 3.x
- Pygame
- Matplotlib
- NumPy
- SymPy

## Installation

Clone the repository or download the code files.
Make sure you have Python installed on your machine.
Install the required libraries using pip:

```bash
pip install pygame matplotlib numpy sympy
```
##Usage

1. Run the game by executing the main Python file:
```bash
python final.py
```
2. Navigate through the main menu to choose between learning about derivatives or practicing problems.
3.In the learning module, read the provided definitions and explanations.
4.In the practice module, differentiate the given function and submit your answer.
5.Receive immediate feedback on your answer.

## Code Structure

- **Button Class**: Handles button creation, rendering, and interaction.
- **InputBox Class**: Manages user input for answers.
- **Main Menu**: Displays the main menu options for learning and practicing.
- **Learning Function**: Displays information about derivatives.
- **Practice Function**: Presents a differentiation problem and checks user answers.
- **Plotting Function**: Visualizes the function and its derivative using Matplotlib.

## Example

When you choose to learn about derivatives, you'll see a definition and explanation. If you choose to practice, you'll be prompted to differentiate a specific function (e.g., f(x) = 3x^3 - 5x^2 + 2x - 7) and input your answer.
