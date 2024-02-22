---
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

<p>You can find a complete list of my publications on &nbsp;<a href="https://scholar.google.com/citations?user=U7HARQEAAAAJ&hl=en">Google Scholar</a>,&nbsp;<a href="https://www.researchgate.net/profile/Ei_Pa_Pa_Pe-Than">Research Gate</a>,&nbsp;and&nbsp;<a href="https://epppt.github.io/files/cv-epppt.pdf">my CV</a>.</p>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
