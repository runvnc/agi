# Naive AGI thoughts

Really I should study much more to try to learn about
and understand more of the large existing field of AGI
research.  But I am going to type up some ideas now despite 
that.

## Overview

Aim is to maximize reward and minimize penalty.
Can be supervised and directly rewarded or automatically
reward itself based on goal achievement.

## Simulation

There is a continuous simulation of the world.  Future
reward is predicted by trying out actions and then actions 
leading to the greatest reward are selected.

The simulation is one or more computer programs which are
written and modified on the fly in order to try to match the
predicted sensor data with real sensor data.  At root all
understanding and modelling reduces to patterns of sensor data
or abstractions built from those.

Actions can be taken to test beliefs about the model and 
predictions.  If expected outcomes aren't achieved then the
model is changed.

## What is a pattern

A pattern is an identifiable correspondence of sensor data or
abstractions (which are effectively a special type of sensor data).
Time and sequence are key aspects of sensor data and patterns.

Individual elements of a pattern are not fixed.  However the
relation between the elements is.  Patterns may be fulfilled to
a partial degree.  

Known patterns are selected, permuted and combined to construct 
new patterns, for example for constructing actions or 
simulating to make predictions.

## Pattern compression

Patterns can be stored and generated more efficiently if
they can be represented as algorithms or combinations
of algorithms.

## Simple Example

The agent is a < or > (depending on the way 
it is facing) in a row of characters/spaces.
Reward is R and penalty is P.

P  P  P  >  R R

Each turn the agent receives sensor input and decides
which way to move. It can see one space ahead in the 
direction it is facing.

The agent simulates the world by combining known patterns and
selecting an element of action at random or based on a pattern.
The outcome is played out and if it is favorable compared to
other outcomes then that action is performed.


