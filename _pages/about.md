---
layout: about
title: about
permalink: /
subtitle: Integrated M.S./Ph.D. Student, <a href='http://cvl.ewha.ac.kr/'>Computer Vision Lab</a>, Ewha Womans University.

profile:
  align: right
  image: jiyeong_profile.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Computer Vision Lab</p>
    <p>Ewha Womans University</p>
    <p>Seoul, South Korea</p>

selected_papers: false # publications are shown directly on the homepage below
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I am an Integrated M.S./Ph.D. student at the [Computer Vision Lab](http://cvl.ewha.ac.kr/), Ewha Womans University, advised by Prof. Dongbo Min.

My research focuses on building models that understand real-world visual data, adapt across domains, and remain practical enough to deploy. My interests span computer vision, multimodal learning, domain-adaptive semantic segmentation, and self-supervised learning.

Feel free to reach out via [email](mailto:wldud8946@gmail.com) if you would like to discuss research or collaboration.

<div class="clearfix"></div>

<div class="publications">

<h2 class="bibliography">Conference &amp; Preprint</h2>
{% bibliography --query @*[category=conference] %}

<h2 class="bibliography">Journal</h2>
{% bibliography --query @*[category=journal] %}

</div>
