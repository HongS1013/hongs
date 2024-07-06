---
title: "Home"
layout: homelay
sitemap: false
permalink: /
---

<!-- ### Welcome! -->

<!-- Theoretical physics is a branch of physics that focuses on the development of mathematical models and theories to understand and explain natural phenomena.
It plays a crucial role in our understanding of the fundamental laws of the universe and the fundamental particles that make up all matter.
Research in theoretical physics helps us to make predictions about how the universe works and to test these predictions through experiments.
It also helps us to understand the fundamental principles that govern the behavior of matter and energy, and to explore the limits of our current knowledge.
Theoretical physics helps us to make progress in a wide range of fields, including cosmology, particle physics, and quantum mechanics, and it has led to many important discoveries and technological innovations. -->

<!-- <div class="container">
<div class="row">
<center>
<img src="{{ site.url }}{{ site.baseurl }}/images/banner.jpg" width="100%"/><br/>
<!-- Examples of Feynman diagrams. <br/>
Feynman R., The theory of positrons. <i>Phys. Rev.</i> (1949) -->
<!-- </center>
</div>
</div>
<br/> --> 
<br/>

I am a newly graduatePh.D in [Learning Technologies program](https://lt.umn.edu) of Instruction and Curriculum Department, University of Minnesota Twin Cities. I have worked as a research fellow in [Penn GSE Wonder Lab](https://penn-wonderlab.github.io/) directed by Dr.Bodong Chen. <br />
<br />
My research interests lie in the intersection between learning design, learning analytics and learning sciences, inquiring how to leverage the learning analytics to support teachers in their design and teaching practice. Grounded in research-practice partnership and heralding human-centered design principles, my current research focuses on the design and development of applications to facilitate collaborative learning activities for both students and instructors. [Rread more]({{site.url}}{{site.baseurl}}/About)


<div>
  <h4>Recent Activities</h4>

  {% for article in site.data.news limit:3 %}
  <b>{{ article.date }}</b>: 
    {{ article.headline }}
  {% endfor %}

</div>