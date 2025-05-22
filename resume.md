# Stav Haldar  
**Postdoctoral Research Associate, CICS, University of Massachusetts Amherst.**  
Google scholar  GitHub-projects  GitHub-personal-page

Ph.D. in Physics with 5+ years of research experience in simulations, modelling and theoretical analysis of quantum networks. Expertise in developing both physical layer and architecture level simulators for scalable quantum-networks using Python, with reinforcement-learning-driven policy optimization. Collaborations with experimental groups for implementation of quantum networking prototypes and testbeds.

## Education:
- Ph.D., Physics, 2019 - 2024, Louisiana State University. Thesis: “Design of long-distance entanglement distribution protocols for quantum networks.”
- M.Sc., Physics (Research Fellow), 2016 - 2019, Harish-Chandra Research Institute, India.
- B.Sc., 2013 - 2016, Birla Institute of Technology, Mesra.

## Relevant Experience
- **Postdoctoral Research Associate, UMass Amherst, Aug ’24–Present**  
  o Designed and analyzed an error-correction-based hybrid quantum network which utilizes the benefits of different physical platforms like ion traps (low gate error) and diamond vacancies (high rates).  
  o Integrated atmospheric turbulence & pointing-error models (including adaptive optics) in collaboration with Xairos Inc. as part of a large modular simulator development project for the European Space Agency.  
  o Developed a model for security of quantum time synchronization protocols.

- **Graduate Research Assistant, LSU, Aug ’20–Jul ’24**  
  o Conceptualized and simulated a global quantum clock synchronization network using a constellation of LEO satellites. Will provide uninterrupted quantum-secure picosecond level precision. Led academia-industry collaboration producing a software infrastructure and co-supervised two students. 4 peer reviewed publications (1 Editor’s Suggestion), 1 preprint, 1 white paper (NASA decadal survey in collaboration with JPL), and co-authored 1 successful grant application (Louisiana Board of Regents).  
  o Developed an ab-initio Markov decision process-based simulation of linear quantum networks. Optimization of distribution policies for high rates and fidelity using Q-Learning (model independent reinforcement learning). Improvement in rate and fidelity estimates is up to 100% using RL policies. Derived heuristics for large-scale implementation. Results publishes in Physical Review Applied (Editor’s suggestion). Co-authored 1 successful grant application (MURI).  
  o Formulated policies for multiplexed quantum networks. First implementation of policies designed to reduce classical communication costs. Introduced quasi-local policies for distillation and swapping, and through simulations showed order of magnitude improvement in entanglement rates compared to fully local policies. Results published in Communications Physics (Nature).

## Main Projects  
**Link to developed code:** https://github.com/stavhaldar/Quantum-Network-Policies  
- Reinforcement learning for quantum network policies: Monte Carlo simulator with Q-learning policy optimizer. Rate and fidelity figures of merit for different hardware parameters can be obtained. Benchmarking against Nested and SWAP-ASAP policies. Concatenation of policies for longer chains. Efficient state-space representation, warm-start, and parallel agents for faster learning.  
- Policies for multiplexed repeater chains: Simulation of quasi-local and fully local policies for multiplexed chains. Incorporation of classical communication costs of implementing policies. Comparison of different entanglement distillation policies. New distillation policies and identification of parameter regimes where different policies are optimal.  
- Hybrid encoded repeater chain: Modeling and simulation of a repeater chain with two kinds of repeaters, pure – using one memory platform (either high rate or high coherence time and high-fidelity gates) and/or hybrid – using two platforms (high rate from 1, high fidelity from other). Error correction using encoded Bell states with the 3-qubit repetition code.  
- Quantum clock synchronization network: Detailed model of free-space quantum communication channels, including atmospheric extinction, scintillation, layered turbulence model, beam wandering, etc. Satellite constellation dynamics for different orbits. Simulation of sync precision (theoretical bounds also derived) and security metrics like Bell violation.

## Publications & Preprints (most relevant, see Scholar link for full list of publications)
1. “Fast and reliable entanglement distribution with quantum repeaters: principles for improving protocols using reinforcement learning.” SH, PJ Barge, S Khatri, H Lee, Phys. Rev. Applied 21, 024041 (2024) (Editor’s suggestion).  
2. “Reducing classical communication costs in multiplexed quantum repeaters using hardware-aware quasi-local policies.” SH, Pratik Barge, Xiang Cheng, Sumeet Khatri, Brian Kirby, Hwang Lee, Chee Wei Wong. Communications Physics volume 8, Article number: 132 (2025)  
3. “Hybrid repeaters with encoding for long distance entanglement distribution.” SH, Saikat Guha, Don Towsley, Filip Rozpedek. Submitted to IEEE International Conference on Quantum Computing and Engineering (QCE) 2025 (Under review)  
4. “Quantum clock synchronization for future NASA deep space quantum links and fundamental science.” J Troupe, SH, I Agullo, P Kwiat. arXiv:2209.15122  
5. “A quantum-assisted master clock in the sky: sub-nanosecond quantum clock synchronization at global scales.” S Ducoing, S Haldar, JE Troupe, I Agullo. Phys. Rev. Applied 23, 014052 (2025) (Editor’s suggestion)

## Technical Skills
- Languages: Python, C++ (object-oriented programming), MATLAB.  
- Tools and Packages: Qiskit, QuTiP, Keras, GitHub.  
- Concepts: Quantum networks, entanglement measures, quantum information, error correction, quantum cryptography, relativistic effects on quantum systems, quantum many-body systems, modeling of free space and fiber-optic optical links, clock synchronization protocols.  
- Teaching and mentoring experience: co-supervised several undergraduate and graduate students at LSU and UMass, taught undergraduate lab courses at LSU, guest lectures on quantum cryptography at UMass. Delivered 10+ conference talks and 10+ invited seminar presentations.

*References available upon request*  
*Full list of publications invited talks and seminars on GitHub page*
