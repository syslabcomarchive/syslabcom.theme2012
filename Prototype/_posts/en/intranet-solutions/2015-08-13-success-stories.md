---
layout: sub-page
title: Success stories
name: success-stories
category: intranet-solutions
tagline: Success stories
lang: en
---



{% assign stories=site.categories['success-stories'] | where:"lang", page.lang %}
<div class="item" id="logos">
    <p class="logo-cloud">
        {% for item in stories %}
        <blockquote>
            <a title="{{ item.summary }}" href="{{ item.url }}#main" class="pat-inject pat-switch" data-pat-inject="target: #modal-content" data-pat-switch="selector: body; add: modal-active"><img src="/media/{{ item.logo }}.jpg" alt="" />
                {{ item.title }}
                {% if item.summary %}
                    <br><em>{{ item.summary }}</em>
                {% endif %}
            </a>
        </blockquote>
        {% endfor %}
    </p>
</div>