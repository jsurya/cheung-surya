---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: minimal
title: Alex & Jess
subtitle: 09.13.25
header_type:: splash
header_image: "https://github.com/jsurya/cheung-surya/blob/main/img/celebrityedge-ship.jpg?raw=true"
permalink: /
---

{% for post in site.posts %}
 <section id="scroll">
    <div class="container px-5">

      <p>  {{ post }}</p>

    </div>
</section>
{% endfor %}
