# nfa-to-dfa-visulizer

#  Automata Visualizer: NFA to DFA Converter

##  Overview
This project is an interactive, web-based visualization tool designed to demonstrate the conversion of a **Nondeterministic Finite Automaton (NFA)** into a **Deterministic Finite Automaton (DFA)**. 

Built as a core concept demonstration for Automata Theory and Computability, the engine utilizes the **Subset Construction Algorithm (Powerset Construction)** to compute the deterministic states from an ambiguous NFA and renders the network topology in real-time.

##  Key Features
* **Algorithmic Conversion:** Accurately computes the DFA subsets, handling transition mapping and final state carry-over.
* **Transition Matrix Generation:** Automatically builds and displays the state transition table for the compiled DFA, including the handling of Dead States (Ø).
* **Dynamic Graph Rendering:** Visualizes both the original NFA and the compiled DFA side-by-side using a physics-based repulsion system to prevent node overlapping.
* **Visual Clarity:** Accepting (Final) states are distinctly marked with a dual-color neon halo (Double Circle effect) for instant identification.
* **Modern UI:** Features a responsive, cyberpunk-inspired glassmorphism interface with ambient background animations.

##  Technologies Used
* **Frontend:** HTML5, CSS3, Vanilla JavaScript
* **Visualization Engine:** [vis-network.js](https://visjs.github.io/vis-network/) for interactive graph physics and node rendering.

##  Author
**Jagmohan Singh** Computer Science Engineering  
Netaji Subhas University of Technology (NSUT)  
Roll Number: 2024UCS1567

