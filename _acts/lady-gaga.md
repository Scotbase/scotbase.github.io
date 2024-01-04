---
layout: acts
image: https://scotbase.com/images/lady%20gaga%20tribute%20acts-u628439-fr.jpg?crc=4154497688
description: scotbase's fabulous totally gaga and  lady is gaga shows represents the grammy award-winning artist lady gaga with great style. Covering all the hits and mimicking all the moves our lady gaga tribute acts have to be seen to be believed.These shows are  great for parties, corporate functions, weddings and other special events as they provide all the talent required of a true diva such as lady gag <hr>
            call now for advice, INSTANT QUOTES & AVAILABILITY
---

<div class="row mt-4 mb-4">
  {% for item in site.data.lady-gaga %}
    <div class="col-md-4 mb-5">
      <div class="card border-0 shadow h-100">
        <a href="/acts/{{ item.title | slugify }}">
          <img class="card-img-top" src="{{ item.image_src }}" alt="" />
        </a>
      </div>
    </div>
  {% endfor %}
</div>