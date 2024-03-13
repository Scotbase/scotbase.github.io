---
layout: acts
image:  ../assets/images/steps tribute bands.jpg
description: our British dance-pop group steps tribute bands are second to none. fabulous shows with amazing dance routines and harmonised vocals they know how to please audiences of all ages, and are suitable to play in venues both large and small. they come  with professional sound systems, light shows and backdrops.
---

<div class="row mt-4 mb-4">
  {% for item in site.data.steps %}
    <div class="col-md-4 mb-5 mt-5">
      <div class="card border-0 shadow h-100">
        <a href="/acts/{{ item.title | slugify }}">
          <img class="card-img-top" src="{{ item.image_src }}" alt="" />
        </a>
         <div class="card-body">
          <p class="card-text">{{ item.description }}</p>
        </div>
      </div>
    </div>
  {% endfor %}
</div>
