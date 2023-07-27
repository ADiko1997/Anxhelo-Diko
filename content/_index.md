---
# Leave the homepage title empty to use the site title
title: Anxhelo Diko
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: features
    content:
      title: Skills
      items:
        - name: Machin Learning
          description: 5+ Years

        - name: Deep Learning
          description: 5+ Years

        - name: Computer Vision
          description: 4+ Years

        - name: Research
          description: 3+ Years

        - name: Programming
          description: 5+ Years


  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Research Fellow
          company: Sapienza University of Rome
          company_url: 'https://www.uniroma1.it'
          company_logo: 'Uniroma1'
          location: Rome, Italy
          date_start: '2021-03-01'
          date_end: ''
          description: |2-
              Main responsibilities include:

              * Designing and implementing computer vision solutions for gait analysis  through RGB videos that assist physicians in diagnosing patients with mobility disorders.
              * Designing and implementing machine learning approaches for medical image processing.
              * Designing and implementing machine learning approaches on resource optimization for post-intervention patients.

        - title: Machine Learning Specialist
          company: MedLear srls
          company_url: 'https://medlea-tech.com/'
          company_logo: 'MedLea'
          location: Rome, Italy
          date_start: '2020-03-01'
          date_end: '2021-07-31'
          description: |2-
              Main responsabilities include:
              * Designing and implementing machine learning algorithms for respiratory diagnosis and prognosis by applying classification, regression, and segmentation techniques on CT images and patient medical history. The implemented solutions would provide MedLea with a suite of algorithms that could analyze patient data for different respiratory problems.
              * Deploying machine learning models.
              * Designing and implementing a parallel and scalable Ray-Tracing algorithm for GPUs for discretizing 3D mesh representation of geometries into a volumetric representation. The implemented algorithm would cut the computational costs of the services offered by MedLear by 30\% in the preparation phase.
              * Manage MedLea computing infrastructure

        - title: Machine Learning Intern
          company: PaperClicks
          company_url: 'https://paperclicks.net/'
          company_logo: 'paperclicks'
          location: Rome, Italy
          date_start: '2018-01-08'
          date_end: '2018-07-31'
          description: |2-
              Main Responsabilities include:
              * Responsible for designing and implementing a machine learning algorithm for the optimization of affiliate marketing campaigns enabling automated profits.
 

            
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://udemy-certificate.s3.amazonaws.com/image/UC-2e52ca6d-7475-4fbd-8957-4ad55d8f0065.jpg
          date_end: ''
          date_start: '2021-11-11'
          description: ''
          organization: Udemy
          organization_url: https://www.udemy.com/
          title: Advanced C++ developer
          url: ''

    design:
      columns: '2'

  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

  - block: collection
    content:
      title: Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation

  - block: collection
    content:
      title: Collaboration (inter-disciplinary)
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./collaboration/).
        {{% /callout %}}
      filters:
        folders:
          - collaboration
        exclude_featured: true
    design:
      columns: '2'
      view: citation

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: diko@di.uniroma1.it
      phone: +393497921839
      address:
        street: Via Sorrento
        city: Roma
        region: Lazio
        postcode: '00177'
        country: Italy
        country_code: IT
      directions: Building 11, A side, 21th

  
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
