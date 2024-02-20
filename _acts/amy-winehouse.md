---
layout: acts
image: assets/images/amy%20winehouse%20tribute%20vocalists.jpg
description: our Amy winehouse tribute vocalists have powerful vocals and stunning costumes ensuring these acts are a big  hit wherever they perform. Amy winehouse had one of the most distinctive voices and style in the music industry. her sound is brought to life by the fabulous tributes artists here at scotbase.we take pride in being able to offer these as acts as completely professional shows including fully programmed lighting, professional backdrops,  and state of the art equipment, making these the perfect amy winehouse Tribute Acts to book for your venue. <hr>
            call today for advice, QUOTES & AVAILABILITY
---

<div class="row mt-4 mb-4">
  {% for item in site.data.amy-winehouse %}
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
