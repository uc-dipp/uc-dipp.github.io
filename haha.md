---
layout: haha
title: Hack Harris
---


<div class="posts">
  {% for post in site.categories.haha %}
  <div class="post">
    <h1 class="post-title">
      <a href="{{ post.url }}">
        {{ post.title }}
      </a>
    </h1>

    <span class="post-date">{{ post.date | date_to_string }}</span>

    {{ post.content }}
  </div>
  {% endfor %}
</div>

<div class="pagination">
  {% if paginator.next_page %}
    <a class="pagination-item older" href="/page{{paginator.next_page}}">Older</a>
  {% else %}
    <span class="pagination-item older">Older</span>
  {% endif %}
  {% if paginator.previous_page %}
    {% if paginator.page == 2 %}
      <a class="pagination-item newer" href="/">Newer</a>
    {% else %}
      <a class="pagination-item newer" href="/page{{paginator.previous_page}}">Newer</a>
    {% endif %}
  {% else %}
    <span class="pagination-item newer">Newer</span>
  {% endif %}
</div>





Hack Harris is here to help you wrangle your worst procrastination habits and *slay* your most nagging data fears. Welcome to a new kind of summer productivity: **Hack Harris in the Summer.**

**What:** Weekly data hack night for the policy-oriented*  
**Your hosts:** Hack Harris and Data in Public Policy  
  
**Where:** Argo Tea at 16 W. Randolph St. (at State)  
**When:** Every Wednesday, 6pm (beginning June 25)  
  
**Who:** Harris students, alums, and friends  
**To bring:** Laptop, enthusiasm  

It’s easy to talk about wanting to learn. It’s harder to put your butt in a chair and do it. Hack Harris in the Summer is a public commitment to be productive for a couple of hours a week. We’ll teach you what we know, and we’ll help you find resources for the rest of it. 

If you’ve ever wanted to learn some data skills (or if you ever want a job), this is your chance to commit to learning them, in a community of *like-minded* and supportive fellow travelers. Bring your questions and your doubts. Bring some skills of your own you’d like to teach, or projects you need help on. 

You don't have to commit to coming every week (though we'd love it if you did). Just show up when it's convenient for you.

<small>\* For those who don't love jargon, a hack night is a loose term for a time when people get together to work on things, together. It can be as collaborative as you'd like it to be. You don't need to have skills in anything data oriented, but you should want to acquire some skills (e.g. learn [R](/resources/#r) or [Python](/resources/#python) or Stata). We'll help you do the learning.</small>
