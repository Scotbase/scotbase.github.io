---
layout: acts
image:  ../assets/images/abba tributes slide.png
# video_src: https://www.youtube.com/embed/kwOaqwIyKas?si=FyAYW6OFKMdkuAjb
description: MAMMA MIA!! OUR OUTSTANDING ABBA TRIBUTES acts ARE A sheer DELIGHT. YOUR DANCE-FLOOR IS GUARANTEED TO BE JUMPING AS THEY PERFORM ALL THE HITS MADE FAMOUS BY THE SWEDISH POP STARS. dance your way into the SevenTIES AND BOOK An abba TRIBUTE FOR A NOSTALGIC EVENING OF THE swedish MUSIC THAT SWEPT THE WORLD. <hr>
            INSTANT QUOTES & AVAILABILITY
---

<div class="row mt-4">
  {% for item in site.data.abba %}
    <div class="col-md-4 mb-5">
      <div class="card border-0 shadow h-100">
        <a href="/acts/{{ item.title | slugify }}">
          <img class="card-img-top" src="{{ item.image_src }}" alt="" />
        </a>
      </div>
    </div>
  {% endfor %}
</div>
