---
title: Aula 11 - Fundamentos de NodeJs
nav_order: 11
has_children: true
has_toc: false
youtubeId: HQWFNwvxZx0
next: 01-introducao
---
{% assign title = page.title | split: "-" %}
{% assign slide =  title[1] | replace: " ", "-" %}

## {{ title | slice: 1 }}

### Recurso

<span class="fs-3">
<a href="{{site.baseurl}}/assets/downloads/{{ page.nav_order }}{{ slide }}.pdf" class="btn" target="_blank">Notas de aula</a>
<a href="https://www.icloud.com/keynote/0vGSUyeYDqiIPQYHqHpQubOAA#09-Fundamentos-de-NodeJS" class="btn" target="_blank">Notas de aula com animações</a>
</span>

{% include youtubePlayer.html id=page.youtubeId %}

<span class="fs-3 float-right">
[Próxima aulas]({{page.next}}){: .btn }
</span>

