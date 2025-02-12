# Quantum Algorithm for System Specification Verification - Lab

This lab guides through implementing a quantum algorithm to verify system specifications using Qiskit.

### **Algorithm Steps:**
1. **Initialize Variables**: Prepare input qubits in a uniform superposition.
2. **Apply Oracles**: Encode system specifications as Boolean logic functions.
3. **Controlled Hadamard Marking**: Use a controlled Hadamard operation to mark valid solutions by entanglement.
4. **Creating Another Instance**: Create a second instance of the system.
5. **Mz Operator**: Apply Mz operator and obtain concurrence value.
6. **Determine Consistency**: Evaluate the concurrence value to check system specification consistency.

### **Reference:**
This algorithm is based on "A Quantum Algorithm for System Specification Verification" by Mohammed Zidan, Ahmed M. Eisa, and Mahmoud A. Ismail Shoman. The paper introduces a quantum approach using entanglement measures for efficient system verification.

M. Zidan, A. M. Eisa, M. Qasymeh and M. A. I. Shoman, "A Quantum Algorithm for System Specifications Verification," in IEEE Internet of Things Journal, vol. 11, no. 14, pp. 24775-24794, 15 July15, 2024, doi: 10.1109/JIOT.2024.3383034.
