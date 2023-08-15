# Multi-Agent PPO Learning Project

[Video Showcasing Project](https://youtu.be/GQbMosjD7x8)

## About
This project was developed as a final project for the course CS 4756 Robot Learning. For the assignment, I was paired up with another student in the class ([@triple-jay](https://github.com/triple-jay)) and together we tried to tackle one of the many open problems in robot learning today. In particular, we chose multi-agent reinforcement learning or MARL for short. Essentially, whereas as reinforcement learning normally focuses on a single agent acting in an environment, MARL expands this definition to include more than one agent.

The specific technique we tested was OpenAI's Proximal Policy Optimization algorithm (PPO). It is a policy gradient method that controls how "fast" the policy can change by clipping the gradient if it gets too large. For a more in-depth explanation, please see the final report included in this repo. We extended the PPO algorithm from the single-agent to multi-agent setting and examined its effectiveness. Again, see our report for the results.

This project required both applying the fundamentals of robot learning taught in class and doing extensive research into papers and online articles. It was coded entirely inside of a Jupyter Notebook using Python and PyTorch. All of our experiments were performed in the multi-agent virtual environment [PettingZoo](https://github.com/Farama-Foundation/PettingZoo).

## Why MARL?
Why MARL? As robot learning advances and robots become increasingly more commonplace, MARL is critical to ensure that the robots can effectively cooperate with each other. In the future, MARL techniques can control drone swarms to coordinate search and rescue efforts and help self-driving cars communicate with each other safely.

## Setup
Setup is simple for this project. To run it, simply upload the notebook to Google Colab and voila! You should then be able to run all the code sections from top to bottom. We recommend using Google Colab as it is a free service to all users with a Google account. It also comes pre-installed with some of the dependencies like Python, PyTorch, and NumPy. However, if you wish to speed up some of the training times using premium GPUs, then you will need to subscribe to Colab Pro. You can also run the Jupyter Notebook using other software, but be aware that you will have to install the dependencies (like PyTorch) yourself.
