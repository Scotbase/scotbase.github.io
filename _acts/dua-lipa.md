---
layout: acts
image:  ../assets/images/dua lipa tribute acts.jpg
description: our dua lipa tribute acts are first class  entertainers. 2017 was such a breakthrough year for the bewitching London born singer  as she sold over a million copies of her self-titled debut album. and scotbase, always on the ball, offer two amazing tributes to the star.  <hr>
            call now for INSTANT QUOTES & AVAILABILITY
---

<div class="row mt-4">
  {% for item in site.data.dua-lipa %}
    <div class="col-md-4 mb-5 mt-5">
      <div class="card border-0 shadow h-100">
        <a href="/acts/{{ item.title | slugify }}">
          <img class="card-img-top" src="{{ item.image_src }}" alt="" />
        </a>
      </div>
    </div>
  {% endfor %}
</div>