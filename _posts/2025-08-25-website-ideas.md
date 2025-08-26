---
title: "Website Ideas"
excerpt_separator: "<!--more-->"
toc: true
categories:
  - blogs
tags: 
  - howto
---

Trying to figure out a tech stack and how to present the content for the site.

<!--more-->

# User Stories

I need to present several user journeys through this site. 

1) First is the front-first visitor that finds the site by typing the domain into their browser. I need them to find something of interest and hopefully find their time well-spent. This is not a commercial site, so I'm not going to spend a lot of effort reading visitor logs, although I will activate Google Analytics, mostly to make sure people are finding what they need.

2) Next is someone coming in from a web search. Over time, I hope that people looking for their ancestors in Google Search will find the site. This person likely wants a specific family name and to find out what became of a relative. In reading the early editions, it seems that a lot of people died of things we can now easily prevent. A ruptured appendix or tonsilitis was a life-threatening illness in 1904. One man, thrown in the town's jail for an evening, was found dead the next morning with a bottle of laudanum (liquid codeine) by his side. Those peoples' names aren't reflected in the current town's populace, but they mattered to someone, somewhere.

3) Someone looking for a specific date. Historical dates such as statehood and the declaration of war. Those should be found with just a few clicks.

If someone is looking for information on a site, the best experience is to have information that has a close affinity to what is being read immediately available without a search or going to the front page and navigating. This is a fuzzy issue and will require some tweaking along the way. For the short term, I'm going to make sure that there are plenty of short-cuts to issues by year with drill-down links to specific issues.

# Technical Stack

As I mentioned earlier, once I'm done with the site, I don't want to spend my evenings and weekends making sure web scum aren't trying to attack the site. For that reason, I'm going to forego traditional CMSes like WordPress, Joomla, and Drupal. Like my personal sites, I want the attack surface to be as small as possible and the potential gain for the attackers to be zero. They might disable the site by flooding my host, but they won't add spurious files and malware.

The site should be capable of being installed on any server without regard to domain. All the links should be relative to the site itself. While a top-level domain exists for this site, someone could take my site and put it on their own server and it should continue to work.

## Jekyll 

I've chosen to work with [Jekyll](https://jekyllrb.com). This is arguably the most well-known of the static site generators (SSGs) and Github itself provides a lot of support for it. There are hundreds of themes and tools made to work with Jekyll. I can host the site locally, on Github.io, as well as in the cloud. There are many CI/CD scripts to support Jekyll build and deploy models. Depending on the budget for this project, I may deploy to Netlify or AWS. I have experience running Jekyll sites on AWS and I like the fact that I can easily control my costs there. Netlify has a great build and deploy model for Jekyll sites, but they have a bit of a bad reputation among hobbyists these days due to well-publicized problem that happened in 2024. Given that this site has a large quantity of static images, I'll have to be careful about CDN hosting and bandwidth costs.

The drawback (and benefit) of Jekyll and every other SSG is that everything about the site must be known in advance. There is a robust scripting language to build pages and link between them, but every new piece of content requires rebuilding the site. Given that the Hydro Review ceased publishing in the 1990's, this doesn't seem like that big of an impediment once it's all running.

The open issue, at least as of today, is search. The OCR is poor, at best, and the word list contains an excessive amount of garbage. I can use the [Lunr](https://www.stephanmiller.com/static-site-search/) search engine to build an index that will allow on-site navigation. Of course, there's always the major search engines.

## Jekyll Themes

There used to be a somewhat thriving market in Jekyll themes when I first started building sites with this tool in 2012. It would seem that at least one of these marketplaces has gone belly up. But, there plenty of others. My own personal site and another for a hobby I play with use a theme called [Minimal Mistakes](). 

Minimal Mistakes is the poster child for aftermarket Jekyll themes, due to its' popularity. Part of the reason is it's still actively maintained and it looks good on desktop and mobile devices. The drawback is that any customization requires writing code in a somewhat obscure dialect called Liquid.

I searched for themes that were meant for newspaper or literary archives. I found one, but it was on one of those defunct sites and the code had not been maintained. If I'm going to start this project, I hope to have a theme that is maintained to deal with future technical hurdles. Who knows when we will have in-eye monitors, but it may be in my lifetime. I hope not, but one never knows.

I'm not 100% convinced that I will stick with Minimal Mistakes, but for now, I'm going to begin with it. If I change, I'll need to modify the structure of the site, but that shouldn't involve too much technical debt. I hope.

## Images

I converted all the PDF pages to images because 