---
title: Editorial Staff
id: staff
---

<section id="editors">
{% for editor in site.data.staff.editors %}
  {% assign plural = editor[1].who | size %}
  <h3>{{ editor[1].title }}{% if plural > 1 %}s{% endif %}</h3>
  <ul>
  {% for p in editor[1].who %}
    <li>
      <b class="name">{{ p.name }}</b>
      <i class="affiliation">{{ p.affiliation }}</i>
      {% if p.email %}
        <a class="email" href="mailto:{{ p.email }}">{{ p.email }}</a>
      {% endif %}
    </li>
  {% endfor %}
  </ul>
{% endfor %}
</section>

<section id="associates">
{% for editor in site.data.staff.associates %}
  <h3>{{ editor[1].title }}s</h3>
  <ul>
  {% for p in editor[1].who %}
    <li>
      <b class="name">{{ p.name }}</b>
      <i class="affiliation">{{ p.affiliation }}</i>
      {% if p.email %}
        <a class="email" href="mailto:{{ p.email }}">{{ p.email }}</a>
      {% endif %}
    </li>
  {% endfor %}
  </ul>
{% endfor %}
</section>

<section id="assistants">
{% for editor in site.data.staff.assistants %}
  <h3>{{ editor[1].title }}s</h3>
  <ul>
  {% for p in editor[1].who %}
    <li>
      <b class="name">{{ p.name }}</b>
      <i class="affiliation">{{ p.affiliation }}</i>
      {% if p.email %}
        <a class="email" href="mailto:{{ p.email }}">{{ p.email }}</a>
      {% endif %}
    </li>
  {% endfor %}
  </ul>
{% endfor %}
</section>
<section id="founder">
{% for editor in site.data.staff.founding %}
  <h3>{{ editor[1].title }}</h3>
  <ul>
  {% for p in editor[1].who %}
    <li>
      <b class="name">{{ p.name }}</b>
    </li>
  {% endfor %}
  </ul>
{% endfor %}
</section>
