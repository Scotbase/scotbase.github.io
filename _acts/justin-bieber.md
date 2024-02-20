---
layout: acts
image: assets/images/justin%20bieber%20tribute%20acts.jpg
description: our justin bieber tribute pay homage to  the Grammy Award-winning Canadian pop star. Justin Bieber  was discovered via YouTube. His latest hits include Let Me Love You, Despacito (Remix) and I'm the One. Bieber went from an unknown, untrained singer to a budding superstar with a big-time record deal with Usher within two years.Bieber went on to become the first solo artist to have four singles enter the Top 40 before the release of a debut album. His 2017 collaboration with Luis Fonsi, Despacito, broke the all-time record for most consecutive weeks at the number one spot on the Top 100.our justin bieber tribute shows have all the energy and bounce of the real thing. <hr>
            call now for advice, INSTANT QUOTES & AVAILABILITY
---

<div class="row mt-4">
  {% for item in site.data.justin-bieber %}
    <div class="col-md-4 mb-5">
      <div class="card border-0 shadow h-100">
        <a href="/acts/{{ item.title | slugify }}">
          <img class="card-img-top" src="{{ item.image_src }}" alt="" />
        </a>
      </div>
    </div>
  {% endfor %}
</div>