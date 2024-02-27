---
layout: acts
image:  ../assets/images/taylor swift tribute acts.jpg
description: our taylor swift tribute acts are in big demand and our four songstresses who put on terrific shows of this small powerhouse deliver every time. In September 2009 taylor swift became the first country music artist to win an MTV Video Music Award when "You Belong with Me" was named Best Female Video.She is also the recipient of ten Grammy Awards, five Guinness World Records, one Emmy Award, 23 Billboard Music Awards, 11 Country Music Association Awards, eight Academy of Country Music Awards, and one Brit Award. Swift is one of the best-selling artists of all time, having sold more than 40 million albums.our taylor swift tribute acts are also suitable for small or large venues. a great night of entertainment is guaranteed with these immensely popular tribute shows. <hr>
            call today for advice, QUOTES & AVAILABILITY
---

<div class="row mt-4 mb-4">
  {% for item in site.data.taylor-swift %}
    <div class="col-md-4 mb-5">
      <div class="card border-0 shadow h-100">
        <a href="/acts/{{ item.title | slugify }}">
          <img class="card-img-top" src="{{ item.image_src }}" alt="" />
        </a>
      </div>
    </div>
  {% endfor %}
</div>