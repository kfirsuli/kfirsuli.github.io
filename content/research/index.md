---
title: Research
summary: Overview of research areas
type: landing
date: 2024-01-01

design:
  spacing: '4rem'

sections:
  - block: markdown
    content:
      title: Research
      subtitle: ''
      text: |
        My research sits at the intersection of **quantum optics**, **photonics**, **machine learning**, and **information security**. I develop new quantum and optical technologies — from fundamental physics to practical systems — with a focus on four interconnected pillars.

        ---

        <h2 id="quantum-secure-ai">Quantum-Secure AI & Quantum Cryptography</h2>

        <figure style="float: right; margin: 0 0 1rem 1.5rem; max-width: 280px;">
        <img src="quantum-secure-dl.jpg" alt="Quantum-secure multiparty deep learning" style="width: 100%; border-radius: 0.5rem;">
        <figcaption style="font-size: 0.8rem; color: #6b7280; margin-top: 0.4rem; text-align: center;">Image credit: Sampson Wilcox</figcaption>
        </figure>

        As deep learning moves to the cloud, protecting sensitive data during computation becomes critical. I pioneered a new approach that uses **quantum mechanics to provide information-theoretic security** for multiparty deep learning — guaranteeing security not by computational hardness assumptions, but by the laws of physics.

        Our protocol enables multiple parties to collaboratively perform deep neural network inference without revealing their private data to each other or to the server. This work was published in **Physical Review X (2025)** and received widespread media coverage from [MIT News](https://news.mit.edu/2024/new-security-protocol-shields-data-during-cloud-based-computation-0926), [Tech Briefs](https://www.techbriefs.com/component/content/article/52065-new-security-protocol-protects-cloud-based-server-data), ScienceDaily, Phys.org, and SciTechDaily.

        On the quantum cryptography side, my work advances **high-dimensional quantum key distribution (QKD)** — encoding information in multiple degrees of freedom of single photons (spatial modes, time bins, orbital angular momentum) to achieve higher secret key rates with practical hardware.

        Key contributions include:
        - **Quantum-secure multiparty deep learning**: Information-theoretically secure cloud AI using quantum mechanics (Physical Review X 2025).
        - **High-dimensional coherent one-way QKD**: A protocol that doubles secret key rates compared to standard binary encoding, using only commercial off-the-shelf hardware. Demonstrated over 40 km of standard fiber — upgradeable via software alone.
        - **Programmable entanglement processing**: Using multi-plane light converters to reconfigurably manipulate high-dimensional entangled states for quantum information tasks.
        - **QKD with quantum dots**: Orbital angular momentum-based high-dimensional QKD using room-temperature single-photon sources.

        *Key papers: Physical Review X (2025), npj Quantum Information (2022, 2025), Physical Review Applied (2022), Optica Quantum (2024)*

        ---

        <h2 id="ai-for-science">AI for Science & Formal Verification</h2>

        A core direction of my research is using AI to advance scientific discovery — in particular through **automated theorem proving** and **formal verification** in the Lean proof assistant. We are building tools that combine the reasoning capabilities of large language models with the rigorous guarantees of formal mathematics, and applying them to quantum information theory.

        Our flagship project is [**Ax-Prover**](https://arxiv.org/abs/2510.12787), a multi-agent framework for automated theorem proving in Lean. Ax-Prover equips LLMs with Lean tools via the Model Context Protocol (MCP), allowing the model to inspect proof goals, search for relevant lemmas, and generate verified proof steps. On standard math benchmarks Ax-Prover is competitive with state-of-the-art provers, while it substantially outperforms them on new domain-specific benchmarks we introduced in **abstract algebra** and **quantum theory**. We also demonstrated Ax-Prover as a human-AI collaboration tool, helping an expert mathematician formalize and machine-check a complex cryptography theorem in ~2,000 lines of Lean over two working days.

        Beyond Ax-Prover, we are actively developing a **Lean library for quantum information theory** — formalizing key results in quantum cryptography, entanglement theory, and quantum error correction. The goal is to create a verified foundation that brings the rigor of formal mathematics to quantum information science.

        *Key paper: [Ax-Prover](https://arxiv.org/abs/2510.12787) (arXiv 2025)*

        ---

        <h2 id="in-physics-computing">In-Physics Computing</h2>

        I develop computing architectures that perform machine learning **directly in the physical domain** — using optical and radio-frequency hardware to execute neural network operations at the speed of light, without digital processing overhead.

        The key insight is that many linear algebra operations at the heart of deep learning (matrix multiplications, convolutions) can be performed natively by physical wave propagation. By designing hardware that exploits this, we achieve energy-efficient and ultra-fast inference that can be deployed at the wireless edge or in data centers.

        Key contributions include:
        - **Disaggregated RF in-physics computing**: Machine learning executed directly in radio-frequency hardware over wireless channels, enabling AI at the edge without digital processing (Science Advances 2026).
        - **Optical QAM neural networks**: Efficient optical AI accelerators using quadrature amplitude modulation for high-throughput inference.
        - **Nanophotonic integrators**: Three-terminal photonic devices for deep neural network computation.
        - **Photodetection-free optical ML**: Optical machine learning architectures that operate entirely in the optical domain via rectification.

        *Key papers: Science Advances (2026)*

        ---

        <h2 id="quantum-nonlinear-photonics">Quantum & Nonlinear Photonics</h2>

        My work in photonics spans both quantum and classical nonlinear regimes — from generating and controlling entangled photon pairs in optical fibers to uncovering new physics in ultrafast laser dynamics.

        **Soliton dynamics and Casimir-like interactions.** Ultrafast fiber lasers produce complex multi-pulse dynamics. My research uncovered **noise-mediated Casimir-like interactions** between optical solitons — a long-range force analogous to the quantum vacuum Casimir effect, but arising from classical noise fluctuations. We observed bidirectional soliton rain dynamics and controlled dynamical transitions between loosely- and tightly-bound soliton states. We also studied ultrafast rogue wave patterns using time-lens techniques.

        **Photon pair generation and coherent control.** I developed **all-fiber sources of multimode correlated photons** using spontaneous four-wave mixing in few-mode fibers, with all-fiber mode sorting for scalable quantum networks. Using programmable multi-plane light converters and mechanical fiber perturbation arrays, we demonstrated reconfigurable control of high-dimensional entangled states and spectral shaping in multimode fibers.

        Key contributions include:
        - **Bidirectional soliton rain dynamics**: First observation of Casimir-like acceleration and bidirectional motion of soliton bunches in fiber lasers (Physical Review Letters 2018).
        - **Bound soliton pairs**: Controlled transitions between loosely- and tightly-bound states via noise-mediated interaction potentials (Optica 2022).
        - **Ultrafast rogue waves**: Measurement and modeling of extreme wave events in fiber lasers (Optica 2018).
        - **All-fiber correlated photon sources**: Generation and sorting of multimode photon pairs in few-mode fiber (npj Quantum Information 2022).
        - **Multimode fiber saturable absorbers**: Theory and experiments on bandwidth-induced saturation mechanisms (Optics Letters 2024).
        - **All-fiber wavefront modulation**: Coherent control of light propagation in multimode fibers using mechanical perturbations (J. Phys. Photonics 2023).

        *Key papers: Physical Review Letters (2018), Optica (2018, 2022), npj Quantum Information (2022), Optics Letters (2024)*
---
