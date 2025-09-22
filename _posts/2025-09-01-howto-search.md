---
title: "How To: Search this site"
excerpt_separator: "<!--more-->"
toc: true
categories:
  - blogs
tags: 
  - howto
---

You've landed on this site. How can you find what you're looking for?

<!--more-->

We know searching for information will be an important feature for users. People want to find out how their great-grandparents fared in this new state.

There are limitations to using many search engines because of the *static* nature of this site and its contents. Unlike interactive sites elsewhere on the web, there is no 'database' or 'back-end' software running this site. This allows us to host the site as cheaply and securely as possible without worrying if people are hacking our site.

## Technical Details

If you're not interested in the technical details, scroll on down...

For some technical background, the data for this site was a series of scanned images, one per page of the old newspaper. The publishing process in 1904 was very different than it is today. These newspapers weren't always stored very well, so they have tattered edges or an excess of ink on the pages. We ran Optical Character Recognition (OCR) software on each page to try to get an understanding of the words on each page, but this software didn't always understand the layout of the pages. So, we can find the list of words on the page, but not always the order in which they would make sense to a human. We lack the ability (and budget) to review each page individually, but we want to make this data publicly available because it is useful, even if the search requires a little more effort than you'd expect from a site like Google or Ancestry.com.

We were able to create a list for each page that shows the words the OCR software thought was on the page, and in the order it encountered them. This may or may not be the order of the sentence on the page that was originally written. Also, those ink spots and torn pages affect the way the OCR software performed. So, a name like William Smith might get read as Williom Smth or Willlam Smitb. As part of the data validation process, we ran the words found for each page against a list of around 80,000 surnames from the US Census along with the most prevalent given names. Those are added to the search results for the pages in which they were found. We also included place names from Oklahoma and local names for places, like "Exendine" or "Reber's Corner". On top of those, we filter out any words that aren't in the 100,000 or so of the most common English words. This keeps the search database clean of OCR defects, but it does mean that some names will be more difficult to find if they didn't get recognized correctly.

## The Shift of Language in 125 Years

The filtering of the OCR results brings up the matter of words in the search results. There are words that were commonly used in pre-Statehoood days to describe people of different races and cultures. Some of those words are no longer used and some are now considered insensitive or even offensive. There were such words on the pages of this newspaper and we've made no efforts to remove them from the scanned pages. However, there is a list of such words that are removed from the search index as it is generated. 

We won't guarantee that you won't encounter an offensive word in these pages, but we have made the effort to remove the ones we could see. If there are others, please use the contact link and we'll update the search results to remove them.

## How To Search

Most likely, you'll want to search for someone by name. It's best to start with the last name and see how many search results appear and then add the first name or variations of both. The site is configured to return up to 100 matches. The Algolia search engine tries to use "relevance" to determine close matches to what you're looking for. So, if I were to search for William Smith, I might find Willem Schmidt or Willie Smythe. If the last name isn't enough to narrow down the results, provide other information that you know about the person you're looking for, such as the state or city that they lived in previously or any other relatives that might've been with them.

Once you find an issue that might have the information you want, click on it to show thumbnails of the pages. The "full issue" link, as shown below, will open an Adobe PDF file in a new browser tab.

___

![masthead example](/assets/images/2025-09-01/fullissue.png)

___

Within the PDF tab, search for a specific word by pressing **CTRL-F**. This will give better results than the site search. It's best to zoom to 75% or greater to be able to see the highlighted search term. Or, you can save the PDF to your own computer and use Adobe Acrobat Reader or similar software to view and print the pages at home.

<iframe width="640" height="360" src="https://www.youtube-nocookie.com/embed/qP4pABbWtfA?controls=0" frameborder="0" allowfullscreen></iframe>

Happy searching. We hope you enjoy reading about Hydro through the years. If you have suggestions, please reach out to us using the [contact page](/contact) or on [FaceBook](https://www.facebook.com/groups/1016477133673656).
