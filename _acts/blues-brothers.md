---
layout: acts
image:  ../assets/images/blues borthers tribute bands slide.jpg
description: our BLUES BROTHERS TRIBUTE ACTS ARE second to none.  IF YOU'Re LOOKING TO LIVEN UP YOUR EVENT A BLUES BROTHERS TRIBUTE ACT IS FOR YOU. THE mad blues, the MAC BLUES AND THE BIRMINGHAM BLUES BROTHERS ARE all TOP CLASS ACTS who AIM TO PLEASE. these acts appeal to audience of all ages and suitable for venues large and small. if you want a full house, a tribute act is the answer. remember we're on a mission from god. <hr>

      call now for advice, INSTANT QUOTES & AVAILABILITY

---

<div class="row mt-4 mb-4">
  {% for item in site.data.blues-brothers %}
    <div class="col-md-4 mb-5">
      <div class="card border-0 shadow h-100">
        <a href="/acts/{{ item.title | slugify }}">
          <img class="card-img-top" src="{{ item.image_src }}" alt="" />
        </a>
         <!-- <div class="card-body">
          <p class="card-text">{{ item.description }}</p>
        </div> -->
      </div>
    </div>
  {% endfor %}
</div>
