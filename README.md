# Connect-4-RL
The goal of this project was to learn how to extend Python with C++ functions.
Specifically, I implemented Connect 4 in C++, and created a Python environment wrapper that directly calls the C++ functions.
This approach combines the speed of C++ with the simplicity of Python. I have only implemented DQN (Deep Q-Network) thus far. The environment
supports the implementation of any Reinforcement Learning algorithm (in Python).

This project assumes that you use Visual Studio: it has been tested with Visual Studio 2019. 

Requirements:
* Visual Studio 2019
* Boost 1.69
* Python 3.6
* Python packages listed in requirements.txt

You will need to link the Boost and Python include and lib directories. 
