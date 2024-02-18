---
layout: acts
image: https://scotbase.com/images/barry%20white%20tribute%20acts-u633335-fr.jpg
description: our barry white tribute artist recreate the Grammy Award–winning singers'  smooth, deep voice, as they entertain with sexy soul hits like Can't Get Enough of Your Love, Babe. barry white's distinctive deep voice and romantic lyrics made him an icon of sexy soul that is still in demand today.sexy soul is what our fabulous barry white  tribute acts ooze. a great night of entertainment is guaranteed with these immensely popular tribute shows. <hr>
            call now for advice, INSTANT QUOTES & AVAILABILITY
---

<div class="row mt-4">
  {% for item in site.data.barry-white %}
    <div class="col-md-4 mb-5">
      <div class="card border-0 shadow h-100">
        <a href="/acts/{{ item.title | slugify }}">
          <img class="card-img-top" src="{{ item.image_src }}" alt="" />
        </a>
      </div>
    </div>
  {% endfor %}
</div>
