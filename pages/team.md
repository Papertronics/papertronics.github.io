---
layout: page-fullwidth
title:  ""
#subheadline:  "Multi-Device Layouts"
#teaser: "The full-width page format gives you all the space you need to show your content using the grid."
header:
    title: The Team
    background-color: "#EFC94C;"
#    pattern: pattern_concrete.jpg
    image_fullwidth: header_colors.jpg
permalink: "/about/"
---

<div class="row">
    
    <div class="medium-8 columns t30">
    <h3>Us</h3>
        Jéremie Cortial and Roman Miletitch are the left and right arms of Papertronics, aiming to find more natural and physical (who said carnal?) ways to interact with new technologies. Pigments on canvas was used by cavemen, so it felt good enough for us. Felt pen, paint or coloured dot stickers on papers, coloured food syrup on thin white waffle, graff on a wall, body paint on bodies... draw by any means necessary, and grant your drawing life by pressing the magical SCAN button. What was static becomes dynamic, alive. A whole new world of messy interactions opens up. We're the welcoming committee.
    </div>

    <div class="medium-4 columns t30">
    <img class="inrow" src="{{ site.urlimg }}jer_rom.jpg" alt="">
    </div>
</div>



<h3>Him & Me</h3>

<br/>
<br/>

<p>
{% for author in site.data.team %}
    <p class="memberText">
        <div class="memberImage"><img alt="{{ author.firstname }}" src="{{ site.url }}/assets/img/{{ author.firstname }}.jpg" /></div>
            <span id="{{ author.firstname }}" class="authorName">{{ author.firstname }} {{ author.lastname }}</span>: {{ author.bio }}
            <br/>
            Email: <a href="mailto:{{ author.email }}">{{ author.email }}</a> <br/>
            Website: <a href="{{ author.website }}">{{ author.website }}</a>
            {% unless forloop.last %}
                </p>
                <center><hr width="60%"/></center>
                <br/>
            {% endunless %}
{% endfor %}
</p>

