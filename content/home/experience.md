---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
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
  - title: Software Engineering Intern
    company: Meta
    company_url: 'https://meta.com/'
    company_logo: meta
    location: Menlo Park, CA
    date_start: '2022-06-01'
    date_end: ''
    description: 
  - title: Research Assistant
    company: Intelligent Automation Lab, Carnegie Mellon University
    company_url: 'https://labs.ri.cmu.edu/iam/'
    company_logo: iam
    location: Pittsburgh, PA
    date_start: '2021-01-01'
    date_end: ''
    description: |2-
        * Exploring the application of information compression in reinforcmenet learning algorithms for learning robust policies for robot manipulation tasks
        * Investigated the use of disentangled representation learning for dynamics model to see if it leads to better generalization
        * Developed a matrix‑based toy environment in OpenAI Gym to stress test causal reasoning algorithms


  - title: Software Engineering Intern
    company: Omnipresent Technologies
    company_url: 'http://www.omnipresenttech.com/'
    company_logo: omni
    location: Pune, India
    date_start: '2020-09-01'
    date_end: '2021-01-01'
    description: |2-
        * Led a team of three to design and implemented a fault tolerant controller for a quadcopter in simulation that prevents crashing after single motor failure.
        * Implemented safety compliance software in the PX4 firmware to satisfy government regulations such as avoiding no‑fly zones and verifying digital certificates
        
  - title: Software Engineering Intern
    company: Uber Advanced Technologies Group
    company_url: 'https://aurora.tech/'
    company_logo: uber
    location: Pittsburgh, PA
    date_start: '2020-05-01'
    date_end: '2020-08-01'
    description: |2-
        * Developed a tool in C++ that analyzes quantitative and visual analysis of the differences between inferred ground generated from point cloud data
        * Analyzed pipeline that generates inferred ground from point cloud data to identify and eliminate unneccesary steps, optimizing for runtime and quality of output. 

  - title: Research Assistant
    company: Human and Robot Partners Lab, Carnegie Mellon University
    company_url: 'https://harp.ri.cmu.edu/'
    company_logo: RI_small
    location: Pittsburgh, PA
    date_start: '2018-10-01'
    date_end: '2019-10-01'
    description: |2-
        * Built a restaurant simulator using V‑REP to use as a testing platform for robot waiters
        * Designed and ran a Human‑Robot Interaction study that used eye gaze information from participants to predict their intent and use robot gestures to manipulate it. 
        
design:
  columns: '2'
---
