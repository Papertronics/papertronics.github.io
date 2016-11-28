---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_colors.jpg
widget1:
  title: "Our Technology"
  url: '/tech/'
  image: home_1.jpg
  text: 'Colours every where! On walls, on paper, on your cloths, even on your food. And guess what? You can interact with it! Curious to know how? Well, click and open up a new world of messiness.' 
widget2:
  title: "Projects"
  url: '/project/'
  text: 'Ok, you know we are playing with colors. But what are we doing with it? Numerous things, some of them eatable. Come check them!' 
  image: home_2.gif
widget3:
  title: "Services"
  url: '/services/'
  image: home_3.jpg
  text: 'We are a helpful bunch of lads, we teach, we share and we even do stuff for you. Who would have guessed? Certainly not our parents.' 
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#

#callforaction:
#  url: https://tinyletter.com/feeling-responsive
#  text: Inform me about new updates and features ›
#  style: alert
permalink: /index.html

#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---


<center><hr width="60%"/></center>


<div class="row">
   <div class="medium-8 columns t30">
   <h3>A little bit about the team</h3>
       Jéremie Cortial and Roman Miletitch are the left and right arms of Papertronics, aiming to find more natural and physical (who said carnal?) ways to interact with new technologies. Pigments on canvas was used by cavemen, so it felt good enough for us. Felt pen on paper, coloured food syrup on thin white waffle, graff on a wall, body paint on bodies... draw by any means necessary, and grant your drawing life by using our home made technology.
   </div>

   <div class="medium-4 columns t30">
   <img class="inrow" src="{{ site.urlimg }}jer_rom_short.jpg" alt="">
    </div>
</div>
 
<br>



<center><hr width="60%"/></center>


<h3>A little bit about our first child</h3>
<br>
<div class="flex-video">
  <iframe width="560" height="315" src="https://www.youtube.com/embed/0MocUzeT8Lw" frameborder="0" allowfullscreen></iframe>
</div>

