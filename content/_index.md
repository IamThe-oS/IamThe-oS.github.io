---
title: 'Home'
date: 2024-09-07
type: landing

design:
  # Default section spacing
  spacing: "4rem"

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: biography
    id: biography
    content:
      username: admin
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download Resume
        url: uploads/resume.pdf
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: kalen-emsley-Bkci_8qcdvQ-unsplash.jpg
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 01.2em;'

sections:
  - block: experience
    id: experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false

sections:
  - block: skills
    id: skills
    content:
      title: Skills & Hobbies
      username: admin

sections:
  - block: certificates
    id: certificates
    content:
      title: Certificates
      username: admin

sections:
  - block: languages
    content:
      title: Languages
      username: admin
---
