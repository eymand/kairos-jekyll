---
title: Editorial Board and Review Process
id: board-and-review
---

<section id="board-members">
  <h3>Editorial Review Board</h3>
  <ul>
    {% for member in site.data.board.members %}
    <li>
      <b class="name">{{ member.name }}</b>
      <i class="affiliation">{{ member.affiliation }}</i>
    </li>
    {% endfor %}
  </ul>
</section>

<section id="board-alumni">
  <h3>Editorial Board Alumni</h3>
  <ul>
    {% for member in site.data.board.alumni %}
    <li class="name>">{{ member }}</li>
    {% endfor %}
  </ul>
</section>
