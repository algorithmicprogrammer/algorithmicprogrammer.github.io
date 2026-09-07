---
title: 'CV'
date: 2026-09-06
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-experience
    content:
      username: me
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: markdown
    content:
      title: Relevant Coursework
      text: |
        <div class="text-base text-gray-600 dark:text-gray-300">
        Big Data Technologies<br>
        Data Preparation and Analysis<br>
        Bayesian Computational Statistics<br>
        Statistical Learning<br>
        Linear Regression
        </div>
    design:
      columns: '1'
  - block: resume-skills
    content:
      title: Skills & Hobbies
      username: me
  - block: resume-awards
    content:
      title: Awards
      username: me
  - block: resume-languages
    content:
      title: Languages
      username: me
---
