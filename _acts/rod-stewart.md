---
layout: acts
image: https://scotbase.com/images/ros%20stewart%20tribute%20acts-u640316-fr.jpg
description: our rod stewart tribute shows have great knowledge & enthusiasm for rod stewart. this is obvious from their portrayals of the rocker.A Rod Stewart concert is more than just the music, it's a combination of all the costumes, the stories and the moves which go to define Rod's character.the shows come with pro lighting, sound systems and backdrops <hr>
            call now for advice, INSTANT QUOTES & AVAILABILITY
---

<div class="row mt-4 mb-4">
  {% for item in site.data.rod-stewart %}
    <div class="col-md-4 mb-5">
      <div class="card border-0 shadow h-100">
        <a href="/acts/{{ item.title | slugify }}">
          <img class="card-img-top" src="{{ item.image_src }}" alt="" />
        </a>
      </div>
    </div>
  {% endfor %}
</div>