---
layout: index
title: Index
permalink: /
inmenu: true
---
<div class="sticky top0">
    <nav>
        <ul class="flex flex_direction_row" >
            {% for anchor in site.data.anchors.mainpage %}
                <li class="inline"><a href='#{{ anchor.anchor }}'>{{ anchor.txt }}</a></li>
            {% endfor %}
        </ul>
</nav>
</div>
{% include top.html %}
{% include vpnfiles.html %}
{% include djinnitxt.html %}
{% include skulletje.html %}