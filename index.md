# A Portable Interface for Laser Engravers #

Our goal is to develop a portable, compilable tool to connect with HTPOW laser engravers. We'll update this landing page as we find new information to share with you. Read our weekly updates below, or check out the blog <!--- TODO --> for more information on what we discover.

## Project Requirements ##

Our project requirements (in order by precedent):

* Reverse engineer protocol for HTPOW engraver
* Reverse engineer image transefer protocol
* Implement driver in portable software language (C/C++)
* Implement Command Line Interface (CLI) for driver

Additional goals (if time allows):

* Reverse engineer settings/speed protocol
* Reverse engineer images storage protocol
* Pre-process raster image to minimize cutting time

## Project Schedule ## <!-- TODO -->

The important completion dates. Some of these will be assigned by the instructor (requirements due, midterm presentation, final presentation) 

## Project Log ## <!-- TODO -->

A log of project activity. All meetings (customer and team) are listed. Changes to project, agreements with customer are listed (do not have to be explained in detail, "bullet points" of changes).

## Other materials ##

<!-- TODO -->

## Recent Posts by Grant Sparks ##
<ul class="posts">
{% for post in site.tags.sparks limit: 10 %}
  <div class="post_info">
    <li>
         <a href="{{ post.url }}">{{ post.title }}</a>
         <span>({{ post.date | date:"%Y-%m-%d" }})</span>
    </li>
    </div>
  {% endfor %}
</ul>

## Recent Posts by Lucian Hymer ##
<ul class="posts">
{% for post in site.tags.hymer limit: 10 %}
  <div class="post_info">
    <li>
         <a href="{{ post.url }}">{{ post.title }}</a>
         <span>({{ post.date | date:"%Y-%m-%d" }})</span>
    </li>
    </div>
  {% endfor %}
</ul>

## Recent Posts by Patrick Thompson ##
<ul class="posts">
{% for post in site.tags.thompson limit: 10 %}
  <div class="post_info">
    <li>
         <a href="{{ post.url }}">{{ post.title }}</a>
         <span>({{ post.date | date:"%Y-%m-%d" }})</span>
    </li>
    </div>
  {% endfor %}
</ul>