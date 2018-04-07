---
title: Editorial Board and Review Process
id: board-and-review
---

<section id="review-process" markdown="1">
### The *Kairos* Editorial Review Process

The most unique feature of *Kairos*—our editorial review process—includes three distinct tiers, or
stages of review.

* #### Tier One
  When the editors receive a [submission](/submissions/), they evaluate it, deciding if it is indeed
  appropriate for *Kairos* and if it is of sufficient quality and scholarly merit to enter our
  formal editorial review process. If it is, then they promote the submission to Tier Two.

* #### Tier Two
  The entire editorial board discusses the submission for two-to-three weeks, coming to a
  collaborative assessment of its quality and potential to be published in *Kairos*. The editors use
  this discussion to compile a review letter along with an overview pointing out specific areas of
  critique to focus on and send this information to the authors (typically within three months of
  submission).

  NOTE: If a text is accepted (or accepted with revisions), the webtext proceeds (upon successful
  completion of revisions) to publication. If the text is not accepted, authors who are asked to
  revise and resubmit are given the opportunity to continue with a Tier Three review/mentorship.

* #### Tier Three
  The editors assign a staff member to work with authors, as needed, to guide/facilitate revisions
  based on the editorial board's comments and evaluation. This mentoring can last up to three
  months. Once Tier Three revisions are complete, the author resubmits the text for a Tier Two
  review and the process starts again. While advancement to a Tier Three review is not a guarantee
  of publication, it does reflect a significant investment in the submission. Our intention is to
  publish the webtext if the author or authors complete the revisions requested in consultation with
  the editors and editorial board.

</section>

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
    <li class="name">{{ member }}</li>
    {% endfor %}
  </ul>
</section>
