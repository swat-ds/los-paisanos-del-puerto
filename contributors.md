---
layout: article
permalink: /contributors/
title: contributors
---

*Language and Identity in the African Experience*, Spring 2017, Swarthmore College:

   **Dr. Jamie A. Thomas** is Assistant Professor of Linguistics at Swarthmore College. Her forthcoming ethnography *Zombies Speak Swahili* is all about the undead, videogames, and why language matters. She teaches sociolinguistics, linguistic anthropology, and applied linguistics with attention to spoken discourse and visual and textual semiotics.   

Students name their own identities.

{% for contributor in site.data.contributors %}

<div class="contributor">
   
   <div class="author-image">
      <img src="{{ site.url }}/images/{{ contributor.image }}" alt="{{ contributor.name }}">
   </div><!-- ./author-image -->
   
   <div class="author-content">
      <p class="author-name" >{{ contributor.name }}</p>
      <p class="author-bio">{{ contributor.age }}, {{ contributor.self_desc }}</p>
      <p class="author-bio"><span>Hometown:</span> {{ contributor.hometown }}</p>
      <p class="author-bio"><span>Language Background:</span> {{ contributor.language }}</p>
   </div>
   
   <p class="author-bio"><em>{{ contributor.desc }}</em></p>
<hr/>
</div>

{% endfor %}

*Not pictured: Nancy Sorto (student, Swarthmore College), a valuable member of our interviewing team.

Special thanks to Nabil Kashyap and Roberto Vargas of Swarthmore College Libraries and John Word of the Language and Media Center.

![swarthmore libraries logo](../images/logo-mccabe-web.png)
![Language Media Center Logo](../images/LMC2.png)