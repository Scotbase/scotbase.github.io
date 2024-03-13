---
layout: acts
image:  ../assets/images/blonde tribute bands.jpg
# video_src: https://www.youtube.com/embed/kwOaqwIyKas?si=FyAYW6OFKMdkuAjb
description: iconic superstar blondie is synonymous with the eighties. scotbase are proud to present our truly fabulous blondie tribute acts.  talented bands who are fronted by amazing vocalists, have  choreographed dance routines and stunning costumes.<hr>
            call today for advice, QUOTES & AVAILABILITY  
---

<div class="row mt-4 mb-4">
  {% for item in site.data.blondie %}
    <div class="col-md-4 mb-5">
      <div class="card border-0 shadow h-100">
        <a href="/acts/{{ item.title | slugify }}">
          <img class="card-img-top" src="{{ item.image_src }}" alt="" />
        </a>
      </div>
    </div>
  {% endfor %}
</div>
<!-- <iframe 
  width="100%" 
  height="500" 
  src="https://www.youtube.com/embed/kwOaqwIyKas?si=FyAYW6OFKMdkuAjb" 
  title="YouTube video player" 
  frameborder="0" 
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
  allowfullscreen>
</iframe> -->
