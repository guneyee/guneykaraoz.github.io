---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_12.jpg
widget1:
  title: "🎯 Projelerim"
  url: '/projects/'
  image: widget-1-302x182.jpg
  text: 'Blockchain, Web3 ve yazılım geliştirme projelerim. Akıllı kontratlardan veri bilimi uygulamalarına kadar çalıştığım projeleri keşfedin.'
widget2:
  title: "ℹ️ Hakkımda"
  url: '/about/'
  text: 'Matematik öğrencisi, blockchain geliştirici ve siber güvenlik meraklısı. Kariyer yolculuğum ve teknolojiye tutkum hakkında bilgi edinin.'
  video: '<a href="#" data-reveal-id="videoModal"><img src="http://phlow.github.io/feeling-responsive/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "💻 GitHub"
  url: 'https://github.com/guneyee'
  image: widget-github-303x182.jpg
  text: 'Tüm açık kaynak projelerim, katkılarım ve kod örneklerim GitHub profilimde. Blockchain ve Web3 projelerini buradan takip edebilirsiniz.'
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
callforaction:
  url: /cv/
  text: CV'mi İndir ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
  <a class="close-reveal-modal">&#215;</a>
</div>
