---
title: Anjali Chandra — Maroon CV Home
date: 2026-06-25
summary: "Academic homepage for Anjali Chandra with maroon accent, Roboto font, and hero photo on the right."
type: landing
sections:
  - block: hero
    content:
        eyebrow: Welcome
        title: Anjali Chandra
        text: "Researcher, educator, and lifelong learner focused on advancing knowledge and fostering curiosity. Explore my work in research and teaching below."
        primary_action:
          text: See Research
          url: "#research"
        secondary_action:
          text: Contact Me
          url: "#contact"
        media:
          type: image
          src: hero.jpg
          alt: Portrait of Anjali Chandra
    design:
        layout: split-right
        alignment: left
        size: tall
    id: home
  - block: markdown
    content:
        title: About Me
        text: "Hello! I'm Anjali Chandra. My academic interests span multiple domains, and I'm passionate about making a positive impact through research and teaching. Learn more about my journey, values, and vision on this site."
    id: about
  - block: collection
    content:
        title: Research
        text: "Highlighted work, publications, and ongoing projects."
        page_type: publication
        count: 3
        archive:
          enable: true
          text: See all publications
          link: /publication/
    design:
        view: card
    id: research
  - block: markdown
    content:
        title: Teaching
        text: "Dedicated to providing an engaging, supportive learning environment. Browse courses, resources, and teaching philosophy."
    id: teaching
  - block: markdown
    content:
        title: Awards
        text: Recognition and awards received for academic and research excellence.
    id: awards
  - block: markdown
    content:
        title: Contact
        text: "Feel free to reach out for collaborations or inquiries. [Email me](mailto:your@email.com)."
    id: contact
---
