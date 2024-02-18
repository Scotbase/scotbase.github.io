---
layout: acts
image: https://scotbase.com/images/ariana%20tribute%20shows.jpg
description: our Ariana grande tribute shows boast powerful vocalists, stunning costumes and choreographed dance routines  ensure your audience will have a great night out. these acts are a big  hit wherever they perform and are rebooked time and time again. Ariana grande has a distinctive voice and style much loved by audiences of all ages.  her sound is brought to life by the fabulous tributes artists here at scotbase. we take pride in being able to offer these as acts as completely professional shows including fully programmed lighting, professional backdrops,  and state of the art equipment, making these the perfect ariana grande Tribute Acts to book for your venue. <hr>
            call today for advice, QUOTES & AVAILABILITY. lines open until 10pm
---

<div class="row mt-4 mb-4">
  {% for item in site.data.ariana-grande %}
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
