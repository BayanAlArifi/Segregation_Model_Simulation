# Segregation Model Simulation

## Table of Contents
- [Introduction](#intro)
- [Simulation](#simulation)
- [Observation](#observation)


<a id='intro'></a>
## Introduction
A Study of Social Networks and Emergent Behaviour, where a simulation experimentation inspired by Thomas Schelling’s Segregation Model for social systems is carried out. The NetLogo tool is used to simulate and model the behaviour of two types of people looking for the right neighbourhood, with the orange agents (turtles) representing those individuals that want neighbours who have kids, and blue agents representing those who do not.


<a id='simulation'></a>
## Simulation
The below figure shows a screenshot of the NetLogo simulation interface. The orange agents and blue agents get along with one another. But each agent wants to make sure that it lives near some of “its own”. That is, each family with children wants to live near at least some families that have children, and each families or singles who do not want kids, want to live near at least some people like them. The simulation shows how these individual preferences ripple through the simulation view over time, leading to segregation patterns.

![image.png](https://github.com/BayanAlArifi/Segregation_Model_Simulation/blob/master/Figures/fig1.png)


<a id='observation'></a>
## Observation
The agents are randomly distributed around the neighbourhoods, and are of equal numbers as in the figure below in **A**. In each step (iteration), each agent best responses by looking at its eight neighbours, what they are doing, and if less than half are of its kind, it moves to a randomly empty location in another neighbourhood. Hence, every person chooses the best response, based on its knowledge of the
other opponents’ decisions. They move around until there is at most one agent on a patch, where each agent is happy with its neighbourhood. If agents do not have enough neighbours that have children, they jump to a random nearby empty patch. The number slider shown in Figure 14 controls the total number of agents. The %similar monitor shows the average percentage of the similar neighbours for
each agent. It starts at 50%, since each agent starts on average with an equal number of blue and orange agents as neighbours. The %unhappy monitor indicates the percent of agents that have fewer similar neighbours than they want, and thus would want to move. Both monitors are also plotted as shown in the figure below in **C**.

![image.png](https://github.com/BayanAlArifi/Segregation_Model_Simulation/blob/master/Figures/fig2.png)
