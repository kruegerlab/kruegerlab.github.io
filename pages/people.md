---
layout              : page
show_meta           : false
title               : "Group Members"
permalink           : "/people/"
header: no
---
(In progress)
<br>
{% for member in site.data.people %}
  <div class="row">
    <div class="small-6 medium-6 large-6 columns b30">
      <img src="{{ site.baseurl }}/images/people/{{ member.slug }}.jpg" alt="{{ member.name }}'s profile picture" class="profile-picture">
    </div>
    <div class="small-6 medium-6 large-6 columns b30 author-info">
      {% if member.website %}
        <h3><a href="{{ member.website }}" target="_blank" rel="noopener noreferrer">{{ member.name }}</a></h3>
      {% else %}
        <h3>{{ member.name }}</h3>
      {% endif %}
      <p>{{ member.title }}</p>
      <p>{{ member.bio }}</p>
    </div>
  </div>
{% endfor %}