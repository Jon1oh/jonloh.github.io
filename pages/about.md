---
layout: page
title: Resume
permalink: /resume/
weight: 1
---

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons/font/bootstrap-icons.css">
<link rel="stylesheet" href="{{ '/assets/css/styles.css' | relative_url }}" />

<div class="row d-flex flex-column flex-md-row align-items-center">
  <div class="col-12 col-md-6 mb-3 mx-auto flex-shrink-0">
    <img src="{{ '/assets/img/static/jon.jpeg' | relative_url }}" alt="Jon Loh" class="img-fluid fade-in custom-size" />
  </div>

  <div class="col-12 col-md-6 mb-3 mx-auto flex-grow-1 ms-3">
    <p class="h1 fw-bold">Jon Loh</p>
    <ul class="list-group list-group-flush d-flex flex-column justify-content-center">
      <li class="list-group-item mb-4"><i class="bi bi-telephone-fill"></i>+65 9822 0762</li>
      <li class="list-group-item mb-4"><i class="bi bi-envelope-fill"></i>jon.loh@hotmail.com</li>
      <li class="list-group-item mb-4"><i class="bi bi-linkedin"></i><a href="https://www.linkedin.com/in/jon-loh/">jon-loh</a></li>
      {% include elements/button.html link="#" text="Download My Resume" style="primary" size="lg" %}
    </ul>
  </div>
</div>

<div class="row d-flex flex-column-reverse flex-md-row">
  <div class="col-12 col-md-6 mb-3 mx-auto">
    <p class="h2">About Me</p>
    A passionate Cybersecurity student ready to bring his IT experience and skills to an internship with the industry. A highly motivated, disciplined, and independent individual who collaborates well with a team.
    <br><br>Beyond IT, Jon is an all-rounded individual who sings with the Singapore Symphony Youth Choir, swims competitively with the school team, and busks with his guitar under the National Arts Council (NAC). His peers and teachers acknowledge him to be a dependable, inspiring, and trustworthy leader.
  </div>

  <div class="col-12 col-md-6 mb-3 mx-auto">
    <p class="h2">Highlights</p>
    {% include about/highlights.html %}
  </div>
</div>

<p class="h2 mt-4">Experiences</p>
<div class="row">
{% include about/work_experiences.html %}
</div>

<p class="h2 mt-4">Education</p>
<div class="row">
{% include about/timeline.html %}
</div>

<div class="row">
{% include about/skills.html title="Skills" source=site.data.skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

{% include button.html %}