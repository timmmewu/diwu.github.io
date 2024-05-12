---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: experience
    content:
       title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Research Assistant
          company: China Data Lab, 21st Century China Center, UC San Dan Diego
          company_url: ''
          company_logo: 
          location: San Diego, California, US
          date_start: '2022-12-01'
          date_end: ''
          description: |2-
              Responsibilities include:
              * Develop Natural Language Processing Algorithm to conduct Topic Modelling on streaming corpora with millions of newspapers articles using machine learning frameworks
              * Analyze the Chinese Local Bond Market using time series analysis, and fixed effect regressions
              * Enhance an Elite Database by scraping data from external official Chinese Government websites and applying GPT API calls to extract relevant information
        - title: Software Engineering Research Intern
          company: German Aerospace Center
          company_url:
          company_logo:
          location: Jena, Germany
          date_start: '2022-06'
          date_end: '2022-08'
          description: Developed machine learning type inference algorithm by combining machine learning and novelty detection, achieved high assurance F1 scores for automated type inference
        - title: Research Project Manager
          company: The Hebrew Univeristy of Jerusalem
          company_url:
          company_logo:
          location: Jerusalem, Israel
          date_start: '2021-08'
          date_end: '2022-09'
          description: Developed computational pipelines in Python using NLP models, Data Mining, Big Data Analysis, and Machine Learning
    design:
      columns: '2'
---
