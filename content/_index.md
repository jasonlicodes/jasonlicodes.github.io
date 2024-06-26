---
# Leave the homepage title empty to use the site title
title: ""
date: 2023-06-25
type: landing

design:
  # Default section spacing
  spacing: "2rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: View CV
        icon: hero/document
        url: uploads/CV.pdf

  - block: collection
    id: papers
    content:
      title: My Papers
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      # background:
      #   color: '#FAFAFA'
      spacing: 
        padding: ['50px', '20px', '50px', '20px']
      view: citation

  - block: collection
    id: projects
    content:
      title: My Projects
      text: ""
      filters:
        folders:
          - project
        exclude_featured: false
    design:
      spacing: 
        padding: ['50px', '20px', '50px', '20px']
      view: card

---
