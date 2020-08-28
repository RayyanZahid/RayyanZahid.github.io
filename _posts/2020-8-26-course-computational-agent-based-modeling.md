---
layout: post
title:  Course review: Computational Modeling and NetLogo
date:   2020-08-27
author: Rayyan Zahid
description: My take away from "Computational Modeling and NetLogo" offered by the Santa Fe Insitute. The course introduced the basics of agent based modeling of complex problems.
featured-image: 2020-8-26-course-computational-agent-based-modeling/ABM BK.jpg
featured-image-alt: Alt texts
categories: Modeling
---
![Featured image](/assets/images/2020-8-26-course-computational-agent-based-modeling/ABM BK.jpg)
  
The course "Computational Modeling and NetLogo" was offered as a summer course by the Santa Fe Institute as an introduction to the basics of agent based modeling of complex problems and NetLogo programing. Having missed the course during the summer, I decided to take the audited course.

This article is a condensed summary of what I learned about computer modeling. I've omitted the basics on NetLogo since I only wanted to talk about the broader encompassing topics of modeling. NetLogo is, nonetheless, a wonderful and powerful programming language which I've lately been having a lot of fun with.

The instructor for this course was Dr. Bill Rand:

| The Instructor           | Description                                                                                                                                                                                                                                                                                                                                  |
|--------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![Bill-rand](/assets/images/2020-8-26-course-computational-agent-based-modeling/Rand-Bill.jpg ) | Bill Rand is the assistant professor of Business Management at the Poole College of Management at North Carolina State University and a computer scientist by training. He recently co-authored a textbook on agent-based modeling with Uri Wilensky, the author of the NetLogo programming language. |

In this course the instructor helped the students explore why agent-based modeling (ABM) is a powerful new way to understand complex systems. ABM was and is used in the past and present to study everything from economics to biology to political science to business and management.

Furthermore, the course not only taught how to build models from the ground up using NetLogo programming Language but it also taught how to analyze and understand the results of a model. For brevity I have skipped the NetLogo part in this article, and rather kept the methods that is useable in any number of different fields.

### What is a model?
A model is an abstracted description of a process where certain aspects of the process are either exaggerated or ignored to understand the subject of the study.

In practice, the conceptual model is designed by the researchers (also known as the authors) who are simulating some aspect of the real world. The conceptual model is then implemented by a developer, who constructs the program using a flowchart or a pseudocode provided by the author. For the proper implementation of the conceptual model, it is important to reduce the communication gap between the author and developer. Modeling tools such as NetLogo, which has a "low threshold and high ceiling", do this by having a human-centered design, intuitive programming language and strict documentation standards.

### Representation

> Essentially, all models are wrong but some are useful. - George Box, 1987

All other challenges aside, for a model, having the right representation can sometimes be the difference between understanding a phenomenon or getting lost in it. With the right representation we can solve many difficult problems, communicate our results effectively and ultimately discover new questions that lead us towards acquiring a deeper insight. 

Representation is the name of the game when dealing with complex systems.

### Complex Systems

> Every real world system is inherently complex. - Tamas Vicsek, 2002

Complex systems are composed of multiple interacting parts that are all connected in complex ways at different levels and scales.

Historically we have used two ways to build our scientific understanding of the world: induction and deduction.

#### Induction, deduction & the third new science

Induction is when we infer from data sets to come up with a general theory. Deduction is when we argue from first principles to get to a general theory. However, in the last few decades, a third new way of science has emerged, simulation or generative.

Axelrod in 1997 argued in his paper "Advancing the Art of Simulation in the Social Sciences" that simulation is a third way of science. In simplified terms, this new way of science, just like in deduction, we argue from first principles but instead of coming up with a general theory, we creates sets of datasets from the principles. We then use induction to infer from the dataset a general theory. We call this simulation or generative reasoning.

#### Complex systems and simulation

When we deal with complex systems, we are often seeking an understanding where deductive, inductive, or both these ways have failed to provide an answer. Simulation uniquely helps us understand the aggregate emergent behavior of a system (**integrative** ) and actual first principles of the aggergate pattern (**differential**).

### Agent and Agent based modeling

Agent Based Modelling (ABM) is one of the ways we study complex systems. It is exclusively a simulation technique.

#### What is ABM?
**Agent based modeling** is an idea that the world can be modeled using agents, an environment, and a description of agent-agent and agent-environment interactions. It is about the process and the patterns it forms in its environment.

#### What is an agent?
An **agent** is an autonomous individual element with properties and actions in a computer simulation.

#### How do we know when to use ABM?

There are few properties of the system that indicate that ABM is useful to gain an insight.

A moderate number of heterogeneous components, interactions between different parts are history and property dependent; often in complex ways. Individuals have no knowledge of the global state of the system and the environment the system operates in is rich in features (sometimes a composition of other parts as well).

In almost all cases time is a necessary condition to use ABM. Though not necessary on its own, agent based modeling is usually the best technique when the components are exhibiting adaptation.

### The history: functional programming and object oriented programming

Initially, functional programming was all about taking a number as an input, performing some state operation on it, and then returning a number as an output.

Thanks to John McCarthy's (1958) efforts, a new programming language called LISP was created that was based of Lambda Calculus (1932). LISP was not only able to take data as an input, but also functions aswell.

Dahl & Nygaard created the concept of "Class" in Simula, which combined functions and data. Smalltalk created by Alan Kay and colleagues brought the first notion of objects in programming.

The similarity between Agent Based Modeling and Object Oriented programming is that agents and objects both are instantiated as classes.

Inspired by Seymour Papert and Alan Kay, Carl Hewitt in 1973 simplified Simula and Smalltalk to create what is known today as the **Actor model**.
In the Actor model each actor can send/receive messages, create another actor or manipulate messages. The actors all run concurrently and in order to send a message to another actor, need to know the exact address of the other actor to communicate.

### Bridging the gap

Agent based modeling follows a similar framework. Agents can run concurrently and only have knowledge of their own local interactions and bounded interaction spaces. Agents are dynamic and exhibit behaviors that are independent of other agents.

When look at the dynamics of the model, ABM studies the system using visualizations and sensitivity analysis. ABM often exhibit phase transitions, that is when a small change in the input parameter dramatically changes the output.

### Components
There are three components to an agent based model. Agents, interaction and environment.

#### The Agent
An agent have properties that can either be fixed, based off some distribution or are variable. Ations that can be performed are usually standardized but can be user-defined if needed. Since we are dealing with moderate numbers of agents, collections or groups of agents is usually part of the feature set.

#### The Environment

There are alot of properties that we can be configured for an environment. Space, boundary and topology are some of them.

**Space:**
* Discrete
* Continuous
* Externally imported environments

**Boundary:**
* Toroidal/wrapped/Pac-Man
* Bounded
* Infinite plane arrangement.

**Topology:**
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

### Interactions
* Agent-agent
* Agent-environment

### Verification and validation of a model

A model is **verified** when the implemented model corresponds to the conceptual model.

Many standards are maintained to ensure that the implemented model follows the conceptual model. Proper documentation, programmatic testing and test cases/scenarios all manage to maintain the quality of the implemented model.

* **Documentation:**
  * What is the model
  * How does the model work
  * How can a user use the model
  * What aspects should the user notice
  * What variables should the user vary
  * Additional ways to expand the model
  * Other similar models
  * Credits and references

* **Programmatic testing:**
  * Unit testing: Functional code that is tested separately
  * Code walkthroughs: Code that is examined in a group setting
  * Debugging: Execution of the program in step by step manner
  * Formal testing: Verification of the model using formal logic
  * Sensitivity analysis by spanning the behavior space

* **Test cases:**
  * Corner cases: Test for extreme values
  * Sampled cases: Create a subset of parameters to discover new behavior
  * Specific scenarios: Find the relationship between inputs and outputs
  
  A model is **validated** when the implemented model succesfully simulates the real world. 

### Failure of a model

There are multiple reasons why a model can fail. Some of the likely reasons are as follows:

* Bugs: Error in the implemented code
* Miscommunication: Misrepresentation of the conceptual model in the implemented model
* Emergence: The conceptual model is correct, but expected results were incorrect or that the implemented model displayed behaviour that could not have been predicted in the first place.

#### Benefits of verification

There are other unique benefits of verification.

* Aids in understanding: A better in-depth understanding is often derived from conducting verfication
* Micro-rules lead to Macro-rules: Macro-rules can be identified that can be used for other models
* Validation: Verification ultimately leads to validation, which is the most sought after part of modeling
