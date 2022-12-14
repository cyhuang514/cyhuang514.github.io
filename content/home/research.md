---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Research Experiences
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Lagrangian Coherent Structures in Flow Past a Backward-Facing Step
    company: Shanghai Jiao Tong University
    company_url: ''
    company_logo: #org-gc
    location: Shanghai, China
    date_start: '2021-09-10'
    date_end: '2022-07-18'
    description: |2-
        Responsibilities include:
        
        * Performed direct numerical simulation of flow past a backward-facing step in a duct using OpenFOAM
        * Uncovered the underlying flow structures by complementary qualitative and quantitative LCS analyses
        * Investigated the interaction between hyperbolic and elliptic structures

        <a></a>

        <a href="https://doi.org/10.1017/jfm.2022.631" target="_blanck">View PDF</a>
    external_link: ''

  - title: Immersed Boundary Method and Applications
    company: Shanghai Jiao Tong University
    company_url: ''
    company_logo: #org-x
    location: Shanghai, China
    date_start: '2021-03-01'
    date_end: '2022-03-01'
    description: |2-
        Responsibilities include:

        * Employed a rotationally oscillating cylinder with an attached flexible filament to approximate tadpole locomotion
        * Developed computational models to simulate this low-Reynolds-number flow based on different immersed boundary frameworks using <a href="https://ibamr.github.io/" target="_blanck">IBAMR</a>
        * Studied the influence of head swing frequency and tail flexibility on the performance of tadpole propulsion

        <a></a>

        <a href="project/tadpole" target="_blanck">View project</a>

  - title: Flow Analysis Based on Lagrangian Coherent Structures (Undergraduate Dissertation)
    company: Shanghai Jiao Tong University
    company_url: ''
    company_logo: #org-x
    location: Shanghai, China
    date_start: '2020-01-01'
    date_end: '2020-06-01'
    description: |2-
        Responsibilities include:

        * Conducted direct numerical simulations of lid-driven cavity flow and pitzDaily flow at different Reynolds numbers
        * Extracted Lagrangian coherent structures based on both heuristic and analytical methods
        * Analyzed physical mechanism behind these two flows from the Lagrangian perspective

  - title: Flow and Magnetic Structures in a Kinematic ABC-Dynamo
    company: Shanghai Jiao Tong University
    company_url: ''
    company_logo: #org-x
    location: Shanghai, China
    date_start: '2019-09-01'
    date_end: '2019-12-01'
    description: |2-
        Responsibilities include:

        * Explored the relationship between the flow skeleton structures and the stagnation points of ABC-flow
        * Visualized their evolutions in the parameter space of ABC-flow through 100 simulations

        <a></a>

        <a href="https://doi.org/10.1007/s11433-019-1568-x" target="_blanck">View PDF</a> | {{< staticref "uploads/abc-flow.gif" "newtab" >}}View animation{{< /staticref >}}

design:
  columns: '2'
---
