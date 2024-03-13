---
layout: acts
image:  ../assets/images/whitney houston tribute acts.jpg
description: our whitney houston tribute acts pay homage to the glamorous star who was the most awarded female artist of all time,  with two Emmy Awards, six Grammy Awards, 30 Billboard Music Awards, 22 American Music Awards, among a total of 415 career awards as of 2010.She held the all-time record for the most American Music Awards of any female solo artist and shared the record with Michael Jackson for the most AMAs ever won in a single year with eight wins in 1994.Houston won a record 11 Billboard Music Awards at its fourth ceremony in 1993.[348] She also had the record for the most WMAs won in a single year, winning five awards at the 6th World Music Awards in 1994. she went on to win an MTV Video Music Award when "You Belong with Me" was named Best Female Video.we are proud to present these fabulous whitney tribute acts who do more than justice to the queen of the night.our whitney houston tribute acts are in big demand so book well in advance of your venue date to avoid disappointment. <hr>
            call today for advice, QUOTES & AVAILABILITY
---

<div class="row mt-4 mb-4">
  {% for item in site.data.whitney %}
    <div class="col-md-4 mb-5 mt-5">
      <div class="card border-0 shadow h-100">
        <a href="/acts/{{ item.title | slugify }}">
          <img class="card-img-top" src="{{ item.image_src }}" alt="" />
        </a>
      </div>
    </div>
  {% endfor %}
</div>