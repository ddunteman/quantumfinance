# quantumfinance
ES170 Project Spring 2019 -- Zach Buttenwieser and Dillon Dunteman

## Files Breakdown

  PricingSimulation_vF runs the simulation for the discretized probability distribution of the expected payoff, then shows the quantum-calculated payoffs per number of qubits.

  EuropeanCall_RealDevice extracts the quantum circuit from European Call tutorial functions within the Qiskit Aqua Finance package. 
  The code has the capability to run on IBM's 5 or 14 qubit devices, with compatibility dependent on the number of "uncertainty_qubits" set as for the probability model that acts as an input for the circuit factory of the "european_call" object.
