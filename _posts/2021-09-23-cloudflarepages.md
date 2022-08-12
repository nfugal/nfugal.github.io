---
title: "CloudflarePages"
excerpt: "In this week's episode, I go all-in with Cloudflare"
date: 2021-09-23
header:
  overlay_image: /assets/images/system.webp
categories:
  - "Websites"
tags:
  - "Cloudflare"
  - "Vercel"
  - "Migration"
---


Long, long ago, in the Before-time, I decided I wanted a personal website. I like self-hosting things and such so I tinkered with doing just that. It worked... mostly.

Then I read an article somewhere about static-site generators such as [Gatsby](https://www.gatsbyjs.com/), [Hugo](https://gohugo.io/), and [Jekyll](https://jekyllrb.com/) (unfortunately I do not recall the article that first sparked my interest so I am unable to give credit where it's due. It was good though). I decided, "Hey, I can do that!" despite the fact that I had (and still have) _very_ little coding experience. I tinkered some more and eventually got something working.

Somewhere along the way, I registered for a [domain](natefugal.tech/about) and stumbled upon a project/product called [Vercel](https://vercel.com/) (it was called Now when I started but they've since changed names). Vercel promised to host my site for free and since I had been tearing my hair out trying to make self-hosting work how I wanted with [nginx](https://nginx.org/en/) in [Docker](https://www.docker.com/) (if you're gonna self-host like that, I hope you don't have Comcast for an ISP. They make it a big ol' PITA. It's almost like they _don't_ want you to host websites from your home...) I decided to give it a shot. I converted my static-ly generated site into a Vercel project and that's how [this site](https://natefugal.tech/) has been hosted for at _least_ 2 years (I'm pretty sure it is longer, but 2 years is as far back as the GitHub repo goes ¯\\_(ツ)_/¯ Oh well.).

Somewhere during this process I got interested in Cloudflare as [a DNS provider](https://blog.cloudflare.com/announcing-1111/) (I'm looking at you 1.1.1.1). I made them the DNS provider for my website and started using 1.1.1.1 everywhere I could.

Fastforward to today, I encountered CloudflarePages for the first time today (I'm prolly super behind. I know.)―which leads me to my point―I'm gonna try to migrate from Vercel to CFP.

If you're reading this, it probably means that the migration worked and that my website is hosted & DNSd from start to finish using Cloudflare―they even are managing the domain registration (should you find yourself curious about how it works, check out one of the static-site generators linked above. Feel free to checkout the [GitHub repo](https://github.com/nfugal/stunning-octo-pancake) for this site too). Also it's likely faster now. Thanks Cloudflare!

Thanks for all you've done for me Vercel. You've been great. But as an incurable tinkerer, it is time for me to try something new.

That's all for now.

<br />

_Remember, if something hasn't gone wrong yet, you're not trying hard enough._

-Nate
