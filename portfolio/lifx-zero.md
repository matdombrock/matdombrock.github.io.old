---
layout: default
---

<img src="{{ "/assets/img/port/lifx.png" | prepend: site.baseurl }}" class="port-ss">
<a class="button-full repo-btn" href="https://github.com/matdombrock/lifx-zero" target="_blank">- GitHub Repository -</a>
<a class="button-full demo-btn" href="https://www.npmjs.com/package/@mdombrock/lifx-zero" target="_blank">- NPM Package -</a>
<h2 class="post-title">Lifx Zero</h2>
<hr>
An NodeJS API wrapper for <a href="https://www.lifx.com/"  target="_blank">Lifx Brand Smart Light Bulbs</a>.

**The main goals & reasons behind building this were**
* I think it's really cool that Lifx offers an open API.
* RGB LED's are awesome. 
* The official control applications are not available for Linux.
* I plan to build a hardware controller for the bulbs and this would be required to do that.
* I wanted to practice wrapping APIs with NodeJS.

## Major Features
* Nearly 100% API coverage at the time or writing. 
* Supports authorization.
* Minimal dependencies.
* Fully Documented.

## Major Technologies Used
* NodeJS
* <a href="https://api.developer.lifx.com/" target="_blank">LIFX API</a>