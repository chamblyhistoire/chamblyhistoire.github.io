---
layout: splash
title: Bienvenue à la page de l'association Chambly Histoire et Patrimoine !

header:
  overlay_image: /assets/images/chambly-home-page-feature-1.jpg
  overlay_filter: 0.5

intro:
  - excerpt: "Bienvenue"

feature_row:
  - image_path: /assets/images/asso-chambly.jpg
    alt: "Notre association"
    title: "Notre association"
    excerpt: ""
    url: /notre-asso/
    btn_label: "Lire"
    btn_class: "btn--primary"

  - image_path: /assets/images/blog.jpg
    alt: "Blog"
    title: "Dernier post du blog"
    excerpt: ""
    url: "{{ latest_post.url }}"
    btn_label: "Lire"
    btn_class: "btn--primary"

  - image_path: /assets/images/Galerie.jpg
    alt: ""
    title: "Galerie d'images"
    excerpt: ""
    url: /galerie/
    btn_label: "Voir la galerie"
    btn_class: "btn--primary"
    
---

{% assign latest_post = site.posts.first %}

{% include feature_row %}


