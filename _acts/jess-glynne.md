---
layout: acts
image: assets/images/jess%20glynne%20tribute%20acts.jpg
description: our jess glynne tribute acts  are delivered by two of scotbase's most talented songstresses, donna ramsdale and meliissa t. the Grammy award-winning artist jess glynne is  represented in style by these two fabulous artists. Covering all the hits and mimicking all the moves our jess glynne tribute acts have to be seen to be believed.   These shows are  great for parties, corporate functions, weddings and other special events as they provide all the talent required of a true superstar such as Miss glynne.<hr>
            INSTANT QUOTES & AVAILABILITY
---
<div class="row mt-4">
  {% for item in site.data.jess-glynne %}
    <div class="col-md-4 mb-5">
      <div class="card border-0 shadow h-100">
        <a href="/acts/{{ item.title | slugify }}">
          <img class="card-img-top" src="{{ item.image_src }}" alt="" />
        </a>
      </div>
    </div>
  {% endfor %}
</div>