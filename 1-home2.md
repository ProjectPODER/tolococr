---
layout: home
title: Home
permalink: /home
---

# THIS IS THE FIRST TITLE

This text is a paragraph.
This won't be another paragraph, it will join the line above it.

This will be another paragraph, as it has a blank line above it.

[Website version](https://towerbuilder.poderlatam.org/)
[Website iframe version](https://towerbuilder.poderlatam.org/?iframe)
[Visualization iframe](https://towerbuilder.poderlatam.org/iframe-visualization/)
[Slider iframe](https://towerbuilder.poderlatam.org/iframe-slider/)

<section class="">
  <div class="container">
    <div class="row w-100">
      <div class="col-lg-12">
        {% for home-section in site.home %}
        {% capture id %}{{ home-section.id | remove:'/' | remove:'home' | downcase }}{% endcapture %}
        <div class="section">
          <div class="container">
            <div class="row align-items-center">
              {%- if home-section.image -%}
              <div class="col-lg-5 col-md-5 col-sm-12">
                {{ home-section.content }}
              </div>
              <div class="col-lg-7 col-md-7 col-sm-12 text-center">
                <img data-src="{{ site.baseurl }}/assets/img/{{home-section.image}}" class="img-fluid">
              </div>
              {%- else -%}
              <div class="col-lg-12 col-md-12 col-sm-12 text-center">
                {{ home-section.content }}
              </div>
              {%- endif -%}
            </div>
          </div>
        </div>
        {% endfor %}
      </div>
    </div>
  </div>
</section>