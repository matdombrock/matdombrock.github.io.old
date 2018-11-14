---
layout: default
---
<div class="home">
    <h1 class="page-title">Yell At A Republican</h1>
    <video width="100%" height="auto" muted autoplay loop controls>
            <source src="{{ "/assets/vid/port/yaar.mp4" | prepend: site.baseurl }}" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</div>

***NOTE: The political views put forward by this web app do not necessarily reflect my own.***

Yell at a Republican was conceptualized by political activists with the goal of driving political discussion. 

This web app allows visitors to find and send messages to Republican leaning households in their area without the identity of either the sender of the message or the recipient being revealed. 

By using the super powerful Mapbox API and some carefully created sorting algorithms (applied to available political data) I was able to bring the clients idea into reality and build something that other development firms said was next to impossible. 

By using a modfied version of WordPress with WooCommerce that I was able to integrate into the new web app, I was able to drastically reduce both the upfront and mantience costs of the software as well as the complexity of the back-end for the client. 

# Major Features
* Custom Implementation of Mapbox map rendering.
* Custom Implementation of Mapbox controls through the Javascript API.
* PHP API built to retrieve political data from the Database.
* Reverse and forward Geocoding allows the app to find the user's ZIP Code from their location, or find their location from their ZIP Code. 
* Covers the vast majority of ZIP Codes in Washington State. 
* Wordpress/WooCommerce back-end for easy usage by the client. 
* Integration of a fully custom web app to the WordPress/WooCommerce order system.
* Household nodes are "fuzzed" and randomized to prevent abuse.

# Major Technologies Used
* LAMP Stack
* Mapbox Maps API
* Mapbox Geocoding API
* WordPress
* WooCommerce
* Stripe API


