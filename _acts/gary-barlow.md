---
layout: acts
image:  ../assets/images/totally gaga tribute show.jpg
video_src: https://youtu.be/aSWhusz6pT4?feature=shared
description: lady gaga tribute show totally Gaga is a stunning live re-enactment of all Lady  Gaga’s finest moments. The show is not just a tribute, she impersonate’s, rather than imitates her character,her look,her moves and the voice are all Totally Gaga.All of Lady Gaga’s greatest live performances are 100% live vocals throughout the Totally Gaga show, including stunning acoustic renditions of Poker Face, Speechless and Edge of Glory. this is a fast moving, dynamic show recreating hit after  hiT.  book early to avoid disappointment. <hr>
            call now for advice, INSTANT QUOTES & AVAILABILITY
---

<div class="row mt-4 mb-4">
  {% for item in site.data.gary-barlow %}
    <div class="col-md-4 mb-5 mt-5">
      <div class="card border-0 shadow h-100">
        <a href="/acts/{{ item.title | slugify }}">
          <img class="card-img-top" src="{{ item.image_src }}" alt="" />
        </a>
      </div>
    </div>
  {% endfor %}
</div>