---
layout: acts
image: assets/images/david%20bowie%20tribute%20acts.jpg
description: We are proud to present the most authentic bowie tribute acts to one of the most iconic british pop stars. these david bowie tribute acts are keeping his legacy alive.David Bowie was an English rock star known for dramatic musical transformations, including his character Ziggy Stardust. He was inducted into the Rock and Roll Hall of Fame in 1996.His first hit was the song Space Oddity in 1969. The original pop chameleon, Bowie became a fantastical sci-fi character for his breakout Ziggy Stardust album. He later co-wrote Fame, with Carlos Alomar and John Lennon, which became his first American Number one single in 1975. An accomplished actor, Bowie starred in The Man Who Fell to Earth in 1976.these are five star tribute shows who leave their audiences wanting more.  book early to avoid disappointment. <hr>
            call now for advice, INSTANT QUOTES & AVAILABILITY
---

<div class="row mt-4 mb-4">
  {% for item in site.data.david-bowie %}
    <div class="col-md-4 mb-5">
      <div class="card border-0 shadow h-100">
        <a href="/acts/{{ item.title | slugify }}">
          <img class="card-img-top" src="{{ item.image_src }}" alt="" />
        </a>
      </div>
    </div>
  {% endfor %}
</div>