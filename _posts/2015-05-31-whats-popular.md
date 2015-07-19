---
layout: post
title:  "What's Popular on Serious Eats"
date:   2015-05-25 23:08:18
categories: ["serious eats"]
---

<div class="preview"><img src="/images/popular-widget.png" /></div>

<a href="//seriouseats.com">Serious Eats</a> uses the <a href="//chartbeat.com">Chartbeat API</a> to track popular content across the site, but required a custom solution to inject some editorial control in to the process.  Data is aggregated from Chartbeat, filtered and scrubbed to enforce date restrictions and editorial rules, and then written out to JSON.  Editors can override the display image using a single-page admin interface.



<ul>
  <li><a href="//chartbeat.com">Chartbeat API</a></li>
  <li>javascript</li>
  <li><a href="//jquery.com/">jquery</a></li>
  <li><a href="//www.python.org/">python</a></li>
  <li><a href="//www.sqlite.org/">SQLite</a></li>
</ul>