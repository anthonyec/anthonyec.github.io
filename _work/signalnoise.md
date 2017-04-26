---
layout: article
color: B3FFEE
title: Signal Noise Website
client: Signal Noise
snippet: Craft CMS based website with a focus on making life easier for content creators.
overview: Commutor tool was created in 2015 for Total Jobs. It uses the information about the users daily commute to calculate a few interesting stats displayed with illustrations.
tags:
    - craft cms
    - php
    - backbone
    - vagrant
    - bem css
    - susy
subjects: 
    - backbone
    - svg

cta_label: Try the tool
cta_href: https://www.totaljobs.com/insidejob/commuter-calculator/
---
From the design I created repeatable image assets to add some looping animation to the start screen.

<video 
    autoplay 
    loop 
    src="videos/start_animation.mp4" 
    poster="images/start_animation_poster.jpg">
</video>

<video 
    autoplay 
    loop 
    src="videos/form.mp4" 
    poster="images/form_poster.jpg">
</video>

The stats are displayed in a carousel. Each slide dynamically changes it's illustrations depending on the numbers generated. The data is stored in a Backbone `model` and specific methods can return calculated numbers ready to be used in the template.

<video 
    autoplay 
    loop 
    src="videos/slides.mp4" 
    poster="images/slides_poster.jpg">
</video>

When you reach the end of the carousel you are given the option to find out more or share your results. Clicking share will generate a custom share message for you to post.

<video 
    autoplay 
    loop 
src="videos/end.mp4" 
    poster="images/end_poster.jpg">    
</video>