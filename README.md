# Quantum-Teleportation-on-IBM-s-quantum-computers

Standard quantum teleportation executed them on IBM's quantum computers. Deferred measurement Principle.

The deferred measurement Principle states that we can delay any measurement on the circuit to the end of the protocol by placing controlled operations. Currently, IBM's devices do not use classical registers, the controlled operations for recovery are necessary in order to Bob obtain the correct quantum state on his side.

# Code Explanation

The process of quantum teleportation is very similar to the one discussed in Quantum-Teleportation, but we can notice some differences. We have uploaded our quantum experience account in step 2, and called the proper backend, they can be found at https://quantum-computing.ibm.com/services/resources. For this, we need to change the execution process, by correctly transpiling our circuit, in order to optimize the procedure according the architecture of the selected device. To conclude, we have added the fitter procedures that can be found at https://qiskit.org/textbook/preface.html, which is important when we are dealing with experimental data.  
