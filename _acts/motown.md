---
layout: acts
image: assets/images/motown%20tribute%20acts%20and%20shows.jpg
description: motown has remained at the front of soul music and is as popular today as it's ever been. our motown tribute acts, with exceptional live vocals and harmonies is so close to the real thing - hearing is believing. all of these motown tribute bands boast fabulous costumes,  have amazing dance routines, and come with professional sound systems,  light shows and backdrops. <hr>
          INSTANT QUOTES & AVAILABILITY, lines open until 10pm
---

<div class="row mt-4 mb-4">
  {% for item in site.data.motown %}
    <div class="col-md-4 mb-5">
      <div class="card border-0 shadow h-100">
        <a href="/acts/{{ item.title | slugify }}">
          <img class="card-img-top" src="{{ item.image_src }}" alt="" />
        </a>
        <!-- <div class="card-body">
          <p class="description">{{ item.description }}</p>
          <a href="#" class="read-more">Read more</a>
        </div> -->
      </div>
    </div>
  {% endfor %}
</div>

<!-- <script>
  var readMoreButtons = document.querySelectorAll(".read-more");
  for (var i = 0; i < readMoreButtons.length; i++) {
    readMoreButtons[i].addEventListener("click", function() {
      this.parentNode.querySelector(".description").style.display = "block";
      this.style.display = "none";
      return false;
    });
  }
</script> -->