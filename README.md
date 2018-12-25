# Continuous Control using Deep Deterministic Policy Gradients



<img src='https://s3.amazonaws.com/video.udacity-data.com/topher/2018/June/5b1ea778_reacher/reacher.gif' align='center'>
In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

    
### Instructions
* Set up your environment: 

	nity has to be installed on your system. Run:
	```
	source ./install.sh
	```

	to install python dependencies. Then you should be able to run jupyter notebook and view navigation_drl.ipynb. 

* Install Udacity's environment



	* To set up your python environment to run the code in this repository, follow the instructions below.

	1. Create (and activate) a new environment with Python 3.6.

	- __Linux__ or __Mac__: 
	```bash
	conda create --name drlnd python=3.6
	source activate drlnd
	```
	- __Windows__: 
	```bash
	conda create --name drlnd python=3.6 
	activate drlnd
	```

	2. Follow the instructions in [this repository](https://github.com/openai/gym) to perform a minimal install of OpenAI gym.  
		- Next, install the **classic control** environment group by following the instructions [here](https://github.com/openai/gym#classic-control).
		- Then, install the **box2d** environment group by following the instructions [here](https://github.com/openai/gym#box2d).

	3. Clone the repository (if you haven't already!), and navigate to the `python/` folder.  Then, install several dependencies.
	```bash
	git clone https://github.com/udacity/deep-reinforcement-learning.git
	cd deep-reinforcement-learning/python
	pip install .
	```

	4. Create an [IPython kernel](http://ipython.readthedocs.io/en/stable/install/kernel_install.html) for the `drlnd` environment.  
	```bash
	python -m ipykernel install --user --name drlnd --display-name "drlnd"
	```

	5. Before running code in a notebook, change the kernel to match the `drlnd` environment by using the drop-down `Kernel` menu. 

	<img src='https://user-images.githubusercontent.com/10624937/42386929-76f671f0-8106-11e8-9376-f17da2ae852e.png'>


## Run
Follow the instructions in Continuous_Control.ipynb to get started with training the agent.
