---
layout: page
title: Code
---

  <div>
    {% for code in site.data.settings.codes %}
        <div class="" data-block-type="47">
        <div class="sqs-block-content"><hr></div></div><div class="sqs-block button-block sqs-block-button sqs-col-6 span-6 float float-right" data-block-type="53"><div class="sqs-block-content">
        <div class="sqs-block-button-container sqs-block-button-container--center" data-animation-role="button" data-alignment="center" data-button-size="medium" data-button-type="primary">
        <a href="{{ code.url }}" class="sqs-block-button-element--medium sqs-button-element--primary sqs-block-button-element" target="_blank" data-initialized="true">
            <h1>{{ code.name }}</h1>
        </a>
        </div>
        <div class="sqs-block html-block sqs-block-html" data-block-type="2" ata-alignment="center">
            <div class="sqs-block-content">
                <p class="sqs-block-button-element--medium sqs-button-element--primary sqs-block-button-element" style="white-space:pre-wrap;">{{ code.description }}</p>
            </div>
        </div>
        <div class="sqs-block horizontalrule-block sqs-block-horizontalrule" data-block-type="47" id="block-yui_3_17_2_1_1652170278642_46940"><div class="sqs-block-content"><hr></div></div><div class="sqs-block button-block sqs-block-button sqs-col-6 span-6 float float-right" data-block-type="53" id="block-yui_3_17_2_1_1610461783598_57110"><div class="sqs-block-content" id="yui_3_17_2_1_1660822141772_77">
    {% endfor %}
  </div>