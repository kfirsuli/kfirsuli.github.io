---
title: ''
summary: ''
date: 2024-01-01
type: landing

design:
  spacing: '5rem'

sections:
  - block: resume-biography-3
    id: home-bio
    content:
      username: me
      text: |
        Kfir Sulimany is an incoming Assistant Professor at the Technion's Andrew and Erna Viterbi Faculty of Electrical & Computer Engineering, where he will establish the **[Quantum Machine Intelligence Lab](/research/)**. He currently leads the Quantum Perception team at MIT's Research Laboratory for Electronics, working with Prof. Dirk Englund, and founded the **[Center for Verifiable AI](https://verifiablescience.ai/)** at MIT-Technion. He received his PhD in Physics from the Hebrew University of Jerusalem under Prof. Yaron Bromberg. His research is driven by a single conviction: the physics of information holds the key to solving AI's biggest challenges, from securing data with quantum mechanics to building AI that can prove its own correctness.
      headings:
        about: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: lg
      avatar:
        size: large
        shape: circle

  - block: cta-card
    content:
      title: Join the Quantum Machine Intelligence Lab
      text: |
        We are building a new research lab at the Technion's ECE faculty. We are hiring PhD and MSc students to work on quantum technology, in-physics computing, and AI for science, with a unique opportunity of a ~1 year funded visit to MIT as part of their studies.
      button:
        text: Open Positions
        url: /openings/
    design:
      card:
        css_class: 'bg-primary-500 dark:bg-primary-900'
        css_style: ''

  - block: markdown
    id: research-highlights
    content:
      title: Research Highlights
      subtitle: ''
      text: |
        <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 1.5rem; margin-top: 1rem;">

        <div style="padding: 1.5rem; border: 1px solid #e5e7eb; border-radius: 0.75rem;">
        <h3 style="margin-top: 0; color: #005BAA;">Quantum Technology</h3>
        <p>Quantum cryptography, secure computation, and quantum machine learning on integrated photonic platforms. Security guaranteed by physics, not mathematical assumptions.</p>
        <a href="/research/#quantum-technology">Learn more →</a>
        </div>

        <div style="padding: 1.5rem; border: 1px solid #e5e7eb; border-radius: 0.75rem;">
        <h3 style="margin-top: 0; color: #005BAA;">In-Physics Computing</h3>
        <p>AI faces an energy crisis: data centers consume more electricity than many countries. We build optical and RF neural networks that perform AI directly in the physical domain at a fraction of the energy, and study the fundamental limits of computation.</p>
        <a href="/research/#in-physics-computing">Learn more →</a>
        </div>

        <div style="padding: 1.5rem; border: 1px solid #e5e7eb; border-radius: 0.75rem;">
        <h3 style="margin-top: 0; color: #005BAA;">AI for Science</h3>
        <p>AI makes mistakes. We build AI whose scientific conclusions can be mathematically verified: AI that comes with a proof, not just a prediction. We couple LLMs with the Lean proof assistant for machine-checked discovery, and founded the <a href="https://verifiablescience.ai/">Center for Verifiable AI</a> at MIT-Technion.</p>
        <a href="/research/#ai-for-science">Learn more →</a>
        </div>

        </div>
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
      count: 5
    design:
      view: citation

  - block: collection
    id: news
    content:
      title: Latest News
      subtitle: ''
      text: ''
      page_type: news
      count: 5
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      order: desc
    design:
      view: card
      spacing:
        padding: [0, 0, 0, 0]
---
