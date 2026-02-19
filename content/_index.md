---
title: ''
summary: ''
date: 2024-01-01
type: landing

design:
  spacing: '5rem'

sections:
  - block: resume-biography-3
    content:
      username: me
      text: |
        Kfir Sulimany is an incoming Assistant Professor at the Technion's Andrew and Erna Viterbi Faculty of Electrical & Computer Engineering. He currently leads the Quantum Perception team at MIT's Research Laboratory for Electronics, working with Prof. Dirk Englund. He received his PhD in Physics from the Hebrew University of Jerusalem under Prof. Yaron Bromberg. His multidisciplinary background — spanning quantum information science, photonics, and artificial intelligence — drives his research at the intersection of quantum optics and machine intelligence on physical platforms.
      headings:
        about: ''
        education: ''
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

  - block: markdown
    id: research-highlights
    content:
      title: Research Highlights
      subtitle: ''
      text: |
        <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 1.5rem; margin-top: 1rem;">

        <div style="padding: 1.5rem; border: 1px solid #e5e7eb; border-radius: 0.75rem;">
        <h3 style="margin-top: 0; color: #005BAA;">Quantum-Secure AI & Cryptography</h3>
        <p>Information-theoretically secure deep learning using quantum mechanics, and high-dimensional quantum key distribution protocols.</p>
        <a href="/research/#quantum-secure-ai">Learn more →</a>
        </div>

        <div style="padding: 1.5rem; border: 1px solid #e5e7eb; border-radius: 0.75rem;">
        <h3 style="margin-top: 0; color: #005BAA;">AI for Science & Formal Verification</h3>
        <p>Automated theorem proving in Lean for quantum information theory. Home of the Ax-Prover framework.</p>
        <a href="/research/#ai-for-science">Learn more →</a>
        </div>

        <div style="padding: 1.5rem; border: 1px solid #e5e7eb; border-radius: 0.75rem;">
        <h3 style="margin-top: 0; color: #005BAA;">In-Physics Computing</h3>
        <p>Optical and RF neural networks that perform machine learning directly in the physical domain — at the speed of light.</p>
        <a href="/research/#in-physics-computing">Learn more →</a>
        </div>

        <div style="padding: 1.5rem; border: 1px solid #e5e7eb; border-radius: 0.75rem;">
        <h3 style="margin-top: 0; color: #005BAA;">Quantum & Nonlinear Photonics</h3>
        <p>Soliton dynamics, photon pair generation, coherent control in multimode fibers, and ultrafast laser physics.</p>
        <a href="/research/#quantum-nonlinear-photonics">Learn more →</a>
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

  - block: cta-card
    content:
      title: Join the Quantum Machine Intelligence Lab
      text: |
        I'm building a new research lab at the Technion's ECE faculty — the Quantum Machine Intelligence Lab. I'm looking for motivated PhD students, postdocs, and MSc students to work on quantum-secure AI, in-physics computing, automated theorem proving, and photonics.
      button:
        text: Open Positions
        url: /openings/
    design:
      card:
        css_class: 'bg-primary-700 dark:bg-primary-900'
        css_style: ''
---
