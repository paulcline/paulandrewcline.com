---
layout: post
title:  "The United States of Burgers"
date:   2015-05-26 23:08:18
categories: "serious eats"
---

<div class="preview"><img src="/images/united-states-of-burgers.png" /></div>

I handled the tech side of the <a href="http://www.seriouseats.com/maps/united-states-of-burgers">United States of Burgers</a> -- one of <a href="http://www.seriouseats.com">Serious Eats</a> first forays into interactive editorial content.  On the client, we're using <a href="http://raphaeljs.com/">raphael.js</a> to draw the map and handle the interactions.

The backend presented a different set of challenges: associating a burger with a state isn't something <a href="https://movabletype.org/">MovableType</a> excels at, as a result the editorial team was using Google Spreadsheets to compile their list.  Without negatively impacting their workflow, we were able to use the <a href="https://developers.google.com/google-apps/spreadsheets/">Google Spreadsheets API</a> to export the data to JSON and assemble the page.

<ul>
  <li>javascript</li>
  <li><a href="http://jquery.com/">jquery</a></li>
  <li><a href="https://www.python.org/">python</a></li>
  <li><a href="http://raphaeljs.com/">raphael.js</a></li>
</ul>