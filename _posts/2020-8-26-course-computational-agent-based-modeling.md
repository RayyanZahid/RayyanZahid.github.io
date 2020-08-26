---
classes: wide
title:  "Course review: Computational"
excerpt: 
published: false
---

### What is a model?
A model is an abstracted description of a process where certain aspects of the process being modeled is either exaggerated or ignored for the sake of some other features.

Conceptual models are usually designed by researchers (the author) to simulate real worlds. This conceptual model is constructed by the developer.

> Essentially, all models are wrong but some are useful. - George Box, 1987

The right representation can often be the key to understanding a phenomenon. Using this understanding, we can solve difficult problems, communicate results effectively and discover new questions that lead to deeper and other fundamental problems.

This is really handy when dealing with complex systems which are composed of multiple interacting parts connected in complex ways.

Historically we have used two ways to build our scientific understanding of the world. In induction, we infer data sets to come up with a general theory and in deduction we argue from first principles to get to a general theory. However, just in the last few decades, a third way of science has emerged.

Axelrod in 1997 argued in his paper "Advancing the Art of Simulationin the Social Sciences: Obtaining, analyzing, and sharing results of computer models" that simulation is a third way of science. In this new way we use our first principles to create a data set than can create a general theory. More formally, we call this generative.

When dealing with complex systems, we are seeking an understanding for when one or both of the following two scenarios are unknown. The aggregate emergent behavior of a system or the local interactions of a group.

Agent Based Modelling (ABM) can help find the answers through generative design. They work best when there are a moderate number of heterogeneous components. The interactions between the parts are complex and are history and property dependent. Individual have no knowledge of the global state of the system and the environment the system operates in is rich (perhaps be a composition of other parts).
In most cases time is a necessary condition and if there is adaptation, then it is a sufficient condition to choose an agent based model.

### Agent and Agent based modeling
An **agent** is an autonomous individual element with properties and actions in a computer simulation.

**Agent based modeling** is an idea that the world can be modeled using agents, an environment, and a description of agent-agent and agent-environment interactions. It is about process. Environments are about pattern.

### The history: functional programming and OOP
Initially, functional programming was simply about taking a number as an input, performing some operation, and then returning a number as an output.

Thanks to John McCarthy's (1958) efforts, a new programming language called LISP was created that was based on Lambda Calculus (1932). LISP could take data and functions as input to produce an output.

Dahl & Nygaard created Simula with "Class" which combined functions and data. Smalltalk created by Alan Kay and colleagues included the first notion of objects.
The similarity between Agent Based Modeling and Object Oriented programming is that agents and objects both are instantiated as classes.

Inspired by Seymour Papert and Alan Kay, Carl Hewitt in 1973 simplified Simula and Smalltalk and created what is known as the Actor model. The
In the Actor model each actor can send/receive messages, create another actor or manipulate messages. The actors run concurrently and need to know the exact address of the other actor to communicate.

Agent based modeling follows a similar paradigm, where agents run concurrently and have knowledge of only their own local interactions and bounded interaction spaces. Agents are dynamic, exhibit behaviors and are independent of other agents.

We are trying to model various dynamics. We find phase transitions, build visualizations, and check for sensitivity.

When modeling, a concept can either be planned first as a flow chart or a pseudo code.

### Components
There are three components to an agent based model. Agents, interaction and environment.

#### The Agent
An agent have properties that are fixed, based of a distribution or variable. It can perform actions that can be standard or user-defined. And collections or groups can be set of various kinds.

#### The Environment
There are multiples types of environments that can be used. Discrete, continuous or externally imported environments. These environments can be confined in a Toroidal/wrapped/Pac-Man, bounded or infinite plane arrangement.

The topology of the plane can be
* 3-dimensional
* Geographical Information system
* Network based environment
  * Grid network
  * Scale-free/preferential attachment
  * Random
  * Small world
  * Real world data
* Spatial environment:
  * Discrete Lattice spaces such as Square (Von Neumann and Moore) or Hex (equal length)
  * Continous spaces

#### Interactions
* Agent-agent
* Agent-environment

### Verification and validation of a model
#### Verification
As previously mentioned, verification is usually done between an authors conceptual model and the developers constructed model.

Many standards are maintained to ensure that the implemented model follows the conceptual model.

Proper documentation, programmatic testing and test cases/scenarios all manage the quality.

* There are multiple ways we can conduct programmatic testing:
  * Unit testing: Functional code tested separately
  * Code walkthroughs: Examined in a group setting
  * Debugging: Execution step by step
  * Formal testing: Verification using formal logic
  * Sensitivity analysis through spanning the behavior space

* Test cases can be done in the following ways:
  * Corner cases: Extreme values
  * Sampled cases: Subset of parameters to discover behavior
  * Specific scenarios: Relationship between inputs and outputs

##### Reasons for failure
* Bugs
* Miscommunication
* Emergence

##### Benefits of verification
* Aids in understanding
* Micro-rules lead to Macro-rules
* Validation
* Implemented model corresponds to the real world
