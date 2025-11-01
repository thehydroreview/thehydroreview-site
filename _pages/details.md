---
title: Technical Details
permalink: /details/
toc: true
---

## Technical Details

Most of the tools used to create this site are open-source with permissive licenses, although several are commercial products with free-to-use clauses for individuals and non-profits. 

### Open Source

* This site is powered by [Jekyll](https://jekyllrb.com/).
* The site design is based on [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes), by [Michael Rose](https://mademistakes.com/).
* PDF operations were performed using [Poppler](https://poppler.freedesktop.org/) and [GhostScript](https://ghostscript.com/).
* Optical Character Recognition was performed using [Tesseract](https://tesseract-ocr.github.io/).
* Image processing was performed using [ImageMagick](https://imagemagick.org/).
* Search word dictionaries are based on [SCOWL](http://wordlist.aspell.net/) that are built into the aspell tool.
* EXIF metadata for the images was inserted using [exiftool](https://exiftool.org/) by Phil Harvey.

### Free-to-use

* Icons on this site are provided by [Font Awesome](https://fontawesome.com/).
* Development and editing was done primarily in [VSCode](https://github.com/microsoft/vscode).
* Source code is stored in public [Github repos](https://github.com/thehydroreview) and deployed to production using modern CI/CD methods.
* Various pieces of vector art on the site from [Vecteezy](https://www.vecteezy.com)
  * Water tower by [Abdurrohim Arifuddin](https://www.vecteezy.com/members/113855795731930470492)
  * Newspaper in OG image by [Diana Johanna Velasquez](https://www.vecteezy.com/members/djvstock)

### Commercial

* Hosting is provided by AWS using S3 and CloudFront. As this is a paid service, we've worked to contain costs of hosting by reducing the quality of the JPEG images on the site. If you are interested in the full-size and high-quality images of this newspaper, please use the [contact form](/contact/).

### Other Software

* The conversion process was done using custom-built Python scripts. These are not stored in a public repo at this time.
* Image editing was primarily done with Adobe Photoshop CS3.

## Credits

* Word lists for the given and surnames were based on work done by Rhett Butler and published on their site at [probablyhelpful.com/](https://probablyhelpful.com). All data is derived from David L. Word, Charles D. Coleman, Robert Nunziata and Robert Kominski (2008). *Demographic Aspects of Surnames from Census 2000*. U.S. Census Bureau.
* Much of the work on this site was based on the discoveries of others. There are countless numbers of [StackOverflow](https://stackoverflow.com) and [Jekyll Talk](https://talk.jekyllrb.com) articles that we read to get everything organized. It's impossible to thank everyone whose body of knowledge was used to build this site, but their contributions are appreciated.