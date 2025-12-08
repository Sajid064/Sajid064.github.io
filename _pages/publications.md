---
layout: archive
permalink: /publications/
author_profile: true
---
<h1 style="border-bottom: 2px solid;">Research Interest</h1>

My broad research interests lie in the fields of Trustworthy and Secure AI, Natural Language Processing, and Computer Vision. Some of the specific areas I am interested include:
- Adversarial Machine Learning and Anomaly Detection – studying adversarial attacks and defenses to improve the robustness and security of machine learning models.
- Multilingual and Low-Resource NLP – developing methods to efficiently utilize resources for low- and zero-resource languages.
- Multimodal Learning – integrating text, image, audio, and video modalities for improved representation and understanding.
- Generative Models – applying models such as GANs and diffusion models for intra-modal and cross-modal tasks, including high-quality image reconstruction and synthesis.
<!-- - Cross-Modal Learning, Integrating Visual, Textual, and Acoustic Data for Advanced AI Systems -->

<br>
<h1 style="border-bottom: 2px solid;">Underx Review</h1>
{% include base_path %}

{% for post in site.punder reversed %}

{% endfor %}


<br>
<h1 style="border-bottom: 2px solid;">Publications</h1>
{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="https://scholar.google.com/citations?hl=en&authuser=1&user=HwhiMM8AAAAJ" style="color: #990033;" target="_blank">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
