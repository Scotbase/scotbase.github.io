---
layout: acts
image:  ../assets/images/neil diamond tribute acts.jpg
description: Our neil diamond tributes to the american Singer and songwriter are so like the  living legend himself. best known as a successful pop music singer who scored a number of hits during the 1960s, 70s and 80s., Diamond wrote the hits I'm A Believer(1966) and A Little Bit Me, A Little Bit You for the Monkees, and had his own first No. 1 hit with  Cracklin' Rosie in 1970.Neil Diamond is adored all over the world, his fan base is massive and he is still touring and producing new albums. Our neil diamond tributes offer all the hits from the seventies onwards. <hr>
            call now for advice, INSTANT QUOTES & AVAILABILITY
---

<div class="row mt-4 mb-4">
  {% for item in site.data.neil-diamond %}
    <div class="col-md-4 mb-5 mt-5">
      <div class="card border-0 shadow h-100">
        <a href="/acts/{{ item.title | slugify }}">
          <img class="card-img-top" src="{{ item.image_src }}" alt="" />
        </a>
      </div>
    </div>
  {% endfor %}
</div>