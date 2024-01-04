---
layout: acts
image: https://scotbase.com/images/beyonce%20tribute%20vocalists%20-%20shows.png?crc=3780278797
# video_src: https://www.youtube.com/embed/kwOaqwIyKas?si=FyAYW6OFKMdkuAjb
description: our beyonce tribute vocalists and shows pay homage to the artist who, with the release of her debut album, Dangerously in Love (2003) saw destiny's child lead singer beyonce established as a solo artist worldwide, debuting at number one on the US Billboard 200 chart and earning five Grammy Awards, and featured the Billboard Hot 100 number one singles "Crazy in Love" and "Baby Boy".scotbase tributes to beyonce are energetic shows with fabulous vocalists, choreographed dance routines and stunning costumes.<hr>
            call today for advice, QUOTES & AVAILABILITY  
---

<div class="row mt-4 mb-4">
  {% for item in site.data.beyonce %}
    <div class="col-md-4 mb-5">
      <div class="card border-0 shadow h-100">
        <a href="/acts/{{ item.title | slugify }}">
          <img class="card-img-top" src="{{ item.image_src }}" alt="" />
        </a>
      </div>
    </div>
  {% endfor %}
</div>