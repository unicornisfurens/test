---
ID: 16
post_title: Milestones
author: nick
post_date: 2016-02-03 16:50:57
post_excerpt: ""
layout: page
permalink: >
  http://devcenter.tenforce.com/milestones/
published: true
---
<div class="horizontal-tab tab-1">
<div id="milestones-nav">[loop type=Milestones clean=true orderby=date]
<a class="milestone" href="[field url]">
<span class="number">[wck-field meta="meta-for-milestones" name="milestone-nr"]</span>
[field title]
</a>
[/loop]</div>
</div>
<div class="horizontal-tab tab-2">
<div id="sprints-nav">[loop type=Sprints clean=true]
<a class="sprint" href="[field url]">
[field title]
<span class="start-end">
[field "start_date" date_format="d/m/y"]-[field "end_date" date_format="d/m/y"]</span>
</a>
[/loop]</div>
</div>
<div class="horizontal-tab tab-3">
<div id="stories-nav">[loop type=Stories clean=true orderby=title]
<a class="story" href="[field url]">
<span class="type">[taxonomy type]</span>
[field title]
<span class="category">[taxonomy category]</span>
</a>
[/loop]</div>
</div>