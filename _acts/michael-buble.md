---
layout: acts
image:  ../assets/images/michael buble tribute acts.jpg
description: our Michael Bublé tribute acts and shows pay homage to the Grammy-winning singer from Canada whose style is inspired by the likes of greats Tony Bennett and Frank Sinatra. Having learned all of his grandfather's favourite tunes, Bublé entered the British Columbia Youth Talent Search competition and won.In 2003, Bublé's first major album was released. The self-titled record was a worldwide success, going multiplatinum in many countries, and reaching the Top 10 in the UK.The debut album incorporated Bublé's multifaceted talents, especially his aptitude for lending a pop style to old classics such as Fever, Moondance and How Can You Mend a Broken Heart?our michael Bublé tribute shows have all the glamour of swing and the punch of pop. suitable for all occasions, including weddings, corporate events, clubs and hotels your guaranteed a fabulous time. <hr>
            call now for advice, INSTANT QUOTES & AVAILABILITY
---

<div class="row mt-4 mb-4">
  {% for item in site.data.michael-buble %}
    <div class="col-md-4 mb-5">
      <div class="card border-0 shadow h-100">
        <a href="/acts/{{ item.title | slugify }}">
          <img class="card-img-top" src="{{ item.image_src }}" alt="" />
        </a>
      </div>
    </div>
  {% endfor %}
</div>