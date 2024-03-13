---
layout: acts
image:  ../assets/images/girls aloud tribute shows.jpg
# video_src: https://www.youtube.com/embed/kwOaqwIyKas?si=FyAYW6OFKMdkuAjb
description: girls aloud tribute shows are a huge hit for all types of events. Re-live the music of girls aloud as it is brought to life from scotbase entertainments girls aloud tribute  acts. with exceptional live vocals and harmonies so close to the real thing - hearing is believing.all these bands boast fabulous costumes,  have amazing dance routines, and come with brilliant sound systems, professional light shows and backdrops. <hr>
            INSTANT QUOTES & AVAILABILITY
---

<div class="row mt-4">
  {% for item in site.data.girls-aloud %}
    <div class="col-md-4 mb-5 mt-5">
      <div class="card border-0 shadow h-100">
        <a href="/acts/{{ item.title | slugify }}">
          <img class="card-img-top" src="{{ item.image_src }}" alt="" />
        </a>
      </div>
    </div>
  {% endfor %}
</div>