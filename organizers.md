---
layout: default
title: Organizers
---

<div class="home">
	<h1>Organizers</h1>
             <ul class="noList">
                 {% for organizer in site.organizers %}
                 <li>
                     <a href="{{ organizer.url }}"><b>{{ organizer.name }}</b></a>, {{ organizer.position }}, {{ organizer.affiliation }}
                 </li> 
                 {% endfor %}
             </ul>
</div>
