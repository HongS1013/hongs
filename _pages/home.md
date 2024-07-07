---
title: "Home"
layout: homelay
sitemap: false
permalink: /
---

<br />
I am a newly graduate PhD in [Learning Technologies program](https://lt.umn.edu) of Instruction and Curriculum Department, University of Minnesota Twin Cities. I have worked as a research fellow in [Penn GSE Wonder Lab](https://penn-wonderlab.github.io/) directed by Dr.Bodong Chen. <br />
<br />
My research interests lie in the intersection between learning design, learning analytics and learning sciences, inquiring how to leverage the learning analytics to support teachers in their design and teaching practice. Grounded in research-practice partnership and heralding human-centered design principles, my current research focuses on the design and development of applications to facilitate collaborative learning activities for both students and instructors. [Read more]({{site.url}}{{site.baseurl}}/About)


<div>
  <h4>Recent Activities</h4>

  {% for article in site.data.news limit:3 %}
  <b>{{ article.date }}</b>: 
    {{ article.headline }}
  {% endfor %}

</div>