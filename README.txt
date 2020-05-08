*******************************************************************
This code was developed for Coursework Part 2: Racetrack coursework
as part of CM50270 Reinforcement Learning module university of Bath
*******************************************************************

#purpose
The model aim to solved Racetrack environment 
by using 3 reinforcement learning agents consist 
of On-Policy First-Visit Monte-Carlo, SARSA ,
and Q-Learning. The agents need to be able to 
drive the car as fast as possible while still
maintain the car in the track

#detail of environment
The environment was implemented (racetrack_env.py)
by memeber of univeristy of Bath as part of coursework
in Reinforcement learning course which is inspried from 
Reinforcement Learning, Sutton & Barto, 2018, Exercise 5.12
The figure of environment can be found in "track_big.png"

#state representation
The state is a list of 4 items which are position and 
velocity for x an y axis

#reward
The agent will gain reward of -1 for every timme step
and get reward of -10 if the car fall off the track

#termination condition
The episode end only if the agent reah the goal
If the agent fall off the track, the agent return
to the starting possition which are randomly selected
across the starting line

#############################################
The code are sepearted into 3 part
1.On-Policy First-Visit Monte-Carlo
2.SARSA
3.Q-Learning
#############################################

#parameter used in model
gamma=0.9
alpha=0.2
epsilon=0.1
gamma=0.9
alpha=0.2
epsilon=0.1
num_episode=150

