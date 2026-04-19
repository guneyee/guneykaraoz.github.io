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
  title: "My Projects"
  url: '/projects/'
  image: widget-1-302x182.jpg
  text: 'Check out my latest projects and work. From web applications to open source contributions, see what I&#39;ve been building.'
widget2:
  title: "About Me"
  url: '/about/'
  text: 'Learn more about my background, skills, and experience as a software developer. Discover my journey in technology and what drives my passion for coding.'
  video: '<a href="#" data-reveal-id="videoModal"><img src="http://phlow.github.io/feeling-responsive/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "My GitHub"
  url: 'https://github.com/guneyee'
  image: widget-github-303x182.jpg
  text: 'Explore my code repositories, contributions, and open source projects on GitHub. See the technologies I work with and my coding style.'
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
  text: Download My CV ›
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
