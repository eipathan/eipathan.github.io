---
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

You can find a complete list of my publications on <a href="https://scholar.google.com/citations?user=U7HARQEAAAAJ&hl=en"> Google Scholar, </a> <a href="https://www.researchgate.net/profile/Ei_Pa_Pa_Pe-Than">Research Gate,</a> and <a href="https://epppt.github.io/files/eipa-cv.pdf>CV</a>.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
