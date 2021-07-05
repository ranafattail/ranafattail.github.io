---
permalink: /
hidden: true
layout: splash
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/cafe.jpg
  actions:
    - label: "Réserver"
      url: /concept/
  caption: "30 Rue des Volontaires, 75015 Paris"
excerpt: "Chat Mallows Café, bar à chats à Paris, un lieu dédié aux chats où vous n'êtes que l'invité 🐱"
intro:
  - excerpt: "**Réservation obligatoire**. 30 Rue des Volontaires, 75015 Paris, du mercredi au dimanche de 12h00 à 20h00."
concept:
  - image_path: /assets/images/jessie.png
    alt: "Concept"
    title: "Concept"
    excerpt: "**Le Chat Mallows Café** est un salon de thé peuplé d'une quinzaine de chats d'origines diverses en **totale liberté**. La particularité de ce « bar à chat » réside dans son approche très orientale du concept."
    url: /concept/
    btn_label: "Plus d'information"
    btn_class: "btn--success"
chats:
- image_path: /assets/images/chats.png
  alt: "Chats"
  title: "Chats"
  excerpt: "Les pensionnaires ont été sélectionnés pour leur comportement docile ou joueur et leur capacité à vivre en communauté."
  url: /chats/
  btn_label: "Qui sont les chats ?"
  btn_class: "btn--info"
chats:
- image_path: /assets/images/carte.png
  alt: "Carte"
  title: "Carte"
  excerpt: "Tout en savourant boissons, collations sucrées ou salées, vous pourrez laisser se nouer la relation avec les maîtres des lieux."
  url: /carte/
  btn_label: "Montrez-moi votre carte !"
  btn_class: "btn--success"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row id="concept" type="left" %}

{% include feature_row id="chats" type="right" %}
