---
title: "Jekyll for Less-Technical Folk"
excerpt: "In this week's episode I help someone switch from Adobe Portfolio to GitHub Pages and Jekyll"
date: 2023-04-08
last_modified_at: 2026-01-11T18:55:20
header:
  overlay_image: /assets/images/clement-h-95YRwf6CNw8-unsplash.webp
  image_description: "Laptop with code editor on the screen"
categories:
  - "Websites"
tags:
  - "GitHub Pages"
  - "Kitty"
  - "Adobe Portfolio"
  - "Pulsar"
  - "OpenCore Legacy Patcher"

---

## Can It Be Done?

"Even trying it is mad!" you say? Well I guess it is good I didn't check with you first. I recently set about helping someone who is less-comfortable with tech than I am convert their portfolio site from [Adobe Portfolio](https://portfolio.adobe.com/) to [GitHub Pages](https://pages.github.com/) with a [Jekyll](https://jekyllrb.com/) template. It was their first time using `git` at all. Nearly their first time using a CLI to do anything (my terminal emulator of preference is [Kitty](https://sw.kovidgoyal.net/kitty/). I find it delightful). The whole process went surprisingly smoothly.

Here were the project requirements:
1. Something more customizable than Adobe Portfolio
2. No net new costs, money-wise

Enter GitHub Pages & Jekyll. GitHub Pages nicely ticked box number 2 and Jekyll filled requirement number 1. Also Jekyll because I use it enough to feel mostly comfortable with it and it integrates nicely with GitHub Pages.

One of the bumps along the way was the age of the Macbook being used. Why not just buy a new one? Remember project requirement number 2? A new Macbook was definitely out of the question. Because of the age, various Adobe programs had stopped working. This lead to using [OpenCore Legacy Patcher](https://github.com/dortania/OpenCore-Legacy-Patcher/releases/tag/0.6.0) to install a newer version of MacOS than officially supported by Apple. This solved the issue with Adobe programs, but is not without its own drawbacks. It turns out that OpenCore works better if you follow _all_ the instructions―which I didn't do initially. Oops. Once that was squared away the aged Macbook started behaving much better.

With the Macbook behaving again, it was time to setup a few tools.
- GitHub
- [Pulsar](https://pulsar-edit.dev/) (🪦RIP Atom)
- Kitty
- Jekyll template

With the tools in place, we talked about `git` and how to use it as a single user. Then we made a new repo on GitHub, cloned it to the laptop, and started making changes.

The website is still a work in progress, but it is up on GitHub Pages and the user knows how to change things and publish the changes. Now all that is left is for them to finish tweaking it to their liking and then do the cutover to the custom domain they have.



<br />

___

_Remember, if something hasn't gone wrong yet, you're not trying hard enough._

-Nate
