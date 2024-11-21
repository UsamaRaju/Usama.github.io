---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        I am a researcher at the LLM Research Group, Department of EEE, BUET, under the supervision of Dr. Mohammad Ariful Haque. My work spans areas like Large Language Models (LLMs), signal processing, robotics, and automation.

        My undergraduate thesis focuses on enhancing generative question-answering systems using fine-tuned LLMs and reinforcement learning from human feedback. Currently, I am engaged in research on RLC circuit recognition and simulation, as well as developing a disease recognition system that utilizes medical image processing with variational encoders and one-class SVM for anomaly detection.
        
        I am passionate about combining theoretical insights with practical applications to solve real-world problems and always eager to collaborate on innovative projects. 😊
    design:
      columns: '1'
 
---
