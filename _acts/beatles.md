---
layout: acts
image: https://scotbase.com/images/the%20beatles%20tribute%20bands%20slide.jpg
# video_src: https://www.youtube.com/embed/kwOaqwIyKas?si=FyAYW6OFKMdkuAjb
description: STEP INTO THE SWINGING SIXTIES AND BOOK A BEATLES TRIBUTE FOR A NOSTALGIC EVENING OF THE MUSIC THAT SWEPT THE WORLD. CELEBRATING THE GREATEST ROCK AND ROLL GROUP OF ALL TIME IS OUR BEATLES TRIBUTES. IT IS THEIR LOOK, SOUND,  MANNERISMS, ACCENTS, COSTUMES, INSTRUMENTATION AND VOCAL HARMONIES, IN  THE MOST AUTHENTIC RECREATIONS THAT YOU WILL FIND.  IT IS A fab VISUAL AND  CONCERT EXPERIENCE THAT APPEAL TO AUDIENCE MEMBERS OF ALL AGES, and suits venues large and small. <hr>
            call our friendly team today for advice and booking information
---

<div class="row mt-4">
  {% for item in site.data.beatles %}
    <div class="col-md-4 mb-5">
      <div class="card border-0 shadow h-100">
        <a href="/acts/{{ item.title | slugify }}">
          <img class="card-img-top" src="{{ item.image_src }}" alt="" />
        </a>
      </div>
    </div>
  {% endfor %}
</div>
