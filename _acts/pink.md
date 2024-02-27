---
layout: acts
image:  ../assets/images/pink tribute acts.jpg
description: scotbase pink tributes all have the wow factor. fabulous vocals, choreographed dance routines, stunning costumes and amazing musicians these shows are not to be missed. With Pink’s career stretching back as far as 2000, her debut single (the R&B inspired ‘There You Go’) kicked off a back catalog that has so far given us over 30 hits .Her widespread appeal continues to grow today, with hit singles still being released off the late 2012 album ‘The Truth About Love’. This massive range of material has been perfect for creating shows that appeal to a wide variety of audiences. <hr>
            call now for advice, INSTANT QUOTES & AVAILABILITY
---

<div class="row mt-4 mb-4">
  {% for item in site.data.pink %}
    <div class="col-md-4 mb-5">
      <div class="card border-0 shadow h-100">
        <a href="/acts/{{ item.title | slugify }}">
          <img class="card-img-top" src="{{ item.image_src }}" alt="" />
        </a>
      </div>
    </div>
  {% endfor %}
</div>