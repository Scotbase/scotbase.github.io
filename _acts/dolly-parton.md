---
layout: acts
image: https://scotbase.com/images/dolly%20parton%20tribute%20acts-u626079-fr.jpg?crc=429696890
description: DOLLY PARTON tribute shows are a lot of fun and are a huge hit for all types of events. ENJOY THESE DIVAS AS THEY maintain the look of dolly  - 'It costs me a lot of money to look this cheap" -  with big hair, full on make-up and sparkly costumes .Dolly Parton is arguably the most important female singer-songwriter in country music history. She scored her first solo number one hit in 1970 with Joshua, and followed up with a string of No. 1 hits that included Jolene, I Will Always Love You and  Love Is Like a Butterfly.These TRIBUTES TO THE GREAT QUEEN OF COUNTRY are RESPECTFUL. NOT ONLY IS The music of DOLLY  brought to life BUT ALL HER GLAMOUR from THESE scotbase entertainments tribute  acts. hearing is believing and you wont believe your ears when you realise how close they are to the real DOLLY PARTON sound. <hr>
            INSTANT QUOTES & AVAILABILITY
---

<div class="row mt-4">
  {% for item in site.data.dolly-parton %}
    <div class="col-md-4 mb-5">
      <div class="card border-0 shadow h-100">
        <a href="/acts/{{ item.title | slugify }}">
          <img class="card-img-top" src="{{ item.image_src }}" alt="" />
        </a>
      </div>
    </div>
  {% endfor %}
</div>