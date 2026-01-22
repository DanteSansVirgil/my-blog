---
title: "My Oops-Baby Desktop PC"
date: 2026-01-22
draft: false

cover:
  image: "cover-small.jpg"
  alt: "cover thumbnail"
  relative: true
---

***A lesson in feature creep and happy accidents.***

<!--more-->

Most PC builders agonize over every little bottleneck and component when they spec a new build.  But this caseless monstrosity I call my primary PC did not begin life in that way.  To understand how it came to be, we have to blame the cryptocurrency boom of 2021 and some poorly insulated walls.

The coldest months in my region average 15 degrees Fahrenheit overnight.  Living in a bedroom built circa 1850, I was supplementing with electric heat for most of the winter.  The corner of my room with the desktop computer was always slightly warmer, especially while gaming with the GPU under load.  It was then that I realized computers are basically space heaters with extra steps.  

I had dabbled in cryptocurrency mining years before, but the economics of it never made sense.  After factoring in the cost of electricity, you could net maybe $0.25 per card per day.  The rise of ASICs and power-pirate GPU farms had achieved a market equilibrium that would make Adam Smith blush.  At that time, the idea of using cryptocurrency mining to heat my room didn't really seem worth the trouble.

However, that winter, an army of sus speculators and FOMO-finance-bros convinced Joe Rogan that the digital gold rush was back on.  I was already looking for an excuse to pump electrons through very expensive resistors, so I bought a shovel!  Actually, I bought six shovels. 

---



***Number go UP! 10,000 to 50,000 in 2 months***
{{< img src="btc-graph.jpg" alt="Number go UP!" width="1200" >}}


The increased price of crypto meant mining with a 1080Ti could net you $3 a day (when you consider the electricity heating your room a sunk cost).  I began to accumulate used GPUs on eBay.  And eventually I ran out of PCIe ports on my motherboard.  Oops.


---

***My old desktop PC with three 1080Tis crammed "into" it.  Forgive me, BigBlue.***
{{< img src="bigblue.jpg" alt="My old desktop PC with three 1080Tis crammed into it.  Forgive me, BigBlue." width="1200" >}}



The solution?  A new motherboard!  I estimated I could run 6 cards simultaneously before worrying about tripping power breakers (drawing ~200W continuous per card).  

Turns out there are not many boards that support six cards simultaneously.  After much research, I found a good deal on a combo B450 Gaming Plus Max with 2x8GB DDR4 RAM and Athlon 3000G with a 256GB Samsung 980 NVME drive.  I also grabbed six PCIe risers and three open-box 650W Seasonic PSUs (two cards per PSU).

***A very crude wooden platform, using some 3D printed brackets and the PSUs as structural supports for a 1x4 beam to mount the cards.  If it works, it works.***

{{< img src="wood-base.jpg" alt="My photo" width="1200" >}}

***A tactical ramen cup was later added to "tilt" the GPUs and prevent rocking on the risers.***

{{< img src="ramen-mode.jpg" alt="My photo" width="1200" >}}

After struggling with CUDA drivers for a week, I finally had 1200 watts of heating and ~$18 per diem for my trouble.  

---

I ran the mining rig for about two years before the block difficulty and price of cyrpto slowed down to the point it wasn't really worth continuing.  I also moved into a new place that didn't need electric heat to stay warm.  At that point, I "sold the farm", and kept an extra 1080Ti to make a new gaming computer.  

I upgraded the CPU to a Ryzen 3600 and planned a new layout for the case.  I really liked the caseless design and was surprised with how little dust accumulated on the mining rig, so I stuck with that approach.

There was ample 80/20 aluminum extrusion laying around from my first DIY 3D printer.  I printed some custom mounting hardware and put it all together in a weekend.

In keeping with the minimalist aesthetic, there was no power switch.  I would short the PWR pins with a metal screwdriver to start it up.  Security through obscurity, anyone?

{{< img src="frame.jpg" alt="My photo" width="1200" >}}
{{< img src="frame2.jpg" alt="My photo" width="1200" >}}

The computer could be mounted vertically or laid flat depending on desk space.  For a year or so, it was plagued by issues with crashing under load due to obscure firmware changes I made when it was a mining rig.  A BIOS update eventually fixed those issues.

{{< img src="frame3.jpg" alt="My photo" width="1200" >}}
{{< img src="frame4.jpg" alt="My photo" width="1200" >}}
{{< img src="flat.jpg" alt="My photo" width="1200" >}}


---

I would like to thank NVIDIA for the greatest mistake they ever made: the 1080Ti.  A card launched in Q1 2017 has no business being so relevant almost 10 years later.  For 1080p gaming at 144Hz, it gets the job done for most titles.  Color coordination dictated I swap the MSI Armor card for the beefier and RGB LED equipped AORUS.

{{< img src="aorus.jpg" alt="My photo" width="1200" >}}

***As they say on the Fury Road; BY MY DEEDS I HONOR HIM, 1080 TI!!***
{{< img src="madmax.jpg" alt="My photo" width="1200" >}}

In 2026, I added 1TB of SSD storage for applications and 4TB HDD for bulk storage.  The RAM is overclocked to 3600MHz using XAMP.  But when I tried overclocking the Ryzen 3600 to 4.2GHz, I was hitting the temperature cutoff limit (~90 degrees Celsius).  Oops.

I replaced the stock cooler with a dual-tower ThermalRight Peerless Assassin.  Now it slings 4.2GHz at a balmy 60 degrees Celsius.  And it comes in black!

{{< img src="cooler.jpg" alt="My photo" width="1200" >}}

Around the same time, I bought myself this nifty knockoff LEGO kit of an SR-71 blackbird.  The PC seemed like a nice place to display it.

{{< img src="blackbird.jpg" alt="My photo" width="1200" >}}


In keeping with the whole black/red cockpit theme, I rigged up a missile-launch style toggle switch with a 3D printed bracket for maximum "engine startup" factor.  [Queue  theme music.](https://youtu.be/NOMa56y_Was?si=pervOOjL58mWStCC&t=10)

<video controls playsinline muted loop style="max-width: 100%; height: auto;">
  <source src="/videos/switch.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>


The HDD needed its own mounting bracket and vanity cover. Some CAD modeling and multi-color printing proved successful.

{{< img src="cad-hdd.jpg" alt="My photo" width="1200" >}}

{{< img src="vanity.jpg" alt="My photo" width="1200" >}}


***System complete! (for now...)***


{{< img src="cover.jpg" alt="My photo" width="1200" >}}


Hopefully I can squeeze another 3 years out of this happy accident.  Sure, it doesn't push Mach 3, but it's good enough for the games I go out with.

I even shoe-horned the extra Athlon3000G and 650W PSU into another project.... coming to another blog post soon!


Final specs:
Ryzen 3600 @4.2Ghz overclock with dual tower air cooling, Ripjaws DDR4 2x8GB XAMP/3600MHz overclock, B450 Gaming Plus Max Mobo, 650W Seasonic Bronze PSU, 256GB Samsung 980 NVME (OS), 1TB SSD Western Digital SA510, 4TB HDD Western Digital WD40EZAZ
