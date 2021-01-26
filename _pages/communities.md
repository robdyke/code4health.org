---
permalink: "/communities/"
layout: page
title:  "Communities"
---

<section class="bg-primary text-white" id="about">
      <div class="container text-center">
        <h2 class="mb-4">Our Communities</h2>
        <p align="left">Innovative digital solutions begin with understanding people's needs and ensuring everyone can participate in their creation. Code4Health hosts a range of communities who bring together anyone with a shared interest across all aspects of digital care. Communities start small and continuously improve using real experiences to inform decisions, building upon it's membership, adding like minded people who understand and can help make informed technology decisions.</p>
		
		<p align="left">Communities can be created around a specific topic, solution or a locality, Code4Health encourages and supports communities to run a range of physical and virtual events and activities. Specialist communities can relate to a particular area of care, a specific project or any other topic where there is a demand from the broader Code4Health community. Local communities can be established at whatever geographical scope their members think is helpful, but will typically be aligned with local health and care communities or city/regions.</p><br>
		<center><a class="btn btn-light btn-xl" href="mailto:info@code4health.org?Subject=%5BSuggest%20New%20Community%5D&Body=%5BName%5D%0A%5BRole%20%26%20Organisation%5D%0A%5BDetails%20of%20the%20community%20and%20its%20aims%5D%0A%5BRelevant%20social%20media%20feeds%5D%0A%5BAny%20relevant%20partners/community%20members%5D%0A%5BLinks%20to%20any%20code%20repositories%20%28if%20applicable%29%5D%0A">Suggest a Community</a></center>
</div>
</section>

<section id="communities">
      <div class="container">
        <div class="row">
          <div class="col-lg-12">
            <center><h2 class="section-heading">Communities & Projects</h2>
            <hr class="my-4"></center>

  	<div style="overflow-x:auto;">	
         <table id="project" class="table table-striped table-bordered display responsive no-wrap" style="width:100%">
        <thead>
            <tr>
                <th>Name</th>
                <th>Description</th>
                <th>Stage</th>
				<th>Community Website(s)</th>
                <th>Case Study</th>
                <th>Social</th>
                <th><i class="fab fa-github"></i> Git Location</th>
                <th>Key Words</th>
            </tr>
        </thead>
        <tbody>
        {% for communities in site.communities %}
            <tr>
                <td style="text-align:center; vertical-align:middle">{{ communities.name }}</td>
                <td><p>{{ communities.description }}</p></td>
                <td style="text-align:center; vertical-align:middle">{{ communities.stage }}</td>      
                <td style="text-align:center; vertical-align:middle">
                {% if communities.www == null %}
                {% else %}
                {% if communities.www contains 'http' %}  
                <a href="{{ communities.www }}" target="_blank"><i class="fas fa-globe fa-2x"></i></a>
                {% else %} 
                <a href="{{ communities.www }}"><i class="fas fa-globe fa-2x"></i></a>
                {% endif %}
                {% endif %}
                </td>
                <td style="text-align:center; vertical-align:middle">
                {% if communities.casestudy == null %}
                {% else %}
                {% if communities.casestudy contains 'http' %}  
                <a href="{{ communities.casestudy }}" target="_blank"><i class="fas fa-file-alt fa-2x"></i></a>
                {% else %} 
                <a href="{{ communities.casestudy }}"><i class="fas fa-file-alt fa-2x"></i></a>
                {% endif %}
                {% endif %}
                </td>
                <td style="text-align:center; vertical-align:middle">
                {% if communities.forum == null %}
                {% else %}
                {% endif %}
                {% if communities.email == null %}
                {% else %}
                <a href="mailto:{{ communities.email }}"><i class="fas fa-envelope fa-2x"></i></a>
                {% endif %}
                {% if communities.twitter == null %}
                {% else %}
                <a href="http://twitter.com/{{ communities.twitter }}" target="_blank"><i class="fab fa-twitter fa-2x"></i></a>
                {% endif %}
                {% if communities.facebook == null %}
                {% else %}
                <a href="{{ communities.facebook }}" target="_blank"><i class="fab fa-facebook fa-2x"></i></a>
                {% endif %}
                {% if communities.youtube ==null %}
                {% else %}
                <a href="{{ communities.youtube }}" target="_blank"><i class="fab fa-youtube fa-2x"></i></a>
                {% endif %}
                </td>
                {% if communities.git == null %}
                <td></td>
                {% else %}
                <td style="text-align:center; vertical-align:middle"><a href="{{ communities.git }}" target="_blank"><i class="fab fa-github fa-2x"></i></a></td>
                {% endif %}
                <td>{{ communities.keywords }}</td>
            </tr>
        {% endfor %}
    </tbody>
</table>
</div>

        
      </div>
	  </div>
	  </div>
    </section>
