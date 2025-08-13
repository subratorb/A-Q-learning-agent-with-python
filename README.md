# Interactive Q-Learning Grid World Explorer
https://subratorb.github.io/A-Q-learning-agent-with-python/ Check web demo
This project is a single-page interactive web application that visualizes the Q-learning reinforcement learning algorithm. It provides a hands-on experience for understanding how a Q-learning agent learns to navigate and solve a grid world environment.

The application is built to serve as an interactive companion to an academic report, bringing the theoretical concepts and experimental results to life through a dynamic and explorable interface.

## Features
Grid World Environment: A visual representation of the agent's environment, highlighting the start, goal, jump, and obstacle cells.

Algorithm Explanation: Clear and concise descriptions of key Q-learning components, including the Q-Table, Epsilon-Greedy strategy, and the learning rate's role in the update rule.

Live Simulation: A dynamic training ground where you can run a Q-learning agent simulation in real-time.

Hyperparameter Control: Interactive sliders to adjust critical hyperparameters such as the Learning Rate (α), Discount Factor (γ), and Initial Epsilon (ϵ).

## Visualization of Learning:

State Value Heatmap: A Chart.js matrix chart that dynamically updates to show the learned value of each state as the agent trains.

Cumulative Reward Chart: A line chart that plots the cumulative reward obtained in each episode, demonstrating the agent's overall learning progress.

## Getting Started
To run this project, simply download the index.html file and open it in any modern web browser. All dependencies (Tailwind CSS, Chart.js) are loaded via CDN, so no installation or build process is required.

## Usage
The application is divided into three main sections, accessible via the navigation buttons at the top:

The Environment: An overview of the grid world. Hover over the cells to see their properties.

The Algorithm: A breakdown of the core concepts of Q-learning.

Training Ground: This is the main interactive section.

Use the sliders to set your desired values for Learning Rate (α), Discount Factor (γ), and Initial Epsilon (ϵ).

Click the "Run Simulation" button to start the training process.

Observe the live agent movement, the updating heatmap, and the reward chart to see how your chosen hyperparameters affect the learning outcome.

Click the button again to pause or resume the simulation.

## Technologies Used
HTML: For the document structure.

Tailwind CSS: For a clean, modern, and responsive user interface.

JavaScript: Vanilla JavaScript for all application logic, state management, and DOM manipulation.

Chart.js: For generating the real-time line and matrix charts.

## Acknowledgment
This project is a practical implementation based on the COM762_CW2 assignment brief, focusing on providing an interactive and educational experience for understanding Q-learning.
