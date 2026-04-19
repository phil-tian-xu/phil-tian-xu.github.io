---
layout: about  # Uses the about page layout from _layouts/
title: about  # Internal page title
permalink: /  # This makes this page your homepage
subtitle: PhD Student in Financial Engineering, The Chinese University of Hong Kong.  #small line under your name

profile:  # This controls everything on the right side panel
  align: right  # left or right
  image: 01_body.jpg  # profile picture, under assets/img/
  image_circular: false # crops the image to make it circular
  more_info: >  # html content, shows directly under my picture.
    <p></p>

selected_papers: false # includes Selected Publications section at bottom, pulls from _bibliography/papers.bib, only shows `selected = {true}`
social: true # includes social icons at the bottom of the page. Enables icons like: GitHub, LinkedIn, Google Scholar. They are configured in: _data/socials.yml

announcements:  # Controls `news` section. Content comes from: `news/`
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:  # Controls `latest posts` section. Content comes from `_posts/`
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts

# Main body content, everything after `---`:
---
I am a PhD student in Finance at the Chinese University of Hong Kong. My research focuses on empirical asset pricing and machine learning.
