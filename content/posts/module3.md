---
title: MorelandU - Learning in the digital age
date: 2022-11-11T16:00:00.000Z
image: techsurvey.png
tags: ['moreland']
---

## Week 1

I created two surveys for this module, one for teachers and one for students. 

Survey for teachers: [https://www.surveymonkey.com/r/R8XJS5F](https://www.surveymonkey.com/r/R8XJS5F)

Survey for students: [https://www.surveymonkey.com/r/BG3T7LH](https://www.surveymonkey.com/r/BG3T7LH)


{{< video "Q0da5qPMH9E" >}}


## Week 2

### Challenges to Learning

1. Information Overload

Know how to ignore things. Look at the sources, follow back to the source. 

2. Thinking critically

Open-mindedness. Considering other points of view. Skepticism.

3. How to use tech holistically

Understand the problem that tech is supposed to solve.  It is about creating a workflow

4. Taking initiative

Allowing independent work. Tying lessons to the end goal, giving them a why.

5. Adapting to change

Be ready to fail. Teach them to not fear complexity. 


## Week 4

### Game of Life

By: Kevin Sparling

Moreland University: Module 3, Unit 3, Activity 1

#### Overview

The Game of Life (or Life) was devised by the mathematician John Conway, it simulates the life of individual cells according to very simple pre-determined rules. It requires user-input only at the beginning - individual cells are set to be living or dead and once the game begins it proceeds according to the initial rules.

#### Instructional Objective

The objective of the game is to show students that very complex patterns can be created using very simple, understandable rules. This would be perfect as part of an IB inquiry that explores any life-system. The children should use this to learn that systems are governed by rules, and initial conditions are very important to how something evolves.

#### Learners

This game is appropriate for children who are approximately 12 years old and above, when used for it's intended purpose to teach about life systems. This should be used as part of a math program, or biology as a way to demonstrate evolution on the cellular level. It can be used for younger children, with a simplified focus or merely as a piece of art.

#### Motivation

This type of game is likely very unfamiliar to students, since it is defined as a zero player game - meaning that students only setup initial conditions and then leave it alone. It can be played many times, with the main motivation being to get students to study the rules and make predictions as to what kind of patterns will be observed. It is very beautiful to watch, and it encourages experimentation. This will pique children's natural curiosity and allow them to make predictions about what they think should happen - and then get immediate feedback.

#### Context of Use

This should be used as supplement in either a math or biology class, used to demonstrate the power of emergent patterns in nature. Since it is also very beautiful, it can also be used as a reward. 

#### Scope

The game is minimal in scope, by design. It can be played in approximately 10 seconds, or all day depending on the determination of the user. There is only one screen, with a modal that describes the rules. It can be modified to allow student's to create their own rules, but in the initial version I will stick to the rules originally created by Dr. Conway.

## Week 4

### Game of Life

By: Kevin Sparling

Moreland University: Module 3, Unit 4, Activity 1

#### Overview

The Game of Life (or Life) was devised by the mathematician John Conway, it simulates the life of individual cells according to very simple pre-determined rules. It requires user-input only at the beginning - individual cells are set to be living or dead and once the game begins it proceeds according to the initial rules.

#### Instructional Objective

The objective of the game is to show students that very complex patterns can be created using very simple, understandable rules. This would be perfect as part of an IB inquiry that explores any life-system. The children should use this to learn that systems are governed by rules, and initial conditions are very important to how something evolves.

#### Learners

This game is appropriate for children who are approximately 12 years old and above, when used for it's intended purpose to teach about life systems. This should be used as part of a math program, or biology as a way to demonstrate evolution on the cellular level. It can be used for younger children, with a simplified focus or merely as a piece of art.

#### Motivation

This type of game is likely very unfamiliar to students, since it is defined as a zero player game - meaning that students only setup initial conditions and then leave it alone. It can be played many times, with the main motivation being to get students to study the rules and make predictions as to what kind of patterns will be observed. It is very beautiful to watch, and it encourages experimentation. This will pique children's natural curiosity and allow them to make predictions about what they think should happen - and then get immediate feedback.

#### Context of Use

This should be used as supplement in either a math or biology class, used to demonstrate the power of emergent patterns in nature. Since it is also very beautiful, it can also be used as a reward. 

#### Scope

The game is minimal in scope, by design. It can be played in approximately 10 seconds, or all day depending on the determination of the user. There is only one screen, with a modal that describes the rules. It can be modified to allow student's to create their own rules, but in the initial version I will stick to the rules originally created by Dr. Conway.

#### Object of the Game

The game can proceed indefinitely or end very quickly. As a learning tool, it is likely best to give the students a goal of creating initial conditions that will create an "ecosystem" that lasts for a long time - or indefinitely. Many different goals can be set, to increase the game's power as a learning tool they should be based around predicting how long different configurations will last and how they will evolve.

#### Design Details

![Game of Life](https://pi.math.cornell.edu/~lipa/mec/banner.png)

This is the initial start screen for the game. A grid of cells, which can be selected by the player before pressing the start button. On the top right is the name of the game, and an info button that displays a list of instructions about how to play the game. 

I am currently working on the game, the initial screen is completed and shown above. This was created using VueJS, which is a package of NodeJS (Javascript). It is played in a web browser, and the requires no technical ability to play. Simply go to the website and the game will load. 

I will list the rules that govern the game here: 

Every cell interacts with its eight neighbors following these six simple rules:

1. Live cells with zero or one live neighbors die by underpopulation.
2. Live cells with two or three live neighbors live to the next generation.
3. Live cells with more than three live neighbors die by overpopulation.
4. Dead cells with three live neighbors become a live cell by reproduction.
5. Live cells retain their colour, permanently, until they die due to over or underpopulation.
6. When a cell is born, it takes on the colour value of the majority of its three neighbours.

#### Design Process

I have a background in earth science, the study of which often involves simple rules that govern complex systems. I have always been intrigued that patterns that seem random can be governed by very simple rules. The motivation for this game is from my background in mathematics, and an interest in syntactical structures as part of linguistics. As mentioned above this game is a classic in mathematics learning, but I have added a new element where the user can give an element of color, red or blue, so there are two different types of "cells". I feel that it adds a new twist to the game, making something that resembles a "battle" between two different types of population. The programming of the game will be relatively simple, I am very familiar with Javascript and making the skeleton of the game shown above only took a short time. The feedback I received was roughly inline with what I planned to do anyway, excepting that the other cohort members seemed to think that this game will require the students to do some math as part of the game, and it will not. This game is to teach logical thinking, so I will include that in the description of how to play the game. 
