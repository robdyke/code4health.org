---
permalink: "/featured-stories/"
layout: feature
title:  "Featured Stories"
---

<section class="bg-primary text-white" id="about" style="padding-bottom: 50px">
      <div class="container text-center">
        <h2 class="mb-4">Archived Stories</h2>
       </div>
</section>

<section id="featured-stories" style="padding-top: 50px">
      <div class="container">
        <div class="row">
          <div class="col-lg-10 mx-auto">
		 	<div style="overflow-x:auto;">	
                <table id="project" class="table table-striped table-bordered display responsive no-wrap" style="width:100%">
                    <thead>
                        <tr>
                            <th> </th>
                            <th>Featured Story</th>
                            <th>Category</th>
                            <th>Date</th>
                        </tr>
                    </thead>
                    <tbody>
                    {% for posts in site.posts %}
                        <tr>  
                            <td><a href="{{ posts.url }}"><img src="{{ posts.thumbnail }}" width="100px"></a></td>
                            <td><a href="{{ posts.url }}">{{ posts.title }}</a></td>
                            <td>{{ posts.categories }}</td>
                            <td>{{ posts.date | date: "%-d/%-m/%Y %R" }}</td>            
                        </tr>
                    {% endfor %}
                    </tbody>
                </table>
            </div>
		  </div>
		 </div>
		</div>
    </section>
