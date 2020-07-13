---
layout: page
title: Jekyll Theme - About - Massively
description: When building a website it's helpful to see what the focus of your site is. This page is an example of how to show a website's focus.
sitemap:
    priority: 0.7
    lastmod: 2017-11-02
    changefreq: weekly
---
## Qualitative Analysis

<span class="image left"><img src="{{ "/images/timeline_swimmer.jpg" | absolute_url }}" alt="" /></span>
The plot illustrates the decisions of the master policy in task Swimmer-v3, where the interleavedly plotted white and yellow dots along the timeline correspond to the small and large sub-policies, respectively. In this task, the reward is determined according to the speed of the swimmer at each timestep. In order to accelerate itself, the swimmer has to perform strokes, which cause the curve to drop down first and then move up. Each stroke enables the swimmer to boost its speed to a sufficient value, which is then gradually decelerated to zero by the water. In order to slow down the deceleration speed, our swimmer maintains a proper posture until its next stroke. In the experiment, our model learns to use the large sub-policy while performing strokes. This is due to the fact that performing strokes involves fast changes in the movements of the joints, thus requiring more complicated control. On the other hand, the swimmer uses the small sub-policy to maintain its posture between two strokes for most of the time, since it only requires slight adjustments of its joints.

### Video demos

<video width="480" height="360" controls>
  <source type="video/mp4" src="{{ "/videos/swimmer_short.mp4" | absolute_url }}">
  Your browser does not support the video tag.
</video>
<video width="480" height="360" controls>
  <source type="video/mp4" src="{{ "/videos/walker-stand.mp4" | absolute_url }}">
  Your browser does not support the video tag.
</video>
<video width="480" height="360" controls>
  <source type="video/mp4" src="{{ "/videos/ant.mp4" | absolute_url }}">
  Your browser does not support the video tag.
</video>
