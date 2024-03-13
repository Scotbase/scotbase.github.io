---
layout: acts
image:  ../assets/images/shania twain tribute acts.jpg
description: our shania twain tribute acts are in big demand. these shows provide Fantastic music to dance and sing along to. these great vocalist  have shania down to a t you'll scarcely believe they aren't the real thing. our shania twain tributes appeal to mixed age audiences and suited to venues large and small.The perfect choice for corporate events, hotels, social clubs and diva Themed Occasions.  book an superb shania twain tribute act and your event will ooze glamour.  scotbase are proud to  present these first class shania twain tribute acts and shows to the uk. <hr>
            call today for advice, QUOTES & AVAILABILITY
---

<div class="row mt-4 mb-4">
  {% for item in site.data.shania-twain %}
    <div class="col-md-4 mb-5 mt-5">
      <div class="card border-0 shadow h-100">
        <a href="/acts/{{ item.title | slugify }}">
          <img class="card-img-top" src="{{ item.image_src }}" alt="" />
        </a>
      </div>
    </div>
  {% endfor %}
</div>
