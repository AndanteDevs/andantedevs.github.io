---
layout: splash
permalink: /portfolio
header:
  overlay_color: "#5e616c"
  overlay_filter: "0.5"
  overlay_image: /assets/images/home-banner.png
#  actions:
#    - label: "Projects"
#      url: "https://andantedevs.github.io/projects/"
excerpt: That guy with too much free time
#intro:
#  - excerpt: ""
origami:
  - image_path: /assets/images/origami-games-banner.png
    alt: "origami-games-banner.png"
    title: "Origami Games"
    excerpt: 'Founder of and developer at Origami Games'
    url: "https://origami-games.github.io"
    btn_label: "Website"
    btn_class: "btn--primary"
artefact:
  - image_path: /assets/images/artefact-feature-row.png
    alt: "artefact-feature-row.png"
    title: "Artefact"
    excerpt: 'An RPG created in vanilla Minecraft'
    url: "https://origami-games.github.io/artefact"
    btn_label: "Read more..."
    btn_class: "btn--primary"
launch:
  - image_path: /assets/images/launch-feature-row.png
    alt: "launch-feature-row.png"
    title: "Launch"
    excerpt: 'A space-themed survival data pack for Minecraft'
    url: "https://origami-games.github.io/launch"
    btn_label: "Read more..."
    btn_class: "btn--primary"
---

{% include feature_row id="origami" type="left" %}
{% include feature_row id="artefact" type="right" %}
{% include feature_row id="launch" type="left" %}
