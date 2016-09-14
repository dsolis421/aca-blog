---
layout: post
title: Bootstrappin
date: 2016-09-14 08:07:00 -0600
categories: learning
---

# Bootstrappin

It's been a while since I last blogged, which means I've been busy.  The good news is that I've been busy learning and coding.  Up to this point, the focus has been raw HTML and CSS.  It's been fun and challenging at the same time.  Here's the best part.  Up until this point, my attempts at coding have been - shall we say - less than graceful.  Picture a guy jumping into a pool with no real understanding of how to swim.  I would jump into the pool, splash around and call it swimming.  Now, I feel like I can jump into the pool, tread water and make a respectable effort to move about.  Analogies aside, I can sit down at my laptop and just start coding.  In minutes, I can have a working web page.  In an hour, I can have a styled web page with functional and responsive elements. I can take an idea and create it from scratch, with code.  That's a good feeling.  Do I know everything? Not by a long shot.  I'm OK with this because I know there's some really cool shit still to learn.

## Progress

In my previous blog posts, I went a bit off the rails trying to express some of my frustrations with HTML, doc flow and elements- namely divs.  I felt like I made some great strides in understanding HTML doc flow and writing code that effectively places and formats elements on the page, using CSS.  Most importantly, I believe that I now *understand* the concepts behind HTML and CSS, such that I can write *efficient* code that produces the exact look and feel desired.  I'm referring to concepts like doc flow, the box model, semantics,  precedence (inheritance, specificity), responsive design (media query).  The result is a true proficiency using the building blocks of a web page.  It's the difference between true *coding* and simply typing text that does...something.  It's having complete command and control over how a web page looks and functions.  So where do I go from here?  Now that I can crawl and walk, can I jog?

## Enter Bootstrap

Even with a good understanding of HTML and CSS, building a web page is still tedious.  Building a responsive web page is even more so.  Accounting for all the many types of devices that can display web content is a chore.  If you want a website that truly stands out and reaches the broadest audience possible, there's no such thing as "one size fits all".  But, there are options.  You can certainly code HTML and CSS to produce a responsive web page, using all the many properties and attributes required to recognize the device and style accordingly.  If you're a hammer and nails kind of person, this might be your approach to building a house.  But, what if you could use a nailgun and what if you had prefabricated pieces of your house ready to use as you see fit.  In software development, it's referred to as a framework - a predefined set of classes that, when called upon, can provide prepackaged code for use in development.  One of the more prominent frameworks for web development is [Bootstrap](https://www.getbootstrap.com).

With Bootstrap, you can apply a set of properties to an element simply by assigning that element to one of the many classes included in the Boostrap framework.  For example, `class="container"` can be used on a `<div>` HTML element to provide a predefined set of properites for margin, padding, size etc. that can then be used to house additional elements within.  What's more, Bootstrap will make the element responsive and adjust these properties for various devices.  All this simply by assigning a class to an element, eliminating the need to code these properties into your CSS.  To say this framework is robust is an understatement.  The list of classes for various purposes, with all the many variations, is huge.  The [examples](http://getbootstrap.com/getting-started/#examples) page at the Bootstrap site is a great place to start.  The bottom line is that Bootstrap provides the heavy lifting code for layout (with an emphasis on mobile), so that you can focus on the code for content and design specific to your project.

## Bootstrap Examples

The internet is full of sites that utilize Bootstrap:
* www.marketwatch.com
* www.esquire.com
* www.spotify-thedrop.com/#/
* www.anakin.co/en
* www.nasa.gov

Just to name a few.  Be sure to resize these pages to various screen widths to see the full effect that Bootstrap can have on a page.

## Next-Gear Dev

Bootstrap allows you to shift your web development into a higher gear.  But, let's be honest.  Bootstrap doesn't mean much to someone who doesn't understand the underlying concepts of HTML and CSS.  The intent of a framework is to supply the most common snippets of code necessary build a much grander design.  The final product ultimately relies on your ability to apply the boilerplate code *to your own code*, in order to meet your requirements.  Bootstrap is a tool, not a crutch.
