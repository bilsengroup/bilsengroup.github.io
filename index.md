---
layout: page
title: BILSEN
subtitle: Bilkent University Software Engineering and Data Analytics Research Group
use-site-title: true
---
<!--  -->
<div style="text-align: justify">
<!-- <img src="./img/group_foto.jpg" alt="BILSEN Members - May 22, 2019 " width="750" > -->
<img src="./IMG_2823.jpg" alt="BILSEN Members - Oct 2, 2019 " width="750" >	
</div>


<div style="text-align: justify">
<p><b>BILSEN (Bilkent University Software Engineering and Data Analytics Research Group)</b> of <a href="http://w3.cs.bilkent.edu.tr/en/">Computer Engineering Department</a> at <a href="http://w3.bilkent.edu.tr/bilkent/">Bilkent University</a> has been performing research studies on software engineering domain over the last decade.</p>

<p>The main goal of the group is to foster research and education on software engineering and support ongoing activities in these directions.</p>

<p>The research activities of the group are in different domains of software engineering including Software Analytics, Machine Learning and Big Data Visualization for Software Engineering,
	Gamification, Software Product Line Engineering,  and Empirical Software Engineering.
</p>
</div>
<!-- <p>Some of the collaborated companies & institutions : </p>
<ul>
  <li>Havelsan</li>
  <li>Huawei</li>
</ul> -->



<!-- 
<div class="posts-list">
  {% for post in paginator.posts %}
  <article class="post-preview">
    <a href="{{ post.url | prepend: site.baseurl }}">
	  <h2 class="post-title">{{ post.title }}</h2>

	  {% if post.subtitle %}
	  <h3 class="post-subtitle">
	    {{ post.subtitle }}
	  </h3>
	  {% endif %}
    </a>

    <p class="post-meta">
      {{ post.date | date: "%B %-d, %Y" }}
    </p>

    <div class="post-entry-container">
      {% if post.image %}
      <div class="post-image">
        <a href="{{ post.url | prepend: site.baseurl }}">
          <img src="{{ post.image }}">
        </a>
      </div>
      {% endif %}
      <div class="post-entry">
        {{ post.excerpt | strip_html | xml_escape | truncatewords: site.excerpt_length }}
        {% assign excerpt_word_count = post.excerpt | number_of_words %}
        {% if post.content != post.excerpt or excerpt_word_count > site.excerpt_length %}
          <a href="{{ post.url | prepend: site.baseurl }}" class="post-read-more">[Read&nbsp;More]</a>
        {% endif %}
      </div>
    </div>

    {% if post.tags.size > 0 %}
    <div class="blog-tags">
      Tags:
      {% if site.link-tags %}
      {% for tag in post.tags %}
      <a href="{{ site.baseurl }}/tags#{{- tag -}}">{{- tag -}}</a>
      {% endfor %}
      {% else %}
        {{ post.tags | join: ", " }}
      {% endif %}
    </div>
    {% endif %}

   </article>
  {% endfor %}
</div>

{% if paginator.total_pages > 1 %}
<ul class="pager main-pager">
  {% if paginator.previous_page %}
  <li class="previous">
    <a href="{{ paginator.previous_page_path | prepend: site.baseurl | replace: '//', '/' }}">&larr; Newer Posts</a>
  </li>
  {% endif %}
  {% if paginator.next_page %}
  <li class="next">
    <a href="{{ paginator.next_page_path | prepend: site.baseurl | replace: '//', '/' }}">Older Posts &rarr;</a>
  </li>
  {% endif %}
</ul>
{% endif %}
 -->
