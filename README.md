# Airplane Optimizer - MacHacks2021

## Inspiration
Wanted to do something with quantum computing and was interested in quantum hybrid algorithms

## What it does
Applies the traveling salesman problem to the airplane industry and uses a quantum computer to compute the optimal solution

## How we built it
- I took a list of airports, found their latitude/longitude to create a distance matrix
- Created a graph and mapped the distance matrix to the graph
- Mapped it to the Ising model then sent it to the quantum algorithm to optimize
- Take the answer and determined which path to take

## Challenges we ran into
- Figuring out what the functions do and what the variables do in the Qiskit tutorial
- Trying to read and understand the Qiskit documentation
- Constant trial and error 

## Accomplishments that we're proud of
- Getting the distance matrix from the airports mapped onto the real graph for the quantum algorithm
- Getting the code to work

## What we learned
- How the math/theory works for the algorithm
- How to create a distance matrix from scratch

## What's next for Airplane Optimizer
- Create parameters and airspace limits (ie. can't fly over White House, etc.)
- Have it work for more airports (more nodes)

(YouTube Video)[https://www.youtube.com/watch?v=KKzbP9s_FK4&feature=youtu.be]
