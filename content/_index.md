---
title: 'Home'
date: 2023-04-03
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Build Your IoT solutions with Sigphase
      text: AI powered IoT Remote Monitoring
      primary_action:
        text: Devices
        url: https://sigphase.com/devices/
     #  icon: rocket-launch
      secondary_action:
        text: Sensors
        url: https://sigphase.com/sensors/
      announcement:
        text: "Learn more about Sigphase"
        link:
          text: "Read more"
          url: "https://sigphase.com/about-us/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: bg-triangles.svg
          filters:
            brightness: 0.5
  - block: stats
    content:
      items:
        - statistic: " "
          description: |
            Industry leading  
            Sensors and Devices
        - statistic: ""
          description: |
            since  
            2014
        - statistic: " "
          description: |
            Completely  
            Customizable
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem",0 , "1rem", 0]
  - block: features
    id: features
    content:
      title: Features
      text: Build your IoT solutions with Sigphase
      items:
        - name: Precise
          icon: magnifying-glass
          description: Improved sensor provides a robust tool for sensing and monitoring.
        - name: Fast
          icon: bolt
          description: Super fast response with Sigphase.
        - name: Easy
          icon: sparkles
          description: Easy deployment!
        - name: Ultra Low
          icon: code-bracket
          description: Long Battery Life IoT Sensing.
        - name: Reliable
          icon: star
          description: Better reliability and robustness.
        - name: Swappable
          icon: rectangle-group
          description: Customizable, built to your requirements!
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: AI powered IoT Remote Monitoring
          text: Customizable, built to your requirements!
          feature_icon: check
          features:
            - "Precise"
            - "Customizable"
            - "AI powered"
          # Upload image to `assets/media/` and reference the filename here
          image: build-website.png
          button:
            text: Sigphase Shop
            url: https://Sigphase.com/shop/


---
