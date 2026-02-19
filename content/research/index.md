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
        I aim to advance the second quantum revolution in the AI era by developing novel information-processing protocols and demonstrating them on physical platforms. My experimental toolbox includes integrated photonics, fiber optics, analog electronics, and satellite-communication infrastructure. The emphasis is on information processing enabled by these platforms, with a dual track: harvesting classical gains now while advancing the protocols and hardware needed for scalable, fault-tolerant quantum information processing.

        ---

        <h2 id="quantum-secure-ai">Quantum-Secure AI & Quantum Cryptography</h2>

        <figure style="float: right; margin: 0 0 1rem 1.5rem; max-width: 280px;">
        <img src="quantum-secure-dl.jpg" alt="Quantum-secure multiparty deep learning" style="width: 100%; border-radius: 0.5rem;">
        <figcaption style="font-size: 0.8rem; color: #6b7280; margin-top: 0.4rem; text-align: center;">Image credit: Sampson Wilcox</figcaption>
        </figure>

        Can we realize the benefits of big data in the AI era without compromising individual privacy? As deep-learning workloads move to the cloud, vulnerabilities multiply, making secure computation urgent. I pioneered a physics-based, **information-theoretically secure computation scheme** using conventional telecom components. The protocol simultaneously prevents leakage of the server's model to the client and of the client's data to the server. I derived analytical upper bounds on information leakage for both neural-network weights and client inputs, attaining accuracy close to digital baselines while guaranteeing information-theoretic security bounds. This work was published in **Physical Review X (2025)** and covered by [MIT News](https://news.mit.edu/2024/new-security-protocol-shields-data-during-cloud-based-computation-0926), [Tech Briefs](https://www.techbriefs.com/component/content/article/52065-new-security-protocol-protects-cloud-based-server-data), ScienceDaily, Phys.org, and SciTechDaily.

        I was the first to exploit **quantum vacuum fluctuations** for secure multiparty computation, and have proposed an implementation via **nondemolition computation** based on optical nonlinearity, validated across several photonic platforms including thin-film lithium niobate photonic-crystal cavities.

        On the quantum cryptography side, my PhD work integrates theory and experimentation, co-optimizing the stages of protocol development to produce practical and **provably secure communication protocols**. My work advances high-dimensional QKD — encoding information in multiple degrees of freedom of single photons to achieve higher secret key rates with practical hardware.

        Key contributions include:
        - **Quantum-secure multiparty deep learning**: Information-theoretically secure cloud AI using quantum mechanics (Physical Review X 2025).
        - **Nondemolition quantum-secure computation**: Photodetection-free approach using optical nonlinearity on integrated photonic platforms.
        - **High-dimensional coherent one-way QKD**: A protocol that doubles secret key rates using only commercial off-the-shelf hardware, demonstrated over 40 km of standard fiber.
        - **Quantum error correction for QKD**: Applying quantum error correction techniques to improve quantum cryptography protocols.
        - **Programmable entanglement processing**: Reconfigurable manipulation of high-dimensional entangled states using multi-plane light converters.

        *Key papers: Physical Review X (2025), npj Quantum Information (2022, 2025), Physical Review Applied (2022), Optica Quantum (2024)*

        ---

        <h2 id="ai-for-science">AI for Science & Formal Verification</h2>

        A core direction of my research is using AI to advance scientific discovery — through **automated theorem proving (ATP)** and **formal verification** in the Lean proof assistant. ATP encodes mathematical statements in formal logic and uses algorithmic inference to verify or discover proofs. Despite recent progress, existing systems cannot yet certify the security or functionality of quantum schemes. In collaboration with ATP experts at MIT, we recently formalized, to our knowledge, **the first QKD security proof in Lean**.

        Our flagship project is [**Ax-Prover**](https://arxiv.org/abs/2510.12787), a multi-agent framework for automated theorem proving in Lean. Ax-Prover equips LLMs with Lean tools via the Model Context Protocol (MCP), allowing the model to inspect proof goals, search for relevant lemmas, and generate verified proof steps. On standard math benchmarks Ax-Prover is competitive with state-of-the-art provers, while it substantially outperforms them on new domain-specific benchmarks we introduced in **abstract algebra** and **quantum theory**. We also demonstrated Ax-Prover as a human-AI collaboration tool, helping an expert mathematician formalize and machine-check a complex cryptography theorem in ~2,000 lines of Lean over two working days.

        Beyond Ax-Prover, we are actively developing a **Lean library for quantum information theory** — formalizing key results in quantum cryptography, entanglement theory, and quantum error correction. This paves the way for **automated discovery of advanced primitives**, including secure multiparty computation and QKD protocols.

        *Key paper: [Ax-Prover](https://arxiv.org/abs/2510.12787) (arXiv 2025)*

        ---

        <h2 id="in-physics-computing">In-Physics Computing</h2>

        Analog computing has been studied for decades, but the demand for high precision kept systems in the digital domain. Today's ML models rely on low-bit arithmetic, well within analog reach. I develop computing architectures that perform machine learning **directly in the physical domain** — using optical and radio-frequency hardware to execute neural network operations at the speed of light, with immediate energy-cost advantages.

        Rather than adapting analog hardware to digital-era models, I propose the inverse: **design hardware-tailored AI models natively suited to optics**. The cornerstone is **digital twins** — differentiable AI-based virtual replicas of physical systems synchronized in real time with experimental data. Training these twins end-to-end lets us co-optimize hardware and algorithms, discover photonics-tailored architectures, and accelerate discovery.

        A fundamental question drives this work: *What is the irreducible energy required to complete a computational task within finite temperature, time, and space, and how close can optics push us to that limit?*

        Key contributions include:
        - **Disaggregated RF in-physics computing**: A cellphone's RF front-end (antenna, filters, mixers, amplifiers) can perform real-time inference when the model is streamed over the air, eliminating memory and extra hardware (Science Advances 2026).
        - **Optical QAM neural networks**: Efficient optical AI accelerators using quadrature amplitude modulation for high-throughput inference.
        - **Nanophotonic integrators**: Three-terminal photonic devices for deep neural network computation.

        *Key papers: Science Advances (2026)*

        ---

        <h2 id="quantum-nonlinear-photonics">Quantum & Nonlinear Photonics</h2>

        My work in photonics spans both quantum and classical nonlinear regimes — from generating and controlling entangled photon pairs in optical fibers to uncovering new physics in ultrafast laser dynamics. The field of nonlinear optics has gained renewed attention for quantum information processing, as single-photon-level nonlinearity has become achievable.

        **Soliton dynamics and Casimir-like interactions.** Ultrafast fiber lasers produce complex multi-pulse dynamics. My research uncovered **noise-mediated Casimir-like interactions** between optical solitons — a long-range force analogous to the quantum vacuum Casimir effect, but arising from classical noise fluctuations. We observed bidirectional soliton rain dynamics and controlled dynamical transitions between loosely- and tightly-bound soliton states. I am also exploring whether **nonlinear quantum solitons** remain steady-state solutions and how they can serve as resources for quantum information processing.

        **Photon pair generation and coherent control.** I developed **all-fiber sources of multimode correlated photons** using spontaneous four-wave mixing in few-mode fibers, with all-fiber mode sorting for scalable quantum networks. Using programmable multi-plane light converters and mechanical fiber perturbation arrays, we demonstrated reconfigurable control of high-dimensional entangled states and spectral shaping in multimode fibers.

        **Experimental platforms.** The lab's photonics toolbox includes silicon photonics (CMOS-compatible, suitable for squeezing and photon-pair generation), thin-film lithium niobate (high nonlinearity for fast modulation and quantum transducers), SPDC-based photon-pair sources, single-photon detectors, and multimode fiber systems.

        Key contributions include:
        - **Bidirectional soliton rain dynamics**: First observation of Casimir-like acceleration and bidirectional motion of soliton bunches in fiber lasers (Physical Review Letters 2018).
        - **Bound soliton pairs**: Controlled transitions between loosely- and tightly-bound states via noise-mediated interaction potentials (Optica 2022).
        - **Ultrafast rogue waves**: Measurement and modeling of extreme wave events in fiber lasers (Optica 2018).
        - **All-fiber correlated photon sources**: Generation and sorting of multimode photon pairs in few-mode fiber (npj Quantum Information 2022).
        - **Multimode fiber saturable absorbers**: Theory and experiments on bandwidth-induced saturation mechanisms (Optics Letters 2024).
        - **All-fiber wavefront modulation**: Coherent control of light propagation in multimode fibers using mechanical perturbations (J. Phys. Photonics 2023).

        *Key papers: Physical Review Letters (2018), Optica (2018, 2022), npj Quantum Information (2022), Optics Letters (2024)*
---
