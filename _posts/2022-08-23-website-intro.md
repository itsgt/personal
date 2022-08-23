---
layout: post
title: Introduction to this website
description: A breif introduction to the pupose of this website, and what I'll be doing for the next five or so years of my life.
summary: A breif introduction to the pupose of this website, and what I'll be doing for the next five or so years of my life.
tags: [frontend, design]
---

As you may already be able to guess, this website is my academic portfolio website for my time at Georgia Tech. 
Classes start this week, and I thought I would lay out some of the design decisions and technical implementations of 
this website, as well as what to expect in the future. 

**What to Expect**

I know from previous content creation experience not to promise anything here. The challenge that I have when creating content for scientific purposes, is knowing when to stop going deeper on a subject long enough to write about it. In my previous experience, I would think to myself that I had a lot of time to make a really good video, and then I would work for months on the code itself, not the interested public in the loop. This is something I plan to work on with this website. 

**Design Decisions**

This website is designed to be very minimal. You can view what is essentially a digital version of my resume on the "About" page, a chronological list of blog posts such as the one you're reading in the "Writing" page, and you can search through the titles in the aptly named "Search", and that's about it. I chose a very minimal and MIT-licensed template for this, called [sidey](https://github.com/ronv/sidey). The icons on the "About" page are also MIT-licensed, and are from a project called [Ionic](https://github.com/ionic-team/ionicons). I would like to keep these icons as some of the only images on the site, and when/if I do include images, they will be due to this being the best way to present some information, and I will attempt to keep them as vector graphics. Adopting this philosophy should keep page load times down, as well as fit in with the overall minimalist aesthetic of the website. There's no cookies, trackers, ads, nothing to get in the way, and I'll work to keep it that way. I will also try to keep the colors to this nearly black and white scheme, for both minimalism and accessibility. At the very bottom of the page, you will see the date and the tags to find posts on similar subjects (which will become more relevant as more posts are added).

**Technical Implementation**

I want to go through the technical details of this project, mostly so that if another PhD student or anyone in a similar situation wants to create a website, they may have some idea of what this one looks like. This site is based on the Jekyll project linked above, and is created by compiling markdown code, which limits the functionality but makes for easier content generation in a way that fits the design philosophy above. This means that for the most part (a caveat mostly for initial setup or fancier features one may want), I'm not coding HTML directly, and I can just focus on writing. It is hosted on a [Github Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages) server, and I have purchased the domain name for five years from [Google Domains](domains.google). The domain name also represents the only financial cost of this project. I would say with technical experience, one should be able to set this up in an afternoon; if some learning is required, probably a weekend. You can find the full code of the website [at my Github](https://github.com/itsgt/personal). Note that my site is also MIT licensed, so feel free to build off of it. 

---

One last note: because I consider this to be a creative work, and I am funded through the [NSF Graduate Research Fellowship Program](https://www.nsfgrfp.org/), my posts will have this appended to the bottom of them. I would highly recommend checking out the program, as it enables me to do the work that I am doing.

> This material is based upon work supported by the National 
Science Foundation Graduate Research Fellowship under 
Grant No. DGE-2039655
>
> Any opinion, findings, and conclusions or recommendations 
expressed in this material are those of the authors(s) and 
do not necessarily reflect the views of the National 
Science Foundation.
