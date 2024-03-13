---
layout: acts
image:  ../assets/images/celine dion tribute acts.jpg
description: our celine dion tribute acts celebrate the Canadian Singer who  is recognised as one of the greatest voices of our time.scotbase celine dion tributes to one of the most famous singers in the world are simply wow. fabulous vocals, choreographed dance routines, stunning costumes and amazing musicians make these shows a must see. <hr>
            call today for advice, QUOTES & AVAILABILITY.
---

<div class="row mt-4 mb-4">
  {% for item in site.data.celine-dion %}
    <div class="col-md-4 mb-5 mt-5">
      <div class="card border-0 shadow h-100">
        <a href="/acts/{{ item.title | slugify }}">
          <img class="card-img-top" src="{{ item.image_src }}" alt="" />
        </a>
      </div>
    </div>
  {% endfor %}
</div>
