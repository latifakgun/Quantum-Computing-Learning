***QUANTUM GATES AND CIRCUITS***

-----
-----

**1. Reading and Interactive Study (Theory + Logic)**

Before starting with your current book, we'll begin with Quantum Country, which explains the subject more fluently.

**Read & Apply:** [Quantum Country - Part II: Introducing quantum logic gates](https://quantum.country/qcvc#part-II)

Take Notes: In this section, you will encounter the concept of "Unitary Evolution." Note why quantum gates (matrices) must be reversible and how this relates to the "unitary" nature of the matrix.

Critical Note: Get acquainted with the X-gate, the quantum equivalent of the classical NOT gate.

-----
-----
-----

**2. Book Reading (Mathematical Reinforcement)**

**Book:** Quantum Computing for Everyone (Bernhardt)

Chapter: Further in the book, there is a chapter titled "Quantum Gates and Circuits" (usually Chapter 6 or 7; check the table of contents). Read only the section on Single Qubit Gates.

**Skip:** If you see sections about "CNOT" or "Entanglement," skip them for now; they're for Section 3. Focus only on single-qubit matrices!

-----
-----
-----

**3. Practice and Coding (Most Important 🚨)**

Now it's time to learn by "writing code." This resource will allow you to put theory into practice immediately.

**Start:** [PennyLane Codebook](https://pennylane.ai/codebook)

**Complete:** Open the "I. Introduction to Quantum Computing" module.

Finish these subtopics: "Qubits," "Unitary Matrices," and "Rotations" (or Single-qubit gates).

Task: Be sure to solve the Python exercises here (X gate, Hadamard gate). Feel the matrix behind the qml.Hadamard command.

-----
-----
-----

**4. Visualization (Dancing in the Bloch Sphere)**

It's difficult to memorize matrices (Linear Algebra) without visualization.

**Research/Watch:** Search "Bloch Sphere Visualization of Quantum Gates" on YouTube or in the Qiskit documentation.

Try to visualize the following:

X-Gate: Rotates the sphere 180 degrees horizontally (turns the North Pole into the South Pole).

Z-Gate: Rotates the sphere on its own axis (longitudinal). (If you are standing at the North or South Pole, the Z-Gate appears to have no effect! This is called "Phase," and it is very critical).

Hadamard (H)Gate: Brings the qubit at the North Pole (∣0⟩) down to the equator (∣+⟩, i.e., Superposition).
