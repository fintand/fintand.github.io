---
layout: default
title: Projects
permalink: /projects/
---


<div class="container">
  <div class="row">
    <h2><i class="fa fa-code" aria-hidden="true"></i> {{ page.title }}</h2>
  </div>


  <ul>
      {% for post in site.posts %}
        <li>
          <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>

          <h2>
            <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
          </h2>
        </li>
      {% endfor %}
    </ul>

  <p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>

</div>