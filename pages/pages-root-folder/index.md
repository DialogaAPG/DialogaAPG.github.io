---
permalink: /index.html

#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage

header:
  image_fullwidth: black.png

widget1:
  title: "Quem somos?"
  url: '/integrantes/'
  image: widget-1-302x182.jpg
  text: 'Contamos com integrantes do IFSC, da EESC e do ICMC. Venha participar, como membro, com propostas/sugestões de programa ou com o seu apoio!'

widget2:
  title: "Nossas propostas"
  url: '/propostas/'
  image: widget-1-302x182.jpg
  text: 'Leia nossas propostas e entre em contato com os nossos integrantes para colaborar com o nosso programa!'

widget3:
  title: "Calendario"
  url: '/calendario/'
  image: widget-1-302x182.jpg
  text: 'Fique atento ao calendario das eleições!!'

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

#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
