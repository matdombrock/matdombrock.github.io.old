---
layout: default
---

<img src="{{ "/assets/img/port/tuxearch.png" | prepend: site.baseurl }}" class="port-ss">
<a class="button-full repo-btn" href="https://github.com/matdombrock/Tuxearch2" target="_blank">- GitHub Repository -</a>
<a class="button-full demo-btn"  href="https://mzero.space/Tuxearch2" target="_blank">- Interactive Demo -</a>
<h2 class="post-title">Tuxearch 2</h2>
<hr><br>
A tool for quickly storing and recalling examples for command line utilities. This is a "simple" piece of software and took me about  2-3 hours to write. That being said, this is a re-write of <a href="https://github.com/matdombrock/Tuxearch" target="_blank">an older project</a> I wrote a few years ago. 

*Requires no server side access, this is 100% front-end JavaScript.*

**The main goals & reasons behind building this were**
* Command line utilities often have hard to remember, unintuitive names.
* I don't really like memorizing things. 
* <a href="https://www.git-tower.com/blog/command-line-cheat-sheet/" target="_blank">Traditional "cheat-sheets"</a> are not that useful to me. 
* I wanted to practice prototyping with Vue.js.

## Major Features
* 100% front-end HTML & JavaScript. 
* Can easily be hosted on GitHub Pages.
* Simple JSON file-based "database".
* Supports the use of "tags" to organize your commands. 
* "Smart Search" ranks your results according to what it thinks you want the most. 
* Fully Documented.

## Notable Technologies Used
* Vue.js