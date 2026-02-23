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
        Kfir Sulimany is an incoming Assistant Professor at the Technion's Andrew and Erna Viterbi Faculty of Electrical & Computer Engineering, where he is building the **Quantum Machine Intelligence Lab**. He currently leads the Quantum Perception team at MIT's Research Laboratory for Electronics, working with Prof. Dirk Englund. He received his PhD in Physics from the Hebrew University of Jerusalem under Prof. Yaron Bromberg. His multidisciplinary background spanning quantum information science, photonics, and artificial intelligence drives his research at the intersection of quantum optics and machine intelligence on physical platforms.
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
        css_class: 'bg-primary-700 dark:bg-primary-900'
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
        <p>Quantum cryptography, secure quantum computation, and quantum machine learning — from provably secure QKD to information-theoretically secure deep learning.</p>
        <a href="/research/#quantum-technology">Learn more →</a>
        </div>

        <div style="padding: 1.5rem; border: 1px solid #e5e7eb; border-radius: 0.75rem;">
        <h3 style="margin-top: 0; color: #005BAA;">In-Physics Computing</h3>
        <p>Optical and RF neural networks that perform machine learning directly in the physical domain, and the fundamental energy limits of computation.</p>
        <a href="/research/#in-physics-computing">Learn more →</a>
        </div>

        <div style="padding: 1.5rem; border: 1px solid #e5e7eb; border-radius: 0.75rem;">
        <h3 style="margin-top: 0; color: #005BAA;">AI for Science</h3>
        <p>LLM-driven automated theorem proving in Lean, and a formal library for quantum information theory.</p>
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
