---
layout: acts
image: assets/images/justin%20timberlake%20tribute%20acts.jpg
description: our justin timberlake tribute acts pay homage to the Singer who got his start on 'The New Mickey Mouse Club' and made it big with boy band NSYNC, before becoming a solo singer and actor.In 2002, Timberlake decided to pursue a solo career, debuting with the hit song "Like I Love You". Later that year, he released his first solo album, Justified, which sold more than 7 million copies worldwide. He received two Grammy Awards in 2004 for Best Pop Vocal Album and Best Male Pop Vocal Performance.As a solo artist, Timberlake has often collaborated with the Black Eyed Peas, receiving a Grammy nomination with the band for "Where Is The Love?" He has also worked with Nelly, Snoop Dogg and Nelly Furtado. in 2005 he released his second solo album, FutureSex/LoveSounds, which debuted at Number 1 on the Billboard chart. The album's lead single, "SexyBack", spent several consecutive weeks at Number 1.our justin timberlake tribute shows have all the energy and bounce of the real thing. <hr>
            call now for advice, INSTANT QUOTES & AVAILABILITY
---

<div class="row mt-4 mb-4">
  {% for item in site.data.justin-timberlake %}
    <div class="col-md-4 mb-5">
      <div class="card border-0 shadow h-100">
        <a href="/acts/{{ item.title | slugify }}">
          <img class="card-img-top" src="{{ item.image_src }}" alt="" />
        </a>
      </div>
    </div>
  {% endfor %}
</div>
