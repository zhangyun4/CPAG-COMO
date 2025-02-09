---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: 2025 China Night  2025 哥城春晚
      text: 🧱 Feb. 1st, Missouri Theater | Free Tickets  🧱
      #primary_action:
      #  text: Get Started
      #  url: https://hugoblox.com/templates/
      #  icon: rocket-launch
      #secondary_action:
      #  text: Read the docs
      #  url: https://docs.hugoblox.com
      announcement:
        text: "Announcing the release of Program Lists"
        link:
          text: "Read more"
          url: "/blog/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "red"
        image:
          # Add your image background to `assets/media/`.
          filename: bg_newyear.svg
          filters:
            brightness: 0.5
  - block: stats
    content:
      items:
        - statistic: "CSSA"
          description: |
            Chinese student Association
            at MIZZOU
        - statistic: "MMCA"
          description: |
            Mid-Missouri Chinese Associatation
        - statistic: "CFC"
          description: |
            Columbia Friends of China 
            Best Friend:)
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
#  - block: features
#    id: features
#    content:
#      title: Features
#      text: Build your site with blocks 🧱
#      items:
#        - name: Optimized SEO
#          icon: magnifying-glass
#          description: Automatic sitemaps, RSS feeds, and rich metadata take the pain out of SEO and syndication.
#        - name: Fast
#         icon: bolt
#          description: Super fast page load with Tailwind CSS and super fast site building with Hugo.
#        - name: Easy
#          icon: sparkles
#          description: One-click deployment to GitHub Pages. Have your new website live within 5 minutes!
#        - name: No-Code
#          icon: code-bracket
#          description: Edit and design your site just using rich text (Markdown) and configurable YAML parameters.
#        - name: Highly Rated
#          icon: star
#          description: Rated 5-stars by the community.
#        - name: Swappable Blocks
#          icon: rectangle-group
#          description: Build your pages with blocks - no coding required!
  - block: cta-image-paragraph
    id: descriptions
    content:
      items:
        - title: Traditional Chinese Culture and Dance
          text: Real Chinese !
          feature_icon: check
          features:
            - "Chinese Dance"
            - "Chinese Songs"
          # Upload image to `assets/media/` and reference the filename here
          image: lamp.jpg
          #button:
          #  text: Get Started
          #  url: https://hugoblox.com/templates/

        - title: Gala from Local Chinese Community
          text: Join our large community gala - Unforgetable Night
          feature_icon: bolt
          features:
            - "One of the most friendly community at COMO"

          # Upload image to `assets/media/` and reference the filename here
          image: tiger.jpg
          #button:
          #  text: Join Discord
          #  url: https://discord.gg/z8wNYzb
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: testimonials
    content:
      title: ""
      text: ""
      items:
        - name: "Tom"
          role: "student at Mizzou"
          # Upload image to `assets/media/` and reference the filename here
          image: "testimonial-1.jpg"
          text: "Awesome, Best Gala I have ever seen!"
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]
  - block: cta-card
    content:
      title: Participate US ASAP
      text: As easy as 1, 2, 3!
      button:
        text: Get Started
        url: https://comochinanight.netlify.app/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
