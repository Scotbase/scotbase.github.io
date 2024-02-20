---
layout: acts
image: assets/images/adele%20tribute%20acts.jpg
description: our adele tribute acts are totally outstanding and capturethe true essence and soul of Adele atkins wonderful songs. these top female vocalists are a big hit wherever they perform. we take pride in being able to offer these tribute acts as completely professional shows including fully programmed lighting, professional backdrops,  and state of the art equipment, making these the perfect Adele Tribute Acts to book for your venue. <hr>
            call today for advice, QUOTES & AVAILABILITY

---

<div class="row mt-4 mb-4">
  {% for item in site.data.adele %}
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
