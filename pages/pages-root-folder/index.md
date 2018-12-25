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
  title: "About me !"
  url: 'http://anshulverma31.github.io/engineering-data/info/'
  image: widget-1-302x182.jpg
  text: 'Every good portfolio website has a blog with fresh news, thoughts and develop&shy;ments of your activities. <em>Feeling Responsive</em> offers you a fully functional blog with an archive page to give readers a quick overview of all your posts.'
widget2:
  title: "Why I started this blog? "
  url: 'http://anshulverma31.github.io/engineering-data/blog/'
  text: 'Data engineering is the aspect of data science that focuses on practical applications of data collection and analysis. For all the work that data scientists do to answer questions using large sets of information, there have to be mechanisms for collecting and validating that information. In order for that work to ultimately have any value, there also have to be mechanisms for applying it to real-world operations in some way. Those are both engineering tasks: the application of science to practical, functioning systems.

  Disclaimer !!!
This blog is in no way affiliated with or endorsed by McKinsey & Company or any other management consulting firm.

The content of the blog posts is based on:
1. Personal experiences captured to the best of my recollection
2. General knowledge that is not client-confidential acquired during my time at the Firm
3. Anecdotes and information provided by other current and former management consultants
4. Articles, quotes, data, and other information from 3rd party sources will always be cited and linked to, whenever possible.
  '
  image: widget-1-302x182.jpg
widget3:
  title: "I help with : "
  url: 'http://anshulverma31.github.io/engineering-data/info/'
  image: widget-github-303x182.jpg
  text: '* Data Engineering
  * Data Architecture
  * Data Governance'
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
