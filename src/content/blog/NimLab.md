---
author: Jackson Bunting
pubDatetime: 2024-01-08T02:16:34.760Z
title: Creating the game Nim in MATLAB
featured: false
draft: false
tags:
  - Project
  - MATLAB
description:
  Background and sources for my MATLAB project NIMLAB.
---

## Github
https://github.com/TalkingF/Nimlab

## Background

As part of my introductory class to programming, we spent the first month or two learning the basics in Matlab. For those unfamilliar, MATLAB is a propietary programming language used for simulations, plotting functions and algorithms as well as providing extra control for some of Mathworks other tools. Before I took this class, I had some basic experience mainly in Java through some university courses I took earlier but hadn't had much experience designing my own project. 

Come mid-semester, we were tasked with developing a complete project, were given some basic criteria and were given free rein to create what ever, given the constraints of the language we were working with. 

Given the nature of the language, I wanted to create something dynamic while staying away from developing a fully-fledged GUI. While doing research, I stumbled upon the game Nim, which shares properties with connect four and tic-tac-toe, being a mathematically solved game. With this idea in hand, I set of to developing it with the tools I had.

The project consisits of an AI that the player can play against, multiple board sizes, choice of turn order and difficulties. I was particuarly proud of my implementation of variable difficulty. Since the game was mathematically solved, i was able to use random number generation to determine whether the AI would play the optimal move or instead opt for a random move instead, with the odds of selecting the optimal move increasing with the difficulty selected.







