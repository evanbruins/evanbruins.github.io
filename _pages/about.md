---
layout: about
title: about
permalink: /
subtitle: Mechanical Engineer Driven by Innovation and a Passion for the Outdoors
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

Hi, I’m Evan Bruins! I am a senior Mechanical Engineering student at George Fox University, focused on creating optimized designs and connecting technology with the natural world. Outside of engineering, I spend my time backpacking, snowboarding, surfing, running, and making music with friends.

  

<div style="margin-top:1rem"></div>
## Featured Projects          

<div class="featured-projects row row-cols-1 row-cols-md-3 g-4">
{% assign sorted_projects = site.projects | sort: "importance" | reverse %}
{% for project in sorted_projects limit:3 %}
  <div class="col d-flex">
    {% include projects.liquid %}
  </div>
{% endfor %}
</div>
