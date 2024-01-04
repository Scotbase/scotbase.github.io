---
layout: acts
image: https://scotbase.com/images/britney%20spears%20tribute%20acts.jpg?crc=330205404
description: scotbase britney spears tributes are energetic ladies with fabulous vocals, choreographed dance routines and stunning costumes.American Top Pop Princess Britney Spears is well represented at scotbase. choose from our talented britney tributes and your event will sizzle. <hr>
            call today for advice, QUOTES & AVAILABILITY
---

<div class="row mt-4 mb-4">
  {% for item in site.data.britney-spears %}
    <div class="col-md-4 mb-5">
      <div class="card border-0 shadow h-100">
        <a href="/acts/{{ item.title | slugify }}">
          <img class="card-img-top" src="{{ item.image_src }}" alt="" />
        </a>
         <!-- <div class="card-body">
          <p class="card-text">{{ item.description }}</p>
        </div> -->
      </div>
    </div>
  {% endfor %}
</div>