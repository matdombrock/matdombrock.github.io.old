---
layout: default
---
<div class="home">
    <h1 class="page-title">Pundulums</h1>
    <video width="100%" height="auto" muted autoplay loop controls>
            <source src="{{ "/assets/vid/port/pun.mp4" | prepend: site.baseurl }}" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</div>
Pundulums was possibly one of the most fun projects I've even been paid to work on. 

The client for this project has a love for puns and wanted a way to share them with the world. 

One of the main challenges for designing a web app that delivers puns, is that each **TIMING** is a very important aspect of pun delivery. The amount of pause between the the setup and the punchline is critical to the pun's success. In order to account for this, I came up with a formula that determines how long on average a pun should take someone to read, and when the punchline should be delivered for maximum hilarity. 

**The main goals when building this web app were:**
* Deliver text-based puns in an effective and novel way.
* Have a simple and easy to use way of adding new puns to the list.
* Allow users to share the puns on social media without ruining the punchline (the shared post contains the setup and a link to see the punchline on the web app).
* Allow users to post comments in the app.

# Major Features
* "Smart" pun delivery system.
* Users can continue reading from where they left off when coming back to the app.
* Simple text based pun "database".
* Custom Twitter and Facebook integration allows users to share puns without ruining the punchline and drives interaction with the site. 
* Deep Google Analytics Integration. 
* The site is static so it does not require a formal database and is very fast. 

# Major Technologies Used
* Facebook API
* Twitter API
