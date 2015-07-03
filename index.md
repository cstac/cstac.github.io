---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
title: "築響系統科技有限公司"
header:
   image_fullwidth: "frontpage_header.jpg"
widget-1:
    title: "營業項目說明"
    url: 'services'
    text: ''
    image: works/description.jpg
widget-2:
    title: "實績案例"
    url: 'works'
    text: ''
    video: '<a href="/works" data-reveal-id="videoModal"><img src="http://phlow.github.io/feeling-responsive/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""></a>'
widget-3:
    title: "經銷商品"
    url: 'distributor'
    text: ''
    image: works/distributor.gif
---


<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
