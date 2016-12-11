---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: main-header.png

overview:
  title: Overview
  text: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus quis dictum nulla. Nullam hendrerit lorem porta placerat aliquam. Sed mattis egestas erat in tristique. Nulla eget urna sed ligula ultricies ultrices. Donec id justo vitae nulla mattis interdum vel eu eros. Sed et leo nec nunc consectetur rutrum. In vulputate turpis nec justo euismod sollicitudin. Praesent quis convallis dolor. Cras quis rhoncus ante. Fusce at nunc lacus. Etiam placerat massa magna, a laoreet elit eleifend ut. Nam a interdum nibh. Morbi nulla ante, elementum sed volutpat eu, tempor id justo. Phasellus rhoncus odio vitae ipsum imperdiet lobortis. Praesent varius nisi urna, ac iaculis mi imperdiet ac.

widget1:
  title: "DinamiX"
  url: 'http://localhost:4000/dinamix/'
  image: 'http://dummyimage.com/302x183/334d5c/efc94c.png&text=Placeholder'
  text: 'A Dynamic Agreement Marketplace on Internet eXchange Points'
widget2:
  title: "Harmony"
  url: 'http://localhost:4000/harmony/'
  image: '/images/logo-harmony-site.png'
  text: 'Efficiently Delivering Online Services through Coopetition between ISP Networks and App Providers'
widget3:
  title: "Hybrid Control Planes"
  url: 'http://localhost:4000/hybrid_coop_cp/'
  image: 'http://dummyimage.com/302x183/334d5c/efc94c.png&text=Placeholder'
  text: 'Control Plane Cooperation Design towards robust programmable WANs'
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
  url: https://tinyletter.com/
  text: Inform me about new updates ›
  style: alert
permalink: /index.html
---
