---
layout: page
title: "bitcoin arbitrage"
description: "Where to trade Bitcoin? What are good exchanges for altcoin trading? Who has lowest fees?"
permalink: /category/arbitrage/
---

<h4 class="exa">All posts related to <b>bitcoin arbitrage</b> or <b>altcoin arbitrage</b></h4>

<span id="note">"Bitcoin Arbitrage"</span>

{% for post in site.posts %}
  {% if post.category contains "bitcoin arbitrage" or post.categories contains "bitcoin arbitrage" %}
  <h4 class="post">
  <strong>
  <a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title | capitalize }}</a>
  </strong>
  <small>{{ post.date | date_to_string }}</small>
  </h4>
  <p>
  {{ post.description }}
  </p>
  {% endif %}
{% endfor %}

<span id="note">"Altcoin Arbitrage"</span>

{% for post in site.posts %}
  {% if post.category contains "altcoin arbitrage" or post.categories contains "altcoin arbitrage" %}
  <h4 class="post">
  <strong>
  <a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title | capitalize }}</a>

  </strong>
  <small>{{ post.date | date_to_string }}</small>
  </h4>
  <p>
  {{ post.description }}
  </p>
  {% endif %}
{% endfor %}


{{ site.ads.ledger }}

<span id="note">"Arbitrage Bots"</span>

{% for post in site.posts %}
  {% if post.category contains "arbitrage bots" or post.categories contains "arbitrage bots" %}
  <h4 class="post">
  <strong>
  <a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title | capitalize }}</a>
  </strong>
  <small>{{ post.date | date_to_string }}</small>
  </h4>
  <p>
  {{ post.description }}
  </p>
  {% endif %}
{% endfor %}
