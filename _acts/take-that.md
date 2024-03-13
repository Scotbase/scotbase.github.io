---
layout: acts
image:  ../assets/images/take that tribute bands and shows.jpg
description: our take that trbute bands are as close as you'll get to the successful band  who've have had 56 number one singles and 39 number one albums, and received eight Brit Awards—winning awards for Best British Group and Best British Live Act. true pros these bands are five star and guaranteed to sell out tickets at your venue. <hr>
          call today for advice, QUOTES & AVAILABILITY
---

<div class="row mt-4 mb-4">
  {% for item in site.data.take-that %}
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
