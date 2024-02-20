---
layout: acts
image: assets/images/bruno%20mars%20tribute%20acts-u633936-fr.jpg
description: our bruno mars tributes to the Grammy-winning singer/songwriter are astounding. these Highly professional and entertaining  guys sound and look like the real thing. After several years as one of the pop music industry's premier songwriters, bruno Mars finally broke out as a singer in his own right with the 2010 hit Nothin' on You. The track proved an enormous hit, skyrocketing to No. 1 on the Billboard singles chart, and instantly transforming Bruno Mars from a behind-the-scenes composer into a pop performer. if you want your event to pop book a bruno mars tribute today. <hr>
            call now for advice, INSTANT QUOTES & AVAILABILITY
---

<div class="row mt-4 mb-4">
  {% for item in site.data.bruno-mars %}
    <div class="col-md-4 mb-5">
      <div class="card border-0 shadow h-100">
        <a href="/acts/{{ item.title | slugify }}">
          <img class="card-img-top" src="{{ item.image_src }}" alt="" />
        </a>
      </div>
    </div>
  {% endfor %}
</div>