---
layout: acts
image: https://scotbase.com/images/book%20psychic%20shows-u611550-fr.jpg?crc=4041079141
description: the psychics at scotbase deal with the foreseeable and the  unforeseeable. Our psychics work with spirit guides to provide you with the answers you need. <hr> Have you ever wondered what the future might hold for you? Do you wonder about past life experiences? Do you want to know when you will meet your true love?the psychics at scotbase deal with the foreseeable and the  unforeseeable. Our psychics work with spirit guides to provide you with the answers you need.They will convey your thoughts and wishes across the divide through psychic medium readings. Open your heart and call to book a psychic  today. BOOK YOUR ACT TODAY! book early to avoid disappointment.
            call today for INSTANT QUOTES & AVAILABILITY
---

<div class="row mt-4 mb-4">
  {% for item in site.data.psychics %}
    <div class="col-md-4 mb-5">
      <div class="card border-0 shadow h-100">
        <a href="/acts/{{ item.title | slugify }}">
          <img class="card-img-top" src="{{ item.image_src }}" alt="" />
        </a>
      </div>
    </div>
  {% endfor %}
</div>