---
title: My Portfolio
---

## My Non-Professional Experience

My [formal résumé](/résumé) gathers details about my degree and paid work experience.
Since it is hard to evaluate my schoolwork and jobwork, publicly available projects are gathered here for your perusal.

[My Github](https://github.com/AVerm/) has several public repositories, but this page gives a better guided tour of my breadth (overrepresenting projects that are easy to put online).

## Website Work

I enjoy hacking on my personal website.
I consider the crown jewel of the website to be 
[the implementation I wrote of an RSS feed that is a valid HTML document with a stylesheet](http://www.ajvermillion.com/feed.xml).
I wrote this project largely directly off of RSS, XML, XHTML, and XSLT specifications, though I took advantage of MDN articles as well.

That feed may not be very good looking, but [my wedding website](https://1inavere6.com/) is much nicer.
It was originally mocked up by my wife in LibreOffice Impress (Open Source Powerpoint), and I worked to implement all the features she wanted.

In order to implement everything she asked for, I learned about Jekyll, Github Pages, and several weird CSS hacks.

Like this website, I left [the Github-hosted repository](https://github.com/AVerm/1inavere6) public.
My favorite effect, even though it is not very remarkable, is the inverted transparency on the menu buttons (reused on this website to lesser effect).

## Shadertoy Uploads

I enjoy using GLSL
<details>
	<summary>&lsquo;fragment shaders&rsquo;</summary>
	the 2-dimensional massively-parallel component of the rendering pipeline
</details>
to make demos.
I present a few of them here to demonstrate my self-motivated learning capabilities.

[My Shadertoy profile](https://www.shadertoy.com/user/tomcatfish) has more examples than the below.

<iframe width="640" height="360" frameborder="0" src="https://www.shadertoy.com/embed/tfGXWR?gui=true&t=10&paused=false&muted=true" allowfullscreen></iframe>

A simple ray marcher I built while intrigued by ray marching and coordinate repetition.

<iframe width="640" height="360" frameborder="0" src="https://www.shadertoy.com/embed/XfdSDX?gui=true&t=10&paused=false&muted=true" allowfullscreen></iframe>

A demonstration of distance metrics. Each dot emits an area over time, enclosing all space that it is nearer to than all other dots.

At [the link to the fragment shader](https://www.shadertoy.com/view/XfdSDX), you can edit the
`distance_` function to switch between the default
<details>
	<summary>Euclidean distance</summary>
	real world distance, where a diagonal meter is 1 meter long
</details>
 and 
<details>
	<summary>Manhattan &ldquo;taxi-cab&rdquo; distance</summary>
	the typical digital pathfinding distance, where a meter at a 45° angle is 2 meters long, one horizontal meter and one vertical meter
</details>.
You can also click to place a dot of your own.

## Psyche Driller

This was my Computer Science B.Sc. capstone, and so is covered in my résumé, but I wanted to add a link here for completeness.

We were split into groups and had to learn how to use Godot while making our game and taking critiques from the NASA rep (who nixed multiple names for our game in a row), all while balancing full courseloads.

You can [play the game](https://capstone2021.missiontopsyche.org/psyche-driller/) online and used to be able to look through [the official repository](https://github.com/MissionToPsyche-Nickel/2021_15E_Web-Based-Game), but it has been privated.
I have a fork available if you are interested (but Github doesn't allow me to make it public).

## Userstyles

I have strong opinions on design, and like to make webpages look how I want them to.
I have written several user CSS restylings for live webpages.

Here is a website that a friend wrote a short story on (a tutorial included in an unrelated story is pictured for privacy reasons) with its default style:

![Default style](/assets/images/ProjectLawful_Before.png)

Here's my favored style, which I won a few converts to when I shared it on the platform's forums:

![My style](/assets/images/ProjectLawful_After.png)

And here's my style-sheet only recreation of someone's website
(the author of the website was thrilled by my effort) which parses stories and writes new HTML for them:

![My copycat style](/assets/images/ProjectLawful_Akrolsmir.png)
