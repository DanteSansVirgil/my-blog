---
title: "Eclipse Viewing Without Glasses: An Unofficial Guide"
date: 2026-01-22
draft: false

cover:
  image: "cover-small.jpg"
  alt: "cover thumbnail"
  relative: true
---

Do not attempt.  I am what you might call a "professional".

<!--more-->

The Great North American Eclipse of 2024 brought totality to 15 states here in the good ol' US of A.  The corona's intensely bright light is damaging to view for even a few moments with the naked eye. Much like toilet paper circa March 2020, the glasses needed to safely view the corona were completely sold out in the days leading up to its arrival.  I wasn't sure if I would have work off that day so I had not planned ahead.  Even my buddy in Boston couldn't locate a pair by the time we decided to take the road trip into northern Maine along the path of totality (t-minus 2 days).  What are a couple of bandwagon astrologists to do?

A heavy duty pair of welding goggles suits the same purposes as these plastic glasses - dimming most but not all visible light, along with UV rays.  So $30 and one trip to the local Harbor Freight and we're good to go, right?  

{{< img src="normal-helmet.jpg" alt="My photo" width="1200" >}}

***Wrong!  No eyesight for you!!***

Modern welding helmets are designed to always block some ambient light, but only kick on their full protection when it detects an arc flash.  It's called an auto-darkening feature.  Modulated (pulsed) infrared light released by welding arcs are detected by the helmet's sensor and flow an electric charge over its viewport.  This converts its nifty panel into a polarized configuration that blocks all the things you don't want to see.  Great for welding in your garage, bad for viewing an eclipse. 

Luckily someone brave and clever enough on Hackaday had already implemented a solution - blast pulsed infrared light at the helmet's photodiode directly and you have an always-darkened welding helmet.

Unfortunately amazon prime 2-day delivery is more like amazon 5-day where I live, and I don't keep IR LEDs on hand.  Guess we'll have to wait for the next eclipse to hit the contiguous United States in another... (checks Wikipedia) ...20 years.  Oh, no.


---


WALMART to the rescue!  Because inside every $5 RCA television remote is an infrared LED, trying to come out!  It's a hardball world, son. We've gotta keep our heads until this eclipse craze blows over.  

But these remotes will never know the tender tele-photonic touch of a television screen.  Because I plan to rip them apart and save myself a 20 year wait.

***God bless Walmart***

{{< img src="remote.jpg" alt="My photo" width="1200" >}}

Once we've cracked the case, helping hands let us desolder the IR LED.

{{< img src="board.jpg" alt="My photo" width="1200" >}}

We add a resistor to prevent burnout of the LED inline with a toggle switch (transplanted from a $1 flashlight courtesy of Dollar Tree).  

To modulate the output, I connected the LED to a PWM output pin on a Wemos D1 Mini (these I DO have lying around).  This is a basic microcontroller that we can program to pulse the IR light output, similar to an arc flash.

The Dollar Tree comes in clutch again with a tiny USB battery pack, which will power the whole device through the D1 Mini's microUSB port.

***In my haste to finish this build, only a few pictures were taken.***
{{< img src="wemos.jpg" alt="My photo" width="1200" >}}

Once mounted directly to the helmet's photodiode sensor with a 3D printed adapter, this wannabe Cyberpunk headgear was ready for action.  [Queue  theme music.](https://www.youtube.com/watch?v=Kn0z35E5Z34)

{{< img src="cocacola.jpg" alt="My photo" width="1200" >}}

***Yes, that's hot glue.  If it works, it works.***

{{< img src="betterhelmet.jpg" alt="My photo" width="1200" >}}

By clicking the toggle switch, we can turn the auto-darkening feature on or off, regardless of ambient light.

I made two of them and on April 8th, 2024 we rendezvoused in Augusta, Maine to test them out.

***Operation Sunglasses is GO***
{{< img src="mike1.jpg" alt="My photo" width="1200" >}}

We drove further north and found some other observers within the path of totality.  Here we are posted up in a field, waiting for the sun to stop shining. 

{{< img src="chilling.jpg" alt="My photo" width="1200" >}}
{{< img src="me.jpg" alt="My photo" width="1200" >}}

I don't have many photos of the actual event.  It was a surreal experience and pictures would not do it justice.  

However, at the very end, I did snap this pic of my buddy pointing towards the sky, doing his best Lethal Company Employee impression.  It's important to note that he was not looking directly at the corona with the helmet up.  It's just as impressive to look around at the eerie twilight effect as it is to see the corona through the safety glasses.

{{< img src="eclipsed.jpg" alt="My photo" width="1200" >}}

Sometimes I still think about that sudden stillness snailing across the sky.  Definitely worth the carnage (R.I.P. flashlights and remote controls).

{{< img src="cover.jpg" alt="My photo" width="1200" >}}

And if you want to view the next total solar eclipse with some real glasses, now you have an eighteen year head start!