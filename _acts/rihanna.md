---
layout: acts
image: https://scotbase.com/images/rihanna%20tribute%20acts-u629739-fr.jpg
description: scotbase rihanna tribute acts pay homage to the youngest solo artist to score fourteen number one singles on the billboard hot 100, and the fastest to do so. she’s sold more than 54 million albums and 210 million tracks worldwide and is the best selling digital artist of all time.So it's no surprise that our rihanna tribute acts are immensely popular. book an entertaining  pink tribute act to give your event pizzazz.  these acts appeal to mixed age audiences and suited to venues large and small. scotbase are proud to  represent these first class pink tribute acts and shows in the uk. <hr>
            call now for advice, INSTANT QUOTES & AVAILABILITY
---
<div class="row mt-4 mb-4">
  {% for item in site.data.rihanna %}
    <div class="col-md-4 mb-5">
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