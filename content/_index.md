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
        Kfir Sulimany is an incoming Assistant Professor at the Technion's Andrew and Erna Viterbi Faculty of Electrical & Computer Engineering. He is currently a postdoctoral fellow and group leader at MIT's Research Laboratory for Electronics, working with Prof. Dirk Englund. He received his PhD in Physics from the Hebrew University of Jerusalem under Prof. Yaron Bromberg. Before academia, he served nine years in the IDF's Talpiot program, leading R&D teams in the Intelligence Corps.
      button:
        text: Download CV
        url: uploads/resume.pdf
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
        <h3 style="margin-top: 0; color: #005BAA;">Quantum Photonics & Communication</h3>
        <p>High-dimensional quantum key distribution, entangled photon sources, and multimode fiber optics for next-generation secure communication.</p>
        <a href="/research/#quantum-photonics">Learn more →</a>
        </div>

        <div style="padding: 1.5rem; border: 1px solid #e5e7eb; border-radius: 0.75rem;">
        <h3 style="margin-top: 0; color: #005BAA;">Quantum-Secure AI</h3>
        <p>Information-theoretically secure deep learning using quantum mechanics — protecting data during cloud-based AI computation.</p>
        <a href="/research/#quantum-secure-ai">Learn more →</a>
        </div>

        <div style="padding: 1.5rem; border: 1px solid #e5e7eb; border-radius: 0.75rem;">
        <h3 style="margin-top: 0; color: #005BAA;">Nonlinear Fiber Optics</h3>
        <p>Soliton dynamics, mode-locked lasers, and multimode nonlinear phenomena — from Casimir-like interactions to rogue waves.</p>
        <a href="/research/#nonlinear-fiber-optics">Learn more →</a>
        </div>

        <div style="padding: 1.5rem; border: 1px solid #e5e7eb; border-radius: 0.75rem;">
        <h3 style="margin-top: 0; color: #005BAA;">AI for Science</h3>
        <p>Optical neural networks, RF in-physics computing, and AI-driven approaches to scientific discovery.</p>
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

  - block: cta-card
    content:
      title: Join My Lab at the Technion
      text: |
        I'm building a new research lab at the Technion's ECE faculty, working at the intersection of quantum photonics, secure AI, and nonlinear optics. I'm looking for motivated PhD students, postdocs, and MSc students to join the team.
      button:
        text: Open Positions
        url: /openings/
    design:
      card:
        css_class: 'bg-primary-700 dark:bg-primary-900'
        css_style: ''
---
