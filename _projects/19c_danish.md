---
layout: page
title: Danish in the 19th century
description: Ongoing work on grammatical change and variation in 19th-century Danish
img: assets/img/ancher.jpg
importance: 3
related_publications: gregersen2023passive, gregersen2021proksimativ
---

Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal its glory in the next row of images.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
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
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}



2020–2024

https://dsn.dk/sprogets-udvikling/grammatik-i-1800-tallet/ (in Danish)



<br>
<h2>Related talks</h2>
<table>
<colgroup>
<col width="50%" />
<col width="25%" />
<col width="15%" />
<col width="10%" />
</colgroup>
<thead>
<tr class="header">
<th>Title</th>
<th>Event</th>
<th>Date</th>
<th>Downloads</th>
</tr>
</thead>
<tbody>
<tr>
<td markdown="span">From possibility to preference: The history of Danish _gide_ ‘be able to, feel like’</td>
<td markdown="span">Expressions of modality in Germanic, HU Berlin</td>
<td markdown="span">15/09 2022</td>
<td markdown="span">[slides](/assets/pdf/pres/HU_gide.pdf)</td>
</tr>
<tr>
<td markdown="span">Om verbet _gide_ – fra middeldansk til 1800-tallet [On the verb _gide_ ‘feel like’ – from Middle Danish to the 19th century]</td>
<td markdown="span">Grammatik i 1800-tallet, Danish Language Council</td>
<td markdown="span">15/06 2022</td>
<td markdown="span">[slides](/assets/pdf/pres/DSN_gide.pdf)</td>
</tr>
<tr>
<td markdown="span">From possibility to preference: The history of Danish _gide_ ‘be able to, feel like’</td>
<td markdown="span">Postmodality and the life cycles of modal expressions, University of Caen</td>
<td markdown="span">02/06 2022</td>
<td markdown="span">[slides](/assets/pdf/pres/Caen_gide.pdf)</td>
</tr>
<tr>
<td markdown="span">_S_-passiv i 1800-tallet [The _s_-passive in 19th-century Danish]</td>
<td markdown="span">_Grammatik i 1800-tallet_, Danish Language Council</td>
<td markdown="span">10/01 2022</td>
<td markdown="span">[slides](/assets/pdf/pres/DSN_passiv.pdf)</td>
</tr>
<tr>
<td markdown="span">Lexical restrictions on the Danish passive</td>
<td markdown="span">Lexical Restrictions research group, University of Amsterdam</td>
<td markdown="span">22/10 2021</td>
<td markdown="span">[slides](/assets/pdf/pres/LexRestr_passive.pdf)</td>
</tr>
<tr>
<td markdown="span">Proksimativt _færdig_ (’lige ved’) i ømål og østdansk [Proximative _færdig_ (’about to’) in Insular and Eastern Danish]</td>
<td markdown="span">Workshop on Insular and Eastern Danish dialects, University of Copenhagen</td>
<td markdown="span">18/06 2021</td>
<td markdown="span">[handout](/assets/pdf/pres/KU_proksimativ.pdf)</td>
</tr>
</tbody>
</table>
<br>
