---
layout: page
permalink: /pt/palestras/
title: palestras
description: apresentações orais e pôsteres em conferências, workshops, escolas e seminários.
nav: false
---

<p class="text-right"><a href="{{ '/talks/' | relative_url }}">🇬🇧 English version</a> · <a href="{{ '/pt/' | relative_url }}">início</a></p>

{% assign talks_by_year = site.data.talks | group_by: "year" %}

<div class="talks">
{%- for group in talks_by_year -%}
<h2 class="year">{{ group.name }}</h2>
<ul>
{%- for t in group.items -%}
{%- case t.type -%}{%- when "talk" -%}{%- assign tipo = "palestra" -%}{%- when "poster" -%}{%- assign tipo = "pôster" -%}{%- when "seminar" -%}{%- assign tipo = "seminário" -%}{%- else -%}{%- assign tipo = t.type -%}{%- endcase -%}
<li class="mb-2"><strong>{{ t.title }}</strong>{% if t.event %}<br>{{ t.event }}{% endif %}{% if t.location %} · {{ t.location }}{% endif %}{% if tipo %} · <em>{{ tipo }}</em>{% endif %}{% if t.slides %} · <a href="{{ t.slides }}" target="_blank" rel="noopener noreferrer">slides</a>{% endif %}{% if t.award_pt %}<br><i class="fa-solid fa-trophy"></i> {{ t.award_pt }}{% endif %}</li>
{%- endfor -%}
</ul>
{%- endfor -%}
</div>
