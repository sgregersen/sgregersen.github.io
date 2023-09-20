---
layout: page
title: A grammar of Wangerooge Frisian
description: Postdoc project on an extinct Frisian language of northern Germany
img: assets/img/project_wf.jpeg
importance: 1
related_publications: gregersen2023sketch
---


Wangerooge Frisian is a now extinct Frisian language once spoken on Wangerooge, a small island in the German Wadden Sea. This language was extensively documented before it went extinct in the first half of the 20th century, but has so far received little attention in the linguistic literature. My current project is a grammatical description of the Wangerooge Frisian language as it was preserved in documentation from the 19th and early 20th century. The project is supported by the Carlsberg Foundation and hosted by the department of Frisian studies at Kiel University.

In addition to the grammatical description of Wangerooge Frisian, the project




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



<br>
<h2>Related presentations</h2>
<table>
<colgroup>
<col width="50%" />
<col width="30%" />
<col width="10%" />
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
<td markdown="span">From complementizer to causal subordinator: The functions of _dat_ ‘that, so, because’ in Wangerooge Frisian. Societas Linguistica Europaea (SLE 2023)
</td>
<td markdown="span">[SLE 56](https://societaslinguistica.eu/sle2023/), University of Athens</td>
<td markdown="span">29/08/23</td>
<td markdown="span">[slides](/assets/pdf/pres/SLE56_dat.pdf)</td>
</tr>
<tr>
<td markdown="span">Om (øst)frisisk i 1800-tallet [On (East) Frisian in the 19th century]</td>
<td markdown="span">_Grammatik i 1800-tallet_, Danish Language Council</td>
<td markdown="span">14/08/23</td>
<td markdown="span">[slides](/assets/pdf/pres/DSN_WF.pdf)</td>
</tr>
<tr>
<td markdown="span">A “lost” language of Northern Germany: An introduction to Wangerooge Frisian</td>
<td markdown="span">_Sprachwissenschaftliches Kolloquium_, Kiel University</td>
<td markdown="span">20/06/23</td>
<td markdown="span">[slides](/assets/pdf/pres/SprKoll_WF.pdf)</td>
</tr>
<tr>
<td markdown="span">A “lost” language of Northern Germany: A crash course in Wangerooge Frisian</td>
<td markdown="span">StuTS 73, University of Frankfurt</td>
<td markdown="span">28/05/23</td>
<td markdown="span">[slides](/assets/pdf/pres/StuTS73_crash_course.pdf)<br>[handout](/assets/pdf/pres/StuTS73_exercises.pdf)</td>
</tr>
<tr>
<td markdown="span">Reconstructing the definite determiner system of Wangerooge Frisian</td>
<td markdown="span">_Methodological Challenges in Historical Sociolinguistics_, University of Amsterdam</td>
<td markdown="span">23/05/23</td>
<td markdown="span">[slides](/assets/pdf/pres/HiSoc_definiteness.pdf)</td>
</tr>
<tr>
<td markdown="span">An invitation to Wangerooge Frisian</td>
<td markdown="span">Lexical Restrictions research group, University of Amsterdam</td>
<td markdown="span">21/04/23</td>
<td markdown="span">[slides](/assets/pdf/pres/LexRestr_WF.pdf)</td>
</tr>
<tr>
<td markdown="span">Sociolinguistic perspectives on Wangerooge Frisian</td>
<td markdown="span">Historical Sociolinguistics research group, University of Amsterdam</td>
<td markdown="span">30/03/23</td>
<td markdown="span">[slides](/assets/pdf/pres/HiSoc_perspectives.pdf)</td>
</tr>
<tr>
<td markdown="span">The word order of complement clauses in Wangerooge Frisian</td>
<td markdown="span">StuTS 72, University of Hamburg</td>
<td markdown="span">04/11/22</td>
<td markdown="span">[slides](/assets/pdf/pres/StuTS72_dat.pdf)</td>
</tr>
<tr>
<td markdown="span">Komplementsætninger i wangeroogefrisisk [Complement clauses in Wangerooge Frisian]</td>
<td markdown="span">_Grammatiknetværket_, Odense</td>
<td markdown="span">27/10/22</td>
<td markdown="span">[slides](/assets/pdf/pres/NFG_dat.pdf)</td>
</tr>
<tr>
<td markdown="span">‘Inside (house)’ vs. ‘inside (non-house)’: A semantic shift in Wangerooge Frisian</td>
<td markdown="span">_Semantic Shifts_, Fréjus</td>
<td markdown="span">19/09/22</td>
<td markdown="span">[slides](/assets/pdf/pres/SemanticShifts_non-house.pdf)</td>
</tr>
</tbody>
</table>
<br>

