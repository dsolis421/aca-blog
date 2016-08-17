---
layout: post
title: Divs Behaving Badly
date: 2016-08-17 12:15:00 -0600
categories: learning
---

#Divs Behaving Badly

Ok Divs, listen up!  I need you to line up in a nice, neat horizontal row.  I know you're used to being stacked, but that's not how we're going to roll this time.  I know you're different colors - red, blue and green, but you're all the same width and the same height, so it should be really simple to line yourselves up.  Ready? Ok:

`.behave {
  height: 100px;
  width: 100px;
}`

`#red {
  background-color: red;
  float: left;
}`

`#blue {
  background-color: blue;
  float: left;
}`

`#green {
  background-color: red;
}`

Green, where did you go???  You're behind Red?  What are you doing there?  I wanted you lined up after blue.  Oh, sorry:

`#green {
  background-color: red;`
  *float: left;*
`}`

Lookin good!  That's exactly what I wanted...



Ok, you know what?  I'm going to switch it up.  You're going to line up to the right, instead.  Now, line up!

`#red {
  background-color: red;
  float: right;
}`

`#blue {
  background-color: blue;
  float: right;
}`

`#green {
  background-color: green;
  float: right;
}`

Nice!! Wait, why are you in a different order now.  You should still be showing as - Red, Blue, Green - in that order.  What?  The doc flow? What does that even mean? Here's the flow in HTML.  It hasn't changed. Why aren't you following this?

`<div class="behave" id="red">Red</div>`

`<div class="behave" id="blue">Blue</div>`

`<div class="behave" id="green">Green</div>`

So let me get this straight, the doc flow now *starts* at the right?  That means I have to switch up the order in HTML.  Fine, whatever...

`<div class="behave" id="green">Green</div>`

`<div class="behave" id="blue">Blue</div>`

`<div class="behave" id="red">Red</div>`

Alright.  Now we're talking.  That looks good.  I'd like to bring in one more div, if you don't mind.  I have a yellow div that's much larger than the rest of you, so I'd like to place him below your row.  Yellow div doesn't need to be to the left or right.  Here he is:

`#yellow {
  background-color: yellow;
  width: 500px;
  height: 100px;
}`

*sigh*  Yellow?  Want to tell me why you're behind red, green and blue?  You do not have a float property like they do, so you're supposed to be a stacked element.  Make sense? No? Ok, then what's the problem?  You need a clear property.  If I give you this clear property you so desperately want, do you promise to get back into the doc flow that's in HTML?  I guess I don't have a choice:

`#yellow {`
  *clear: both;*
  `background-color: yellow;
  width: 500px;
  height: 100px;
}`

This would be so much easier if you divs just did what I needed you to do the first time.  But no, you guys have to be uber literal about everything.  I guess I will just have to be specific with my CSS and be mindful of the doc flow in HTML.

Now, I'd like to have you all centered horizontally on the page.  But, we'll wait for flex to gets here...
