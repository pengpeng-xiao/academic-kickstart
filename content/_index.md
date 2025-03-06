---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "5rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      # button:
      #   text: Download CV
      #   url: uploads/resume.pdf
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
      title: '🔬 My Research'
      subtitle: ''
      text: |-
        <div style="font-size: 1.0em;">

        My research journey began in **high-energy phenomenology**, where I explored fundamental physics and learned so much about the smallest scales of the universe. Over time, my interests expanded to the interplay between **physics and AI**, including the theoretical foundations of deep learning and quantum machine learning. Currently, I am particularly fascinated by the intersection of **generative AI and PDEs**, exploring how these techniques can enhance scientific computing and discovery. 

        I'm always open to collaborations! Feel free to reach out via **email** (p.xiao@yale.edu) or **WeChat** (luuuuuhan777) 😃 
        </div>
    design:
      columns: '1'

  - block: markdown
    id: news
    content:
      title: "What's New?"
      subtitle: ''
      text: |-
        <div style="font-size: 0.87em;">

        **[Feb 28, 2024]** 🎤 Presented *Quantum DeepONet* at the [CRUNCH Seminar](https://www.youtube.com/watch?v=54orRsJuFrU&t=67s).  

        **[Nov 28, 2024]** 📄 Our paper [LD-EnSF](https://arxiv.org/abs/2411.19305) is now on arXiv!  

        **[Oct 23, 2024]** 🎤 Presented a poster on *Quantum DeepONet* at [SIAM MDS](https://www.siam.org/conferences-events/siam-conferences/mds24/) in Atlanta.  

        **[Oct 16, 2024]** 🎤 Gave a talk on *LD-EnSF* at [ROM+ML4LES+](https://math.emory.edu/site/romml4les/) at Emory.  

        **[Sep 24, 2024]** 📄 My first paper [Quantum DeepONet](https://arxiv.org/abs/2409.15683) is now on arXiv!  

        </div>
    design:
      columns: '2'
      view: compact

    #   # Page type to display. E.g. post, talk, publication...
    #   page_type: post
    #   # Choose how many pages you would like to display (0 = all pages)
    #   count: 0
    #   # Filter on criteria
    #   filters:
    #     author: ""
    #     category: ""
    #     tag: ""
    #     exclude_featured: false
    #     exclude_future: false
    #     exclude_past: false
    #     publication_type: ""
    #   # Choose how many pages you would like to offset by
    #   offset: 0
    #   # Page order: descending (desc) or ascending (asc) date.
    #   order: desc
    # design:
    #   container_width: "1000px"
    
  # - block: collection
  #   id: news
  #   content:
  #     title: "What's New?" 
  #     subtitle: ''
  #     text: ''
  #     count: 0  # ✅ 设置 count 为 0，避免 Hugo 试图填充动态内容
  #   items:  # ✅ 确保 items 被识别
  #     - date: "2024-09-20"
  #       icon: "🎉"
  #       text: "2 papers (AgentReview and CPPLM) accepted to EMNLP'24 main track."
  #     - date: "2024-07-15"
  #       icon: "🎉"
  #       text: "1 paper FairGAD accepted at CIKM'24."
  #     - date: "2024-05-15"
  #       icon: "🎉"
  #       text: "2 papers MM-Soc and Proto-RM accepted at ACL'24."
  #     - date: "2024-05-06"
  #       icon: "💻"
  #       text: "Joined Adobe as a Research Intern in San Jose, CA."
  #     - date: "2024-05-01"
  #       icon: "🎉"
  #       text: "1 paper CompeteAI accepted at ICML'24 Oral."
  #     - date: "2024-04-01"
  #       icon: "📢"
  #       text: "Our WebConf2024 Project on Cross-Lingual Evaluation of LLMs is featured at Scientific American and The World."
  #     - date: "2024-01-23"
  #       icon: "🎉"
  #       text: "1 paper XLingEval accepted at The Web Conference 2024."
  #   design:
  #     view: compact  # ✅ 选择一个适合 `items` 的布局，比如 `compact`
  #     spacing:
  #       padding: [0, 0, 0, 0]

      # # Page type to display. E.g. post, talk, publication...
      # page_type: post
      # # Choose how many pages you would like to display (0 = all pages)
      # count: 5
      # # Filter on criteria
      # filters:
      #   author: ""
      #   category: ""
      #   tag: ""
      #   exclude_featured: false
      #   exclude_future: false
      #   exclude_past: false
      #   publication_type: ""
      # # Choose how many pages you would like to offset by
      # offset: 0
      # # Page order: descending (desc) or ascending (asc) date.
      # order: desc
    # design:
    #   # Choose a layout view
    #   view: date-title-summary
    #   # Reduce spacing
    #   spacing:
    #     padding: [0, 0, 0, 0]

  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent Talks
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1
 
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!
        
        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
