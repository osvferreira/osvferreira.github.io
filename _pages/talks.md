---
layout: page
permalink: /talks/
title: talks
description: talks and posters at conferences, workshops, schools and seminars.
nav: true
nav_order: 2
---

<p class="text-right"><a href="{{ '/pt/palestras/' | relative_url }}">🇧🇷 Versão em português</a></p>

{% assign talks_by_year = site.data.talks | group_by: "year" %}

<div class="talks">
{%- for group in talks_by_year -%}
<h2 class="year">{{ group.name }}</h2>
<ul>
{%- for t in group.items -%}
<li class="mb-2"><strong>{{ t.title }}</strong>{% if t.event %}<br>{{ t.event }}{% endif %}{% if t.location %} · {{ t.location }}{% endif %}{% if t.type %} · <em>{{ t.type }}</em>{% endif %}{% if t.slides %} · <a href="{{ t.slides }}" target="_blank" rel="noopener noreferrer">slides</a>{% endif %}{% if t.award %}<br><i class="fa-solid fa-trophy"></i> {{ t.award }}{% endif %}</li>
{%- endfor -%}
</ul>
{%- endfor -%}
</div>
