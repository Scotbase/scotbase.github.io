---
layout: acts
image:  ../assets/images/luther vandross tribute acts.jpg
description: our luther vandross tribute acts and shows respectfully pay homage to the Grammy Awards winning singer.  Luther vandross was a permanent and dynamic force in popular music. He crossed boundaries, starting with his earliest success as a background vocalist and arranger for David Bowie, Bette Midler, Barbra Streisand, Donna Summer, Carly Simon, Judy Collins, J. Geils Band, Ben E. King, Ringo Starr and Chic.For almost 25 years, from 1981 to 2005, Luther dominated the American R&B music charts like no other artist before or since. In that span Luther released eight number 1 R&B albums, seven number 1 R&B singles and another five Top 20 R&B singles.He achieved crossover status with eight Billboard Top 10 albums, including reaching number 1 with 2003’s Dance With My Father; and another five Top 10 Billboard Hot 100 singles.our van luther tribute shows bring back to life his distinctive brand of satin smooth vocal magic that moved international audiences and continues to touch people to this day. <hr>
            call now for advice, INSTANT QUOTES & AVAILABILITY
---

<div class="row mt-4 mb-4">
  {% for item in site.data.luther-vandross %}
    <div class="col-md-4 mb-5">
      <div class="card border-0 shadow h-100">
        <a href="/acts/{{ item.title | slugify }}">
          <img class="card-img-top" src="{{ item.image_src }}" alt="" />
        </a>
      </div>
    </div>
  {% endfor %}
</div>