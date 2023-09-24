---
title: About
---

<div class="about">

<img src="/assets/images/about/face.jpg" id="leftflex">

<div id="rightflex">
I'm Steven Impson. A software developer, writer and podcaster in Adelaide, South Australia.

I develop back-end software during the day, and muse about video games in the rest of the time.

<nav class="links">
    <ul id="linklist">
    {% for item in site.data.links %}
        <li>
            <a href="{{ item.link }}" {% if page.url == item.link %}class="current"{% endif %} {% if item.link == "/" %}class="title"{% endif %}>{{ item.name }}</a>
        </li>
    {% endfor %}
    </ul>
</nav>
</div>
</div>


