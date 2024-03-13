---
layout: acts
image:  ../assets/images/bon jovi tribute bands.png
description: These fantastic Bon Jovi Tribute Acts will make you think you are at Bon Jovi concert. Formed in the early eighties, this America Hard Rock band ‘Bon Jovi’ went from strength to strength with big hits like ‘Living On A Prayer’’’, It’s My Life, ‘You Give Love A Bad Name’, and with the big hair to match. With front man jon Bon Jovi’s vocal talent they continued to dominate the eighties hard Rock music world, and today these truly authentic tribute bands play a collection of the biggest rock hits from the earlier days right up to the modern day, with magical songs to match all age groups. <hr>
            call now for advice, INSTANT QUOTES & AVAILABILITY

---

<div class="row mt-4 mb-4">
  {% for item in site.data.bon-jovi %}
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
