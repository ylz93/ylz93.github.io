---
layout: page
title: Predoctoral projects
description: Serious games designed and developed at MSU
img: assets/img/project/predoc_cover.jpg
importance: 2
category: work
---

Before going to UW–Madison for my doctorate, I earned my master's degree in Media and Information at Michigan State and was interested in serious game design and development. In my culture, games are often regarded as something addictive and harmful to children. Nonetheless, I believe game's potential of attracting kids and maintaining their attention can be leveraged to create great learning experiences. Here are two example serious games I have worked on.

Tech Trek is a 4-player card game designed to make available to middle school students information about technology related careers. This game is suitable for classrooms, is easy to put together and to play, and is a free engaging activity designed specifically for learning. The goal of this game is to excite middle school students (especially girls) about pursuing technology related careers, so that they carry this excitement throughout their education and hopefully pursue STEM careers in the future. I participated in the design and crafting of this game and a field test at a local middle school.

More information can be found at <https://playtechtrek.wordpress.com>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project/predoc/tech trek.png" title="Tech Trek" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Tech Trek's gameplay
</div>


Picky Birds




<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>


You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
