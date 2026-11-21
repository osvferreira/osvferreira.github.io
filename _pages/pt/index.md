---
layout: about
title: português
permalink: /pt/
nav: true
nav_order: 6
description: Osvaldo Ferreira Neto, pesquisador de pós-doutorado no Instituto de Física da Universidade de São Paulo (IF-USP).
subtitle: Pesquisador de pós-doutorado · <a href='https://portal.if.usp.br/' target='_blank'>Instituto de Física da Universidade de São Paulo</a>

profile:
  align: right
  image: osvaldo_profile.jpg
  image_circular: true
  more_info: >
    <p>Instituto de Física, USP</p>
    <p>Rua do Matão, 1371</p>
    <p>São Paulo, SP, Brasil</p>

selected_papers: true
social: true

announcements:
  enabled: false

latest_posts:
  enabled: false
---

<p class="text-right"><a href="{{ '/' | relative_url }}">🇬🇧 English version</a></p>

<p class="text-center">
<a href="{{ '/pt/publicacoes/' | relative_url }}">Publicações</a> ·
<a href="{{ '/pt/palestras/' | relative_url }}">Palestras</a> ·
<a href="{{ '/pt/pesquisa/' | relative_url }}">Pesquisa</a> ·
<a href="{{ '/pt/ensino/' | relative_url }}">Ensino & Divulgação</a> ·
<a href="{{ '/pt/cv/' | relative_url }}">CV</a>
</p>

Sou pesquisador de pós-doutorado no [Instituto de Física da Universidade de São Paulo](https://portal.if.usp.br/) (IF-USP), com bolsa FAPESP, e membro do projeto temático _Análise de dados multidisciplinar em Big Data: de Física de Altas Energias à astrofísica e Ciências Médicas_. Sou doutor em Física pela Universidade Federal do Rio de Janeiro (UFRJ, 2026), sob orientação de [Eduardo Fraga](https://inspirehep.net/authors/1009599), com doutorado-sanduíche na Universidade Goethe de Frankfurt (Alemanha) pelo programa CAPES-PrInt, com [Jürgen Schaffner-Bielich](https://inspirehep.net/authors/990034). Sou mestre em Física pela UFRJ e bacharel em Física de Materiais pela Universidade Federal de Uberlândia (UFU).

Minha pesquisa situa-se na interface entre física nuclear, astrofísica e cosmologia, com foco no **comportamento da matéria fortemente interagente em condições extremas e nas formas de observá-la**. No universo primordial, investigo a transição da QCD (incluindo a condensação de píons induzida por grandes assimetrias leptônicas) e suas assinaturas no fundo cosmológico de ondas gravitacionais. Em astrofísica, estudo estrelas compactas como sondas da matéria em densidades muito altas. Também investigo propriedades da matéria quente e densa, como sua resposta eletromagnética, utilizando métodos de QCD perturbativa.

Mais recentemente, tenho aplicado métodos de inferência bayesiana à fenomenologia de colisões de íons pesados, contribuindo para as atividades da colaboração ExTrEMe (EXperiment and TheoRy in Extreme MattEr).

#### Interesses

- Diagrama de fases da QCD e a época da QCD no universo primordial
- Fundo cosmológico de ondas gravitacionais
- Estrelas compactas, matéria densa e matéria escura
- QCD quente e densa com métodos perturbativos
- Inferência bayesiana em colisões de íons pesados

#### Formação

- **Doutorado em Física**, 2026, Universidade Federal do Rio de Janeiro (com período sanduíche na Universidade Goethe de Frankfurt)
- **Mestrado em Física**, 2022, Universidade Federal do Rio de Janeiro
- **Bacharelado em Física de Materiais**, 2019, Universidade Federal de Uberlândia

#### Palestras recentes

<ul>
{%- for t in site.data.talks limit: 5 -%}
<li><strong>{{ t.title }}</strong>, {{ t.event }}{% if t.location %} ({{ t.location }}){% endif %}, {{ t.year }}{% if t.award_pt %} <i class="fa-solid fa-trophy" title="{{ t.award_pt }}"></i> <em>{{ t.award_pt }}</em>{% endif %}</li>
{%- endfor -%}
</ul>
<p><a href="{{ '/pt/palestras/' | relative_url }}">Ver todas as palestras →</a></p>
