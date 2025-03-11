---
# Leave the homepage title empty to use the site title
title:
date: 2025-03-01
type: landing

sections:
  - block: hero
    content:
      title: >-
        <div style="color: white; font-family: 'Archive Regular'">Amsterdam Policy Hackathon</div>
      # image:
        # Reference an image in your `assets/media/` folder
        # filename: bg-amsterdam.jpg
      # Add your Call-To-Action (CTA) button and optional icon
      cta:
        label: Apply here!
        url: https://docs.google.com/forms/d/e/1FAIpQLSc6jM8kdDcWxt-Su7DlmraSccM4ZTA4pDgFGnEHH880IyugiA/viewform?usp=dialog
        icon_pack: fas
        icon: right-to-bracket
      # Optionally, add an alternative CTA link
      cta_alt:
        label: View challenges
        url: /#challenges
      # Optionally, add a note under the Call-To-Action button
      # cta_note:
      #   label: >-
      #     <div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star Hugo Blox Builder</a></div><div style="text-shadow: none;"><a class="github-button" href="https://github.com/wowchemy/starter-hugo-academic" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star the Academic template</a></div>          
      # Add your Hero text here
      text: >-
        <div style="color: white;"><b>Participate in the Netherland's first data-driven policymaking hackathon.</b></div><!--Custom spacing--><div class="mb-3"></div><!--GitHub Button JS--><script async defer src="https://buttons.github.io/buttons.js"></script>        
    design:
      # Choose an optional background color, gradient, image, or video
      background:
        image:
          filename: bg-amsterdam.jpg
          filters:
            brightness: 0.5
  
  - block: markdown
    id: about
    content:
      title: About
      text: |-
        The Amsterdam Policy Hackathon (APH) is a newly founded hackathon event in Amsterdam, the Netherlands. During this 2.5 days competition event, students and young professionals form multidisciplinary teams to develop data-informed policies and/ or policy tools to help with solving the most pressing societal issues in Amsterdam or the Netherlands more broadly. The challenges are provided by both government and industry actors. At the core, the event champions research and policy development at the interdisciplinary intersection between technology and society. The event is inspired by the MIT Policy Hackathon, which is a similar competition held annually at the Massachusetts Institute of Technology in Boston, US.
        
        Are you motivated to work together in a multidisciplinary team of motivated peers to solve some of the most pressing challenges? Then apply below!
  - block: markdown
    id: challenges
    content:
      title: Challenges
      text: To be announced, stay tuned!
  - block: markdown
    id: partners
    content:
      title: Partners
      text: >-
        <div class="logo-container">
          <img src="{{ "images/logos/company1.png" | relURL }}" alt="Company 1 Logo">
          <img src="{{ "images/logos/company2.png" | relURL }}" alt="Company 2 Logo">
          <img src="{{ "images/logos/company3.png" | relURL }}" alt="Company 3 Logo">
        </div>
  - block: markdown
    content:
      title: Applications are not open yet!
      subtitle: Do you want to participate in the first Amsterdam Policy Hackathon? Register below and join us in June 2025!
      text: |
        {{% cta cta_link="https://docs.google.com/forms/d/e/1FAIpQLSc6jM8kdDcWxt-Su7DlmraSccM4ZTA4pDgFGnEHH880IyugiA/viewform?usp=dialog" cta_text="Register now! →" cta_new_tab="true"%}}
    design:
      columns: '1'
---
