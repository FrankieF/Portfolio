---
layout: page
title: Designs
---

  <div>
    {% for design in site.data.settings.designs %}
        <div class="" data-block-type="47">
        <div class="sqs-block-content"><hr></div></div><div class="sqs-block button-block sqs-block-button sqs-col-6 span-6 float float-right" data-block-type="53"><div class="sqs-block-content">
        <div class="sqs-block-button-container sqs-block-button-container--center" data-animation-role="button" data-alignment="center" data-button-size="medium" data-button-type="primary">
        <a href="{{ site.url }}/assets/designs/{{ design.url }}" class="sqs-block-button-element--medium sqs-button-element--primary sqs-block-button-element" target="_blank" data-initialized="true">
            <h1>{{ design.name }}</h1>
        </a>
        </div>
        <div class="sqs-block html-block sqs-block-html" data-block-type="2" ata-alignment="center">
            <div class="sqs-block-content">
                <p class="sqs-block-button-element--medium sqs-button-element--primary sqs-block-button-element" style="white-space:pre-wrap;">{{ design.description }}</p>
            </div>
        </div>
    {% endfor %}
  </div>