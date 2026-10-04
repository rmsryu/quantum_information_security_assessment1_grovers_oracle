# Assessment 1: Quantum Oracle and Grover's Algorithm
Presentation of the marking phase Quantum Concept. How an Oracle work on Grovers algorithm.

# Notes [[1]](https://doi.org/10.1103/PhysRevX.14.041029)
1. > _GA requires a second operator, the diffusion operator Us that has a structure similar to the oracle but with respect to the known state |s⟩_ 
2. > _Definition of the Grover algorithm: Given an oracle Uw, GA proceeds as follows:_
    - (1) initiate the qubits in state |000...0>.
    - (2) apply a Hadamard gate on each qubit to obtain |s⟩.
    - (3) apply the oracle operator Uw.
    - (4) apply the diffusion operator Us.
    - (5) repeat steps 3 and 4 each q times.
    - (6) measure the qubits in the computational basis and find |w⟩ with a probability very close to 1.
 3. >  _.. in other words, while Grover’s algorithm takes advantage of quantum parallelism (i.e., superposition), it uses very little entanglement for most of the algorithm_

