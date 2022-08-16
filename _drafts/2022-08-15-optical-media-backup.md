---
title: "Backing Up Optical Media for Increased Utility & Ease of Enjoyment"
excerpt: "Discs are sooo last decade."
date: 2022-08-15
last_modified_at: 2022-08-15T16:20:02-06:00
header:
  overlay_image: /assets/images/discs-1344774.webp
  image_description: "Four discs spread out"
categories:
  - "How-To"
tags:
  - "Plex"
  - "Kodi"
  - "JellyFin"
  - "MakeMKV"
  - "HandBrake"
  - "FFmpeg"

---

## Disclaimer

Check your local copyright laws before digging into a project like this. I am **not** responsible for anything that happens as a result of you following these instructions. Proceed at your own risk.

## How to Backup Your Optical Media Collection

### Why You Might Want To

Optical media has some solid pluses. Ease of use in today's world is _not_ one of them. Anyone who had ever tried to binge watch a season of something on DVD or Blu-ray can tell you, getting up to swap to the next disc is just not the same as the auto-play next popularized by NetFlix.

Digitizing your media has some pluses (some minuses too). Here are some that jump out to me:

  + No more dealing with discs (after you finish the ripping & compressing of course)
  + Metadata-rich experience while choosing and watching
  + Faster to get to the content you _actually_ want to watch (no more unskippable previews or _sloooow_ loading menus, I'm looking at you Blu-rays)
  + Flexibility

For me, one of the big reasons to go discless was having a toddler, for whom DVD, Blu-ray, & Wii cases were unconquerably alluring. After backing everything up to internal storage, I got rid of the cases, put the discs in a giant CD wallet and boxed it all up out of sight. 5/7 would recommend.

### Why You Might _Not_ Want To

There definitely some reasons you might _not_ want to go discless. Here are some:

  + Time. Sooooo much time spent ripping and compressing things!
  + Streaming services availability.
  + Legality in your country
  + Upfront costs
  + Maintenance
  + Configuration
  + Did I mention time? It is a long project if you have a lot of discs.

### How Does Streaming Fit In?

Now I can practically hear someone screaming "Don't bother! Streaming is the answer!" to which I say, "Streaming sucks!" Here's why:

  + Service fragmentation:
    + Different interfaces to learn _everywhere_ and different apps to maintain/update
  + $$$$ or ads (sometimes both):
    + Sure Disney+ isn't terribly expensive on its own, but you add it to AmazonPrime Video & Netflix & HBOMax & Hulu & AppleTV & & & and its _more_ expensive than cable TV. 
    ![Obligatory Episode III meme](/assets/images/meme-eqawq1cgtkv81.webp)
  + Licensing: 
    + I'd much rather buy a thing once and then use it however I want than have to pay for that thing every month, use it or not, and have it potentially disappear from the service without me being able to do anything about it. The physicality of discs wins some major points here. Enough that I would _always_ rather buy the disc and rip it myself than buy it digital only.
  + Decreased choices: 
    + Sometimes a particular show or movie isn't available on _any_ streaming platform. Sometimes they come & go. In both cases, my ability to chose is limited―something I generally try to avoid.

### Why You Might Care for Instructions From Me

One word: 

  + Experience.

More words:

  + I've walked this path (multiple times because of some poor storage choices I made, we'll probably discuss that more a bit later) and successfully guided others along it too.


### Where to Begin?

#### Gather the Things

1. Some number of discs you care to backup:
  + The number will affect many aspects of this process but I'll write generally assuming somewhere a collection of interest in the 50-100 discs range.
2. A computer with a disc drive capable of reading the discs you want to back up:
  + This is becoming less and less common so purchasing one just for the project is a very real possibility. Fortunately they aren't particularly expensive.
  + The computer for ripping doesn't need to be particularly powerful. For compressing, you'll want the beefiest CPU you can manage to utilize.
3. Somewhere to store & serve the resulting files
  + A [RaspberryPi](https://www.raspberrypi.org/) with some external storage attached works great for many folks.
4. The appropriate software to make the job manageable and make your discless experience better than your discful one:
  + Ripping tool(s)
    + [MakeMKV](https://makemkv.com/)
  + Compressing/encoding tool(s)
    + [HandBrake](https://handbrake.fr/)
  + Media management tool(s)
    + There are many to choose from. If you prefer the FOSS route I'd highly recommend both [Kodi](https://kodi.tv/) & [Jellyfin](https://jellyfin.org/). If you don't mind the Freemium model, [Plex](https://www.plex.tv/) & [Emby](https://emby.media/) are both compelling options. Here are the ones I have the most experience with, in descending order (most experience first):
      1. Kodi
      2. Plex
      3. Jellyfin
      4. Emby
    + All of the software tools listed are available on many OSes. Specifically for me, Linux availability was paramount (👈 movie studio pun! 🥁), but I've helped others walk this path with Windows & MacOS too. 
