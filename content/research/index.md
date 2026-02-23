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
        We aim to advance the second quantum revolution in the AI era by developing novel information-processing protocols and demonstrating them on physical platforms, with a dual track: harvesting classical gains now while advancing the protocols and hardware needed for scalable, fault-tolerant quantum information processing.

        <div style="border-left: 4px solid #005BAA; padding: 1rem 1.5rem; margin: 2rem 0;">

        **1. [Quantum Technology](#quantum-technology)**
        - [Quantum Cryptography & Secure Computation](#quantum-cryptography)
        - [Quantum Computation](#quantum-computation)
        - [Quantum Machine Learning](#quantum-machine-learning)

        **2. [In-Physics Computing](#in-physics-computing)**
        - [Optical Machine Learning](#optical-machine-learning)
        - [AI Accelerators](#ai-accelerators)
        - [Fundamental Limits of Computation](#fundamental-limits)

        **3. [AI for Science](#ai-for-science)**
        - [Automated Theorem Proving](#automated-theorem-proving)
        - [Formal Quantum Information Theory](#formal-quantum-info)

        </div>

        <h2 id="quantum-technology">1. Quantum Technology</h2>

        The second quantum revolution promises advances in communication, computation, and sensing, driven by quantum information processing that harnesses superposition and entanglement. These fundamental quantum properties were first demonstrated in pioneering experiments with photons in the 1970s and 1980s, recognized by the 2022 Nobel Prize in Physics. Photons have emerged as ideal carriers for quantum information, and integrated photonic circuits are central to scaling both quantum and classical information processing.

        <h3 id="quantum-cryptography">Quantum Cryptography</h3>

        <figure style="float: right; margin: 0 0 1rem 1.5rem; max-width: 280px;">
        <img src="quantum-secure-dl.jpg" alt="Quantum-secure multiparty deep learning" style="width: 100%; border-radius: 0.5rem;">
        <figcaption style="font-size: 0.8rem; color: #6b7280; margin-top: 0.4rem; text-align: center;">Image credit: Sampson Wilcox</figcaption>
        </figure>

        Quantum cryptography uses the laws of quantum mechanics to guarantee information security — not through the computational difficulty of breaking a code, but through the fundamental physics of measurement and entanglement. Any eavesdropper necessarily disturbs the quantum states being transmitted, making interception detectable in principle. This is the basis of quantum key distribution (QKD), which allows two parties to establish a shared secret key with **information-theoretic security**: security that holds even against an adversary with unlimited computational power. Our work in QKD integrates theory and experimentation, co-optimizing every stage from security proofs to hardware implementation. We advance **high-dimensional QKD**, encoding information in multiple degrees of freedom of single photons (time bins, orbital angular momentum, spatial modes) to achieve higher secret key rates, and have demonstrated protocols that double key rates using only commercial off-the-shelf components over standard telecom fiber.

        Beyond secure communication, quantum mechanics also enables fundamentally new forms of **secure computation**. In secure multiparty computation, several parties jointly evaluate a function while keeping their inputs private — for example, a hospital classifying a patient's data using a server-owned model without either party revealing their private information. We pioneered an **information-theoretically secure computation scheme** using conventional telecom components, with analytical upper bounds on information leakage for both neural-network weights and client inputs. At the quantum limit, where mode occupation approaches the vacuum level, we exploit vacuum fluctuations for secure computation via **nondemolition computation** based on optical nonlinearity. Our **quantum-secure multiparty deep learning** protocol was published in *Physical Review X* (2025) and covered by [MIT News](https://news.mit.edu/2024/new-security-protocol-shields-data-during-cloud-based-computation-0926), [Tech Briefs](https://www.techbriefs.com/component/content/article/52065-new-security-protocol-protects-cloud-based-server-data), ScienceDaily, Phys.org, and SciTechDaily.

        <h3 id="quantum-computation">Quantum Computation</h3>

        A central question in quantum information science is: which problems can a quantum computer solve faster than any classical one? For structured problems like integer factoring, quantum algorithms offer an exponential advantage, while for unstructured search the speedup is only polynomial. Between these extremes lies a large, largely unmapped space of partially structured problems. A core aim of our lab is to identify which physical resources convert partial structure into provable quantum advantage.

        Integrated photonics is emerging as one of the most promising platforms for building scalable quantum processors. Our experimental work is built on two complementary foundry platforms: **silicon photonics** (CMOS-compatible, low-loss, suitable for squeezing and photon-pair generation) and **thin-film lithium niobate** (high nonlinearity enabling fast modulation, spontaneous parametric down-conversion, quantum transducers, and nondemolition gates). These platforms support the generation, manipulation, and detection of quantum states of light on a chip — the essential building blocks for photonic quantum computing. We develop coherent photonic control tools for quantum information processing, including all-fiber sources and sorters for multimode correlated photons and programmable processing of high-dimensional entangled states, and are currently validating nondemolition computation in thin-film lithium niobate photonic-crystal cavities.

        <h3 id="quantum-machine-learning">Quantum Machine Learning</h3>

        Quantum machine learning (QML) sits at the intersection of quantum computing and artificial intelligence. Building on theoretical speedups and a growing photonic QML community, we translate these concepts into practical experiments. Where much QML work assumes large-scale, fault-tolerant quantum computers or unrealistic models, our testbed consists of fully functional optical computers that already solve hard problems efficiently. We explore what becomes achievable with realistic squeezing and non-Gaussian operations — in spirit, this mirrors LIGO, where a robust classical detector is quantum-enhanced by modest squeezing.

        <h2 id="in-physics-computing">2. In-Physics Computing</h2>

        Analog computing has been studied for decades, but the demand for high precision kept practical systems in the digital domain. That constraint has now relaxed: today's machine-learning models rely on 8-bit or even 4-bit arithmetic, well within analog reach. This opens the door to computing architectures that perform machine learning **directly in the physical domain** — using optical and radio-frequency hardware to execute neural-network operations at the speed of light, with immediate energy-cost advantages over digital electronics.

        <h3 id="optical-machine-learning">Optical Machine Learning</h3>

        Optics is uniquely promising for machine learning because the core operation of neural networks — matrix-vector multiplication — maps naturally onto the physics of light propagation. A beam of light passing through a mesh of interferometers or scattering through a diffractive layer performs a linear transformation at the speed of light, consuming energy only for the light source and detectors, not for the computation itself. This is why optical neural networks have attracted intense interest from both academia and industry as a path to AI inference that is orders of magnitude more energy-efficient than electronic processors.

        Rather than adapting analog hardware to run digital-era models, we propose the inverse: **design hardware-tailored AI models natively suited to optics**. The cornerstone of our approach is **digital twins** — differentiable AI-based virtual replicas of physical systems synchronized in real time with experimental data. Training these twins end-to-end lets us co-optimize hardware and algorithms simultaneously, discover photonics-tailored architectures, and accelerate experimental discovery. We develop optical neural networks based on quadrature amplitude modulation for high-throughput inference and nanophotonic integrators that implement neural-network primitives directly in silicon.

        <h3 id="ai-accelerators">AI Accelerators</h3>

        Optics already plays a growing role in AI infrastructure: optical interconnects carry data between GPUs in modern data centers, and photonic tensor cores are being developed by startups and major labs to accelerate matrix operations. We push this further by exploring **unconventional physical substrates** for neural-network inference. In recent work, we demonstrated that a cellphone's RF front-end — its antenna, filters, mixers, and amplifiers — can perform real-time deep-learning inference when the model is streamed over the air, eliminating on-device memory and dedicated AI hardware entirely. This **disaggregated in-physics computing** paradigm opens the door to AI inference on any device with a radio, from IoT sensors to satellites, and was published in *Science Advances* (2026).

        The same principle applies broadly: any physical system whose input-output relationship is differentiable can, in principle, be trained as a computing element. We co-design analog electronics with photonics for in-physics AI accelerators that exploit the native physics of signal propagation rather than fighting it.

        <h3 id="fundamental-limits">Fundamental Limitations of Computation</h3>

        A fundamental question drives this entire research direction: *What is the irreducible energy required to complete a computational task within finite temperature, time, and space, and how close can physical systems push us to that limit?*

        Classical complexity theory classifies problems in abstract, unitless time and space, largely ignoring energy — the resource that dominates advanced computing today. Physics offers a richer lens. In the spirit of Szilard, Landauer, and Bennett, we go beyond the abstractions of computer science and bring thermodynamics back into the foundation. **Landauer's principle** states that erasing a single bit of information at temperature *T* dissipates at least *kT* ln 2 joules of energy — a bound set by the second law of thermodynamics. This seemingly tiny quantity, roughly 3 × 10⁻²¹ joules at room temperature, represents the absolute physical floor of computation. Today's transistors dissipate roughly a million times more energy per operation, so the gap is enormous — but closing it requires fundamentally rethinking how we compute.

        We study these thermodynamic and information-theoretic bounds on computation, connecting Landauer's principle and finite-time thermodynamics to the physics of noise, to understand the ultimate efficiency of analog and optical processors. This theoretical thread informs the design of all our in-physics computing platforms and tells us how far we are from the physical limits of what is possible.

        <h2 id="ai-for-science">3. AI for Science</h2>

        A core direction of our research is using AI not just as a tool, but as a **partner in scientific discovery**. The central idea is that large language models, when connected to formal verification systems, can do more than generate text — they can construct and verify rigorous mathematical proofs, accelerating the pace at which we can establish new theoretical results in physics and mathematics.

        <h3 id="automated-theorem-proving">Automated Theorem Proving</h3>

        Automated theorem proving (ATP) encodes mathematical statements in formal logic and uses algorithmic inference to verify or discover proofs. Despite recent progress in both LLMs and proof assistants like Lean, existing systems cannot yet certify the security or functionality of quantum schemes — the proofs are too specialized, too long, and require deep domain expertise that general-purpose models lack.

        Our approach bridges this gap by building **multi-agent frameworks** that equip LLMs with the tools of the Lean proof assistant. The model can inspect proof goals, search for relevant lemmas in a formalized library, and generate verified proof steps — all within a feedback loop where the proof assistant checks every step for correctness. This methodology has two powerful properties: it leverages the creativity and pattern recognition of LLMs while demanding the rigor of formal verification, and it scales to domains where human expertise is scarce. We have demonstrated this approach on benchmarks in abstract algebra and quantum theory, and as a human-AI collaboration tool that helped an expert mathematician formalize and machine-check a complex cryptography theorem in ~2,000 lines of Lean over two working days.

        The impact extends far beyond mathematics. Formal verification can certify that a quantum protocol is truly secure, that an optimization algorithm converges, or that a physical model satisfies conservation laws — tasks that are currently performed by human peer review, with all its limitations. By automating this process, we aim to accelerate the cycle of conjecture, proof, and discovery across the sciences.

        <h3 id="formal-quantum-info">Formal Quantum Information Theory</h3>

        We recently formalized, to our knowledge, **the first QKD security proof in Lean** — machine-checking the mathematical argument that guarantees the security of a quantum communication protocol. This milestone demonstrates that formal verification of quantum information theory is not only possible but practical.

        We are now building a **Lean library for quantum information theory**, formalizing key results in quantum cryptography, entanglement theory, and quantum error correction. This library serves a dual purpose: it provides a verified foundation that other researchers can build on with confidence, and it creates a knowledge base that AI agents can search and extend. The long-term vision is **automated discovery of advanced primitives** — secure multiparty computation protocols, new QKD schemes, and error correction codes — where AI-guided formal reasoning explores proof spaces far larger than any human could navigate, with every step machine-verified for correctness.
---
