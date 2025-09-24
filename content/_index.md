---
# Leave the homepage title empty to use the site title
title:
date: 2025-03-01
type: landing

sections:
  # - block: hero
  #   content:
  #     title: Amsterdam Policy Hackathon
  #     text: bottom text
  #     cta:
  #       label: Get Started
  #       url: https://docs.google.com/forms/d/e/1FAIpQLSc6jM8kdDcWxt-Su7DlmraSccM4ZTA4pDgFGnEHH880IyugiA/viewform?usp=dialog
  #       # icon: 📝
  #   design:
  #     spacing:
  #       padding: [0, 0, 0, 0]
  #       margin: [0, 0, 0, 0]
  #     # For full-screen, add `min-h-screen` below
  #     css_class: "dark min-h-screen"
  #     background:
  #       color: "navy"
  #       image:
  #         # Add your image background to `assets/media/`.
  #         filename: bg-amsterdam.jpg
  #         filters:
  #           brightness: 0.5
  - block: hero
    content:
      title: >-
        <div style="color: white; font-family: 'Archive Regular'">Amsterdam Policy Hackathon</div>
      # image:
        # Reference an image in your `assets/media/` folder
        # filename: bg-amsterdam.jpg
      # Add your Call-To-Action (CTA) button and optional icon
      cta:
        label: Stay in the loop
        url: https://forms.gle/iqDdhpaUhu2fL3sU8
        icon_pack: fas
        icon: newspaper
        # class: cta_button
      # Optionally, add an alternative CTA link
      # cta_alt:
      #   label: View challenges
      #   url: /#challenges

      # Optionally, add a note under the Call-To-Action button
      # cta_note:
      #   label: >-
      #     <div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star Hugo Blox Builder</a></div><div style="text-shadow: none;"><a class="github-button" href="https://github.com/wowchemy/starter-hugo-academic" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star the Academic template</a></div>          
      # Add your Hero text here
      text: >-
        <div style="color: white;"><b>A new hackathon focused on interdisciplinary, data-driven policymaking.</b></div><!--Custom spacing--><div class="mb-3"></div><!--GitHub Button JS--><script async defer src="https://buttons.github.io/buttons.js"></script>   
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
        The Amsterdam Policy Hackathon (APH) is a newly founded hackathon event in Amsterdam, the Netherlands. During this 2.5 days competition event, students and young professionals form multidisciplinary teams to develop data-informed policies and/ or policy tools to help with solving the most pressing societal issues in Amsterdam or the Netherlands more broadly. The challenges are provided by both government and industry stakeholders. At the core, the event champions research and policy development at the interdisciplinary intersection between technology and society. The event is inspired by the MIT Policy Hackathon, which is a similar competition held annually at the Massachusetts Institute of Technology in Boston, US.

  # - block: markdown
  #   id: challenges
  #   content:
  #     title: Challenges
  #     text: To be announced, stay tuned!
  - block: markdown
    content:
      title: Thank you to everyone for attending the event!
      subtitle: |
        Are you motivated to work together in a multidisciplinary team of motivated peers to solve some of the most pressing challenges? Participate in the first Amsterdam Policy Hackathon! Register below to stay up to date about APH.
      text: |
        {{% cta cta_link=https://forms.gle/iqDdhpaUhu2fL3sU8 cta_text="Stay in the loop" cta_new_tab="true"%}}
    design:
      columns: '1'
  - block: markdown
    id: partners
    content:
      title: Supported by
      text: >-
        <div class="logos">
          <div class='logos-slide'>
            <a href="https://idss.mit.edu/" target="_blank">
              <img class='logo-image' src="/images/mit.png" alt="Logo for MIT Institute for Data, Systems, and Society (IDSS)"">
            </a>
            <a href="https://vu.nl/" target="_blank">
              <img class='logo-image' src="/images/vu.png" alt="Logo for Vrije Universiteit (VU)"">
            </a>
            <a href="https://recimpact.uva.nl/" target="_blank">
              <img class='logo-image' src="/images/rec_impact.png" alt="Logo for UvA Roeterseilandcampus Impact (REC Impact)"">
            </a>
            <a href="https://dsc.uva.nl/" target="_blank">
              <img class='logo-image' src="/images/uva_dsc.png" alt="Logo for UvA Data Science Center"">
            </a>
            <a href="https://www.amsterdamai.com/nl/" target="_blank">
              <img class='logo-image' src="/images/amsterdamai.png" alt="Logo for Amsterdam AI"">
            </a>
            <a href="https://www.sustainalab.nl/" target="_blank">
              <img class='logo-image' src="/images/sustainalab.png" alt="Logo for Sustainalab"">
            </a>
            <a href="https://kickstart.ai/" target="_blank">
              <img class='logo-image' src="/images/kickstart_ai.png" alt="Logo for Kickstart AI"">
            </a>
            <a href="https://www.tintt.co/" target="_blank">
              <img class='logo-image' src="/images/TINTT.png" alt="Logo for TINTT"">
            </a>
            <a href="https://wearebit.com/" target="_blank">
              <img class='logo-image' src="/images/bit.png" alt="Logo for Bit"">
            </a>
            <a href="https://www.pava.ai/" target="_blank">
              <img class='logo-image' src="/images/pava.png" alt="Logo for PAVA"">
            </a>
            <a href="https://www.ams-institute.org/" target="_blank">
              <img class='logo-image' src="/images/AMS.png" alt="Logo for AMS Institute"">
            <a href="https://iis.uva.nl/en" target="_blank">
              <img class='logo-image' src="/images/iis.jpg" alt="Logo for UvA Institute for Interdisciplenary Studies (IIS)"">
            <a href="https://polder.center//" target="_blank">
              <img class='logo-image' src="/images/polder.png" alt="Logo for Polder Center"">
            </a>
            <a href="https://www.rijksorganisatieodi.nl/i-partnerschap" target="_blank">
              <img class='logo-image' src="/images/ipartnerschap.png" alt="Logo for I-Partnerschap">
            </a>
            <a href="https://www.inaiyan.com/" target="_blank">
              <img class='logo-image' src="/images/INAIYAN.png" alt="Logo for INAIYAN">
            </a>
            <a href="https://www.aisoamsterdam.com/" target="_blank">
              <img class='logo-image' src="/images/AISO.png" alt="Logo for AISO">
            </a>
            <a href="https://www.amsterdam.nl/" target="_blank">
              <img class='logo-image' src="/images/municipality.png" alt="Logo for Gemeente Amsterdam">
            </a>
            <a href="https://www.gelderland.nl/" target="_blank">
              <img class='logo-image' src="/images/gelderland.png" alt="Logo for Provincie Gelderland">
            </a>
            <a href="https://www.amsterdamsciencepark.nl/" target="_blank">
              <img class='logo-image' src="/images/amsterdamSP.png" alt="Logo for Amsterdam Science Park">
            </a>
            <a href="https://benthomas.nl/" target="_blank">
              <img class='logo-image' src="/images/thomas.png" alt="Logo for Thomas van Neerbos">
            </a>
            <a href="https://www.mtelgon.com/roses" target="_blank">
              <img class='logo-image' src="/images/elgon.svg" alt="Logo for Mount Elgon Orchards">
            </a>
            <a href="https://amsterdamdataacademy.com/" target="_blank">
              <img class='logo-image' src="/images/ADA.png" alt="Logo for Amsterdam Data Academy">
            </a>
            <a href="https://nxtmuseum.com/" target="_blank">
              <img class='logo-image' src="/images/NXTmuseum.png" alt="Logo for Nxt Museum Amsterdam">
            </a>
          </div>
        </div>
        <script>
          var copy = document.querySelector(".logos-slide").cloneNode(true);
          document.querySelector(".logos").appendChild(copy);
        </script>
---
