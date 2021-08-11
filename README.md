# IBM Quantum Awards: Open Science Prize

This is the solution repository for the IBM Quantum Awards: Open Science Prize. You can read more about it [here](https://www.ibmquantumawards.com/), and read the IBM Quantum announcement [here](https://www.ibm.com/blogs/research/2020/11/open-science-prize/).

# Objective

**Creating larger graph states with better fidelity** Graph states entangle all involved qubits, and these entangled quantum states could be important for various applications, particularly those related to error correction, in the near future. The goal here is to create the largest graph states using the same benchmarking and error mitigation techniques that are also used to improve the individual quantum gates, ultimately looking for the best fidelity graph state with at least a 50% reduction in the infidelity as estimated by stabilizer measurements outlined in [this Jupyter notebook](https://github.com/qiskit-community/open-science-prize/blob/main/ibmquantum-graph-states-challenge.ipynb).

# Solution

We focus on improving gate fidelities by manipulating the graph state function to minimize decoherence. We modify the way the circuit gates run to optimize and reduce noise error. We calibrate our measurements for the CTMP error mitigation using quantum states with two-qubit excitations with custom parameters.
Solution Notebook [here](https://github.com/prashanth-up/Graph-State-Challenge/blob/master/solution-ibmquantum-graph-states-challenge.ipynb)
