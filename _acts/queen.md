---
layout: acts
image:  ../assets/images/queen tribute bands.jpg
video_src: https://player.vimeo.com/video/310767379?h=4ca6be024d
description: queen are of the worlds most famous and successful bands to come out of the uk and  freddie mercury lives on in these fantastic queen tribute acts. scotbase queen Tribute Acts emulate the English rock band who gave the anthems "We Will Rock You" and "We Are the Champions" to the world.one of the world's best-selling music bands, Queen received the Outstanding Contribution to British Music Award, were inducted into the Rock and Roll Hall of Fame, received the Ivor Novello Award for Outstanding Song Collection, and in 2018 they were presented the Grammy Lifetime Achievement Award. <hr>
            call now for advice, INSTANT QUOTES & AVAILABILITY

---

<div class="row mt-4 mb-4">
  {% for item in site.data.queen %}
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
