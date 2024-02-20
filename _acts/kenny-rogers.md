---
layout: acts
image: assets/images/kenny%20rogers%20tribute%20acts.jpg
description: our kenny rogers tribute acts pay homage to the Award-winning singer/songwriter. Kenny Rogers has enjoyed enormous success on both the country and pop charts with hits like Lucille, The Gambler, Islands in the Stream, Lady and  Morning Desire.kenny rogers has been wowing fans for over sixty years and these tribute acts pay homage to his great legacy. country fans will love these shows as they cover all of  kenny’s hits.the look and sound of mr rogers being recreated is remarkable. these long standing professional acts will bring the house down. if your  looking for success with your event look no further these are sure fire hit shows.our kenny rogers tribute shows have all the warmth and fun of the real thing. to avoid disappointment get your date secured. <hr>
            call now for advice, INSTANT QUOTES & AVAILABILITY
---

<div class="row mt-4 mb-4">
  {% for item in site.data.kenny-rogers %}
    <div class="col-md-4 mb-5">
      <div class="card border-0 shadow h-100">
        <a href="/acts/{{ item.title | slugify }}">
          <img class="card-img-top" src="{{ item.image_src }}" alt="" />
        </a>
      </div>
    </div>
  {% endfor %}
</div>