---
layout: acts
image: assets/images/elton%20john%20tribute%20acts.jpg
description: Sir Elton John is one of pop music's great survivors. Born 25 March, 1947, as Reginald Kenneth Dwight, he started to play the piano at the early age of four. At the age of 11, he won a scholarship to the Royal Academy of Music.He became the most successful pop artist of the 1970s, and he has survived many different pop fads including punk, the New Romantics and Britpop to remain one of Britain's most internationally acclaimed musicians.We are proud to present the most authentic elton john tribute acts.  these are popular shows who leave their audiences wanting more.  book early to avoid disappointment. <hr>
            call now for advice, INSTANT QUOTES & AVAILABILITY
---

<div class="row mt-4 mb-4">
  {% for item in site.data.elton-john %}
    <div class="col-md-4 mb-5">
      <div class="card border-0 shadow h-100">
        <a href="/acts/{{ item.title | slugify }}">
          <img class="card-img-top" src="{{ item.image_src }}" alt="" />
        </a>
      </div>
    </div>
  {% endfor %}
</div>