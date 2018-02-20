---
layout: home
country: eu
---

<div class="home">
  <div class="row" id="splash-row">
    <div class="col-sm-12">
      <div class="carousel slide" data-ride="carousel" id="splash-box">
        <div class="carousel-inner" role="listbox">
          {% include home_carousel_galaxy.html %}
          {% include home_carousel_usegalaxy_eu.html %}

          <div class="item carousel-item jumbotron">
            <h2 class="display-3">Who is involved?</h2>
            <p>useGalaxy.eu is maintained by: <a href="/freiburg">Freiburg Galaxy Team</a></p>
          </div>

          {% include home_carousel_training.html %}
          {% include home_carousel_acknowledgments.html %}
        </div>
        <a class="left carousel-control" href="#splash-box" role="button" data-slide="prev">
          <span class="icon-prev" aria-hidden="true"></span>
          <span class="sr-only">
            <previous></previous>
          </span>
        </a>
        <a class="right carousel-control" href="#splash-box" role="button" data-slide="next">
          <span class="icon-next" aria-hidden="true"></span>
          <span class="sr-only">
            <next></next>
          </span>
        </a>
      </div>
    </div>
  </div>

  {% include home_news_events.html %}
  {% include home_done.html %}
</div>
