---
layout: page-fullwidth
title:  ""
#subheadline:  "Multi-Device Layouts"
#teaser: "The full-width page format gives you all the space you need to show your content using the grid."
header:
    title: Interacting with Colors 
    background-color: "#EFC94C;"
#    pattern: pattern_concrete.jpg
    image_fullwidth: header_colors.jpg
permalink: "/tech/"
---


First there was Flippaper, a project between a drafting table and a pinball. Take a few felt pens, draw a few shapes, press SCAN and ta-dah!, not only does your drawing lights up but a virtual ball appears and react to it. Through a language of shapes and colours, Flippaper allows you to create your own pinball, game-play and look.

Over time, we realised that this idea of interaction between colour and paper was more than just one project worthy and that we were not bound by paper and felt pens. This motivated us to first create a library and then release setups to ease the whole canvas/pigment interaction process.


<div class="row">
    
    <div class="medium-8 columns t30">
    <h3>The concept</h3>

    Our core principle is to be able to interact with a drawing made on any surface. More than that, it's to allow the machine to behave in a way that is linked with the drawing. Sometimes this will end up as an interaction (for instance the Flippaper) sometimes it can stay generative (a machine that will try to complete the drawing you gave it).
<br>
For that to happen, our technology will issue a set of description from the drawing captured. This description will be then linked with behaviour that will define how the machine (and user) interact with the drawing.
<br>
The canvas can be a wall, a chalkboard, a thin waffle... and the drawing can be based on paint cans, magnets, felt pens, coloured sugary syrups...

    </div><!-- /.medium-4.columns -->

    <div class="medium-4 columns t30">
    <img class="inrow" src="{{ site.urlimg }}ourtech_concept.jpg" alt="">
    </div>
</div><!-- /.row -->


<div class="row">
    
    <div class="medium-4 columns t30">
    <img class="inrow" src="{{ site.urlimg }}ourtech_kit_2.jpg" alt="">
    </div>

    <div class="medium-4 columns t30">
    <img class="inrow" src="{{ site.urlimg }}ourtech_kit_1.jpg" alt="">
    </div>

    <div class="medium-4 columns t30">
    <h3>The kit</h3>
    In order to both capture the drawing and draw on top of it, you need a webcam, a video projector and ... a way to attach them. For that, we're creating a stand that makes it easy to use the whole system both on a table and on a wall. Nice for prototyping, as good for exhibiting your projects.
    </div><!-- /.medium-4.columns -->

</div><!-- /.row -->

<div class="row">
    
    <div class="medium-8 columns t30">
    <h3>The library, PTX system</h3>
The library is an ever growing bite of code which holds both the core mechanism (description of drawing) as well as a template to help calibrate the system. This templates is a graphical interface that allows you to calibrate your picture (both on the exposure/colour and on the optical correction side), specify the colours of interest and helps you debug any issue along the way. The templates is also a very good starting point for your own project since all the little things are already taken care of for you.
<br>
<br>
Right now, the library exist both in C++ (we use it with Cinder, should work with everything) and in Java (aimed at Processing). Once all calibration is done, the library returns you a list of areas (each is a separate part of your drawing) with a list of descriptions. It's then up to you to use them in your code to give life to some crazy, or even non crazy, ideas!

    </div><!-- /.medium-4.columns -->

    <div class="medium-4 columns t30">
    <img class="inrow" src="{{ site.urlimg }}ourtech_library.jpg" alt="">
    </div>
</div><!-- /.row -->
<br>
<div>
Curious about all that? Drop us a message by mail or through the social links in the top navigation bar, we'll be happy to hear from you!
</div>
