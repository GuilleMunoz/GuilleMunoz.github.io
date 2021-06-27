---
permalink: /projects/
title: "Projects"
---

## Topological Data Analysis ([TDA](https://en.wikipedia.org/wiki/Topological_data_analysis)) 

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/GuilleMunoz/computational_topology)

TDA aims to extract information from noisy, incomplete or complex dataset using techniques from topology like persistent homology. This projects provide multiple data structures and algorithms used in TDA. 
The main class, AlphaComplex, is a simple implementation can be used to compute the persistence homology of a set of points.

<figure class="half" align="center">
  <a href="/_pages/examples/TDA/animation.gif"><img src="/_pages/examples/TDA/animation.gif"></a>
  <a href="/_pages/examples/TDA/persistent_homology.png"><img src="/_pages/examples/TDA/persistent_homology.png"></a>
  <figcaption>Persistent homology of a double torus (genus 2).</figcaption>
</figure>

## Advanced Encryption Standard ([AES](https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.197.pdf))

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/GuilleMunoz/AES)

AES algorithm is a symmetric key encryption block cipher capable of handling 128 bits (16 bytes) blocks using keys of size 128, 192 or 256 bits. AES consists of multiple encryption rounds. On each, the cipher performs a series of mathematics transformations. 
With performance in mind, the algorithm will be implemented using [cython](https://cython.org). 


<figure class="align-center" align="center">
  <a href="/_pages/examples/AES/diagram.png"><img src="/_pages/examples/AES/diagram.png" style="max-width: 500px;"></a>
  <figcaption>AES flowchart for 128 bits keys.</figcaption>
</figure>

## City Tasks Assigment

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/GuilleMunoz/city_tasks_assignment)

This projects consists on assigning some tasks to some teams during a campaign (e.g. cleaning and maintenance of a city or packages distribution) minimising the time and cost. 
To solve the problem we've implemented an exact method that uses linear programming techniques (such as branch and bound algorithm) in order to obtain the optimal solution, and, because this method has a hi complexity, we also implement the simulated annealing metaheuristic.
With performance in mind, algorithms will be implemented using **C** and later extended to **Python** for ease of use.

<figure class="align-center" align="center">
  <a href="/_pages/examples/CTA/A-flowchart-of-the-simulated-annealing-algorithm.jpg"><img src="/_pages/examples/CTA/A-flowchart-of-the-simulated-annealing-algorithm.jpg" style="max-width: 500px;"></a>
  <figcaption>Flowchart of the simulated annealing algorithm.</figcaption>
</figure>

Aditionaly, because in real life the times and costs of doing each tasks are known with certain uncertainty (assumed to be normal), we implement a Monte Carlo simulation to analyse how the objetives vary. 
A similar simulation can be done to observe how different preferences on the objectives affect to the overall time and cost.

## Assembly Line Balancing Problem (ALBP)

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/GuilleMunoz/Assembly_Line_Balancing_Problem)

The ALBP consists of assigning tasks to an ordered sequence of stations such that the precedence relations among the tasks are satisfied, and some performance measure is optimized. 
There are some algorithms designed for this problem. 
The genetic algorithm approach is easy to program and can be easily adapted for other problems such as the travelling salesman problem. 
To try to find a better solution faster we defined an heuristic mutation operator. 
It assigns a random station to a task that violates the precedence relations. 
We also include multiple selection methods (roulette, tournament, rank), mutation operators (random, swap, scramble, inverse), crossover operators (Double Point, Single Point, Uniform). 
To compare the performance, we define comparations methods.

<figure class="align-center" align="center">
   <a href="/_pages/examples/GA/ga.png"><img src="/_pages/examples/GA/ga.png" style="max-width: 500px;"></a>
  <figcaption>Genetic algorithm flowchart.</figcaption>
</figure>

## First steps of a JavaScript compiler

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/GuilleMunoz/javascript_pdl)

Compilers translate the programming language’s source code to machine code dedicated to a specific machine.
The compilation process is divided into 6 phases:
1. Lexical analysis
2. Syntax analysis
3. Semantic analysis
4. Intermediate code generation
5. Optimization
6. Code generation

This projects focuses on the first 3 phases for a simplified version of JavaScript.

## Tokyo Subway

[![View on Github](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/GuilleMunoz/tokyo_subway)

A* is a path search algorithm. 
In this project we will use it for finding the shortest path between two stations of a simplified version of the Tokyo subway. 
A* achieves better performance than Dijkstra algorithm using an heuristic to guide the search. 
For ease of use we implemented a GUI to execute the A* search. 

<figure class="third" align="center">
  <a href="/_pages/examples/Tokyo/GUI_Tokyo1.png"><img src="/_pages/examples/Tokyo/GUI_Tokyo1.png"></a>
  <a href="/_pages/examples/Tokyo/GUI_Tokyo2.png"><img src="/_pages/examples/Tokyo/GUI_Tokyo2.png"></a>
  <a href="/_pages/examples/Tokyo/GUI_Tokyo3.png"><img src="/_pages/examples/Tokyo/GUI_Tokyo3.png"></a>
  <figcaption>GUI of app at different stages.</figcaption>
</figure>
