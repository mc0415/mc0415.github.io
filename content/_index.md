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
      # Avatar customization
      avatar:
        size: medium  # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
      background:
        color: 
        image:
          # Add your image background to `assets/media/`.
          filename: 'background 2.png'
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
        My research examines the role of Artificial Intelligence in Emergency Communication Centers, with a focus on how these technologies affect operational performance and the delivery of critical public services. 

        More broadly, my interests lie at the intersection of AI, operations management, and public safety systems operating under high-stakes conditions.
        
        Please reach out to collaborate 😃
    design:
      columns: '1'

  - block: markdown
    content:
      title: '👩‍🏫 Teaching Experience'
      subtitle: ''
      text: |-
        <div id = "teaching" style="display: flex; flex-direction: column; gap: 1.5rem;">

          <div style="display: flex;">
            <div style="width: 150px; font-weight: bold;">Fall 2024, Spring 2025, Fall 2025</div>
            <div>
              <span style="font-size: 1rem; font-weight: bold;">Supply Chain Modeling and Optimization</span><br>
              <span style="font-size: 0.9rem;">Teaching Assistant</span><br>
              <span style="font-size: 0.9rem;">McCombs School of Business, University of Texas at Austin</span>
            </div>
          </div>
        </div>
    design:
      columns: '1'


  - block: markdown
    content:
      title: '📬 Contact'
      subtitle: ''
      text: |-
        <div id = "contact" style="display: flex; flex-direction: column; gap: 0.5rem;">
          
          <div> 📩 mchristou@utexas.edu <div>
          <div>📍 2110 Speedway, Austin, TX 78705</div>

          <iframe 
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3445.3482428212633!2d-97.74022612275662!3d30.28414627480375!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8644b59c68123325%3A0x690ca90b0920ae54!2sMcCombs%20School%20of%20Business!5e0!3m2!1sen!2sus!4v1758245356828!5m2!1sen!2sus" 
            width="600" 
            height="450" 
            style="border:0;" 
            allowfullscreen="" 
            loading="lazy" 
            referrerpolicy="no-referrer-when-downgrade">
          </iframe>   

          <div>
            <a href="https://www.mccombs.utexas.edu/" target="_blank">
            McCombs School of Business, University of Texas at Austin
            </a>
          </div>
        </div>
    design:
      columns: '1'

  
      
  #- block: collection
  #  id: papers
  #  content:
  #    title: Featured Publications
  #    filters:
  #      folders:
  #        - publication
  #      featured_only: true
  #  design:
  #    view: article-grid
  #    columns: 2

  #- block: collection
  #  content:
  #    title: Recent Publications
  #    text: ""
  #    filters:
  #      folders:
  #        - publication
  #      exclude_featured: false
  #  design:
  #    view: citation

  #- block: collection
  #  id: talks
  #  content:
  #    title: Recent & Upcoming Talks
  #    filters:
  #      folders:
  #        - event
  #  design:
  #    view: article-grid
  #    columns: 1

  #- block: collection
  #  id: news
  #  content:
  #    title: Recent News
  #    subtitle: ''
  #    text: ''
  #    page_type: post
  #    count: 5
  #    filters:
  #      author: ""
  #      category: ""
  #      tag: ""
  #      exclude_featured: false
  #      exclude_future: false
  #      exclude_past: false
  #      publication_type: ""
  #    offset: 0
  #    order: desc
  #  design:
  #    view: date-title-summary
  #    spacing:
  #      padding: [0, 0, 0, 0]

---