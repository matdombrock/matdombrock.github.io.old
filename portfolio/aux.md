---
layout: default
---

<img src="{{ "/assets/img/port/dmark.png" | prepend: site.baseurl }}" class="port-ss">
<a class="button-full repo-btn" href="https://github.com/matdombrock/dMark" target="_blank">- GitHub Repository -</a>
<a class="button-full demo-btn"  href="http://mzero.space/dMark/" target="_blank">- Interactive Demo -</a>
<h2 class="post-title">AUX</h2>
<hr>
A self-hosted bookmark manager designed for developers and built for GitHub pages.

*Requires no server side access, this is 100% front-end JavaScript.*

**The main goals & reasons behind building this were**
* Browsers have terrible bookmark managers.
* Many 3rd party solutions require you keep your data on their servers.
* I don't like giving my data away.
* Many open source solutions are cumbersome.
* I wanted to practice prototyping with Vue.js.

## Major Features
* 100% front-end HTML & JavaScript. 
* Can easily be hosted on GitHub Pages.
* Simple JSON file-based "database".
* Supports the use of "tags" to organize your bookmarks. 
* Search box with filters for "Tag", "Name" and "Description".

## Major Technologies Used
* Vue.js
* jQuery
* Bootstrap