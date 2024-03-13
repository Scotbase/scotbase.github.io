---
layout: acts
image:  ../assets/images/westlife tribute bands2.jpg
description: scotbase's westlife tribute bands celebrate THE GREATEST boy band OF ALL TIME. these are the most authentic recreations that you will find. thet have their look,  sound, dance routines, costumes  replicated to perfection. it is a visual and  concert experience THAT WILL appeal to audiences of all ages and to most venues. full shows with special lighting effects - a must for westlife fans. <hr>
            call today for advice, QUOTES & AVAILABILITY
---

<div class="row mt-4 mb-4">
  {% for item in site.data.westlife %}
    <div class="col-md-4 mb-5 mt-5">
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
