---
layout: archive
permalink: /publications/
author_profile: true
---
<h1 style="border-bottom: 2px solid;">Research Interest</h1>

My broad research interests lie in the fields of Computer Vision and Natural Language Processing. Some of the specific areas I am eager to explore include:
- Adversarial Attacks and Defense Mechanisms, Robustness and Security of Machine Learning Models
- Multilingual NLP, Efficient Utilization of Resources for Low- and Zero-Resource Languages
- Digital Image Processing, Enhancing Image Quality and Detection Techniques
<!-- - Cross-Modal Learning, Integrating Visual, Textual, and Acoustic Data for Advanced AI Systems -->

<br>
<h1 style="border-bottom: 2px solid;">Publications</h1>
{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="https://scholar.google.com/citations?hl=en&authuser=1&user=HwhiMM8AAAAJ" style="color: #990033;" target="_blank">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
