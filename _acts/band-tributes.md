---
layout: acts
image: https://scotbase.com/images/book%20a%20tribute%20band.jpg?crc=4267022110
# video_src: https://www.youtube.com/embed/kwOaqwIyKas?si=FyAYW6OFKMdkuAjb
description: HIRE the uk's best tribute bands and get the ideal act for your event.
            five star ACTS to suit all events and venues, large or small. <hr>
            call now for INSTANT QUOTES & AVAILABILITY
---

<div class="row mt-4">
  {% for item in site.data.bands %}
    <div class="col-md-4 mb-5">
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
