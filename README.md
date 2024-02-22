# Quantum computing project for course PHYS-641 in 2021

## Digital quantum simulation of interacting spin models

Richard Feynman is considered the father of the idea of quantum computing. In 1981 he gave a keynote address at the MIT Conference on the Physics of Computation. His most famous quote of that address was: “Nature isn’t classical . . . and if you want to make a simulation of Nature, you’d better make it quantum mechanical, and by golly it’s a wonderful problem, because it doesn’t look so easy!”. Feynman was putting forth the idea that, since simulating the laws governing quantum mechanics is a hard computational task on a quantum computer, the same task could be carried out more efficiently by a computer governed by the very same laws of quantum mechanics. This marked the birth of quantum simulation.

In this project, we wish to learn and practice digital quantum simulation. Digital quantum simulation means that the laws of quantum mechanics – more specifically Schrödinger’s equation – are translated into a quantum algorithm running on a quantum computer using only a universal set of quantum gates, like we learned in this course. Alternatively, quantum simulation may be analog, meaning that we design and build a specific quantum system in which the laws we wish to simulate are hardwired, rather than programmed. Analog quantum simulation is a vast and interesting research field, but it lies outside the scope of our course.

A very good and pedagogical review article on digital quantum simulation has very recently been published. You may also be interested in a more specific research article by the same Authors, which conveys the same ideas in a more synthetic – but less pedagogical – way.

The goal of the project is:

1. Read and understand the main article and present its results.
2. Implement on IBM-Q digital simulations of the time-evolution of the two- and three-spin Heisenberg model, explaining what are the main differences in the two implementations.
3. Using the QASM simulation, compute estimates of various observables of the system as a function of time, and in particular of the dynamical correlation functions.
4. Run the simulation with the QASM simulator including noise and study how rapidly the quality of the solution deteriorates as a function of the time interval that is being simulated. This is done by computing the fidelity of the solution.
5. Discuss the origin of errors and in particular study the relative importance of the finite time step error (called Suzuki-Trotter error) and of the errors originating from the quantum hardware itself.

## Find in this repository
- The jupyter notebook using qiskit to implement the project
- The final presentation of the project
