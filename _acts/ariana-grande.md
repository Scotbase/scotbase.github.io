---
layout: acts
image: https://scotbase.com/images/ariana%20tribute%20shows.jpg?crc=209923926
---

<div class="row mt-4 mb-4">
  {% for item in site.data.ariana-grande %}
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
