---
layout: acts
image: https://scotbase.com/images/shirley%20bassey%20tribute%20acts-u630369-fr.jpg?crc=146843264
description: our shirley bassey tribute acts and shows pay homage to the tiger from tiger bay. Dame Shirley bassey, oBE.  a Welsh vocalist whose career began in the mid-1950s. best known both for her powerful voice and for recording the theme songs to the James Bond films Goldfinger (1964), Diamonds Are Forever (1971), and Moonraker (1979).In January 1959, Bassey became the first Welsh person to gain a number one single, since then she has wowed audiences around the globe and remains a sought after artiste. as are our fabulous Shirley bassey tribute acts.a great night of entertainment is guaranteed with these immensely popular tribute shows. <hr>
            call today for advice, QUOTES & AVAILABILITY
---

<div class="row mt-4 mb-4">
  {% for item in site.data.shirley-bassey %}
    <div class="col-md-4 mb-5">
      <div class="card border-0 shadow h-100">
        <a href="/acts/{{ item.title | slugify }}">
          <img class="card-img-top" src="{{ item.image_src }}" alt="" />
        </a>
      </div>
    </div>
  {% endfor %}
</div>
