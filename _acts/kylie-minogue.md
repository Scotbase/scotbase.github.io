---
layout: acts
image: https://scotbase.com/images/kylie%20minogue%20tribute%20acts-u628029-fr.jpg
description: these kylie minigue tribute artists pay homage to the Grammy award-winning songstress who's popularity has spanned over thirty years. kylie is a style icon and the represention, by two of scotbase's most talented songstresses, Jennie Laine and victoria Jones, have authentically reproduced her wonderful stage costumes.Covering all the hits and mimicking all the moves our jess glynne tribute acts have to be seen to be believed.   These shows are  great for parties, corporate functions, weddings and other special events as they provide all the talent required of a true superstar such as Miss minogue. <hr>
            call now for advice, INSTANT QUOTES & AVAILABILITY
---

<div class="row mt-4 mb-4">
  {% for item in site.data.kylie %}
    <div class="col-md-4 mb-5">
      <div class="card border-0 shadow h-100">
        <a href="/acts/{{ item.title | slugify }}">
          <img class="card-img-top" src="{{ item.image_src }}" alt="" />
        </a>
      </div>
    </div>
  {% endfor %}
</div>