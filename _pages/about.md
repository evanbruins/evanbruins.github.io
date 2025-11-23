---
layout: about
title: about
permalink: /
subtitle: <a href='#'>Affiliations</a>. Address. Contacts. Motto. Etc.
overflow: hidden;

profile:
  align: right
  image: Evanb.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Location: Portland OR</p>
    <p>Phone: +1(503) 268-9254</p>
    <p>Email: ecbruins@gmail.com</p>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page


announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_projects:
  enabled: false
  scrollable: true 
  limit: 3
---

<style>
/* Remove extra bottom whitespace on the about page only */
body { padding-bottom: 0 !important; }
</style>

Wite your biography here. Tell the world about yourself. Link to your favorite [subreddit](http://reddit.com). You can put a picture in, too. The code is already in, just name your picture `prof_pic.jpg` and put it in the `img/` folder. 

  

<div style="margin-top:3rem"></div>
## Featured Projects

<div class="featured-projects row row-cols-1 row-cols-md-3 g-4">
{% assign sorted_projects = site.projects | sort: "importance" | reverse %}
{% for project in sorted_projects limit:3 %}
  <div class="col d-flex">
    {% include projects.liquid %}
  </div>
{% endfor %}
</div>
