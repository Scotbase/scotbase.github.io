---
layout: acts
image: https://scotbase.com/images/motown%20tribute%20acts%20and%20shows.jpg?crc=103598974
---

<div class="row">
  {% for item in site.data.motown %}
    <div class="col-md-4 mb-5">
      <div class="card border-0 shadow h-100">
        <a href="/acts/{{ item.title | slugify }}">
          <img class="card-img-top" src="{{ item.image_src }}" alt="" />
        </a>
        <div class="card-body">
          <p class="description">{{ item.description }}</p>
          <a href="#" class="read-more">Read more</a>
        </div>
      </div>
    </div>
  {% endfor %}
</div>

<script>
  var readMoreButtons = document.querySelectorAll(".read-more");
  for (var i = 0; i < readMoreButtons.length; i++) {
    readMoreButtons[i].addEventListener("click", function() {
      this.parentNode.querySelector(".description").style.display = "block";
      this.style.display = "none";
      return false;
    });
  }
</script>