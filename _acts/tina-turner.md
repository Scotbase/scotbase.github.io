---
layout: acts
image:  ../assets/images/tina turner tribute acts.jpg
description: our tina turner tribute acts emeulate the lady with  the raunchy on-stage persona, the golden wigs, flailing legs and breath-taking mini-skirts tina turner is a giant in the world of pop. Tina broke the world record for the largest paying audience at a solo concert – 184,000 people, at the Maracanã in Rio de Janeiro.our tina turner tribute acts are also suitable for small or large venues. a great night of entertainment is guaranteed with these immensely popular tribute shows. <hr>
            call today for advice, QUOTES & AVAILABILITY
---

<div class="row mt-4 mb-4">
  {% for item in site.data.tina-turner %}
    <div class="col-md-4 mb-5 mt-5">
      <div class="card border-0 shadow h-100">
        <a href="/acts/{{ item.title | slugify }}">
          <img class="card-img-top" src="{{ item.image_src }}" alt="" />
        </a>
      </div>
    </div>
  {% endfor %}
</div>