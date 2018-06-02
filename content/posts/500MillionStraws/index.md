---
title: "500 Million Straws"
date: 2018-06-02T09:42:17-04:00
draft: false
tags: []
categories: []
# slug:
# description:
---

In the last few years, it's been quite common to see the statement that "Americans throw away 500 million straws per day" thrown around. That figure seems to not having any [verifiable backing][reason] and either way I agree that one time use plastic items should go away. But that's not why I'm here. I'm here because I want to visualize what 500 million straws per day is.

[EcoCycle][eco] already tried to do this by comparing it to the capacity of school buses but that's just boring. I'd rather use speed... specifically, if one single machine had to make *all* 500 million straws, per day, how fast would they come out of that machine?

<!--more-->

I know, you're saying "That's impossible!" or "That's insane! No machine could do that!". But in the grand tradition of spheres in a frictionless vacuum, hypotethical science and math is way more fun if you just assume a few things that aren't actually possible. Moving on...

Since [EcoCyle][eco] seems to be the main originator of this value, I'll use some of their assumptions. Mainly that an average straw has a volume of **0.75** cubic inches. But because we're all scientists here, we'll just go ahead and call that **~12cm<sup>3</sup>**. But we don't actually need volume (of course, the empty center of the straw is included in that volume), we need the length. Most straws are probably around **7mm** in diameter. Volume of a cylinder is:

{{< tex display="V = {\pi}r^{2}h">}}

Therefore the heigh of a cylinder based on the volume is:

{{< tex display="h = \frac{V}{{\pi}r^{2}}">}}

So, we get:

{{< tex display="h = \frac {12cm^3}{{\pi}\times0.35cm^2} = 31.18cm" >}}

That's about **12.27** inches for all you imperial types.

Ok, so that's **31cm** or **0.31m** per straw and 500 million straws, for a total length of {{< tex "\bold{0.3m \times 5\times10^8 = 155,000,000m}">}} which is **155,000km** or **96,313 miles**. For scale, that is roughly long enough to wrap around the entire Earth, at the equator, **4 times**. That's one long straw!

But we need to make that much in a single day. For the sake of the math, we'll use **86,400 seconds** and therefore the required speed is:

{{< tex display="v = \frac {1.55\times10^8m}{86,400sec} = 1794m/s">}}

Punching the above into [Wolfram Alpha][wolfram] comes up with some fascinating comparisons and conversions, but those I found most interesting:

- **Mach 5.2**: These straws are *hypersonic*!
- **4013 mph** for the imperial users
- **0.76 Moon Escape Velocity**: if we only increased our straw usage by **~33%** and produced them on the Moon, they would shoot out of the machine, orbit the moon and slam into the back of the machine at **Mach 7**

When dealing with speeds that quick it makes me wonder what kind of damage a hypersonic straw could do. A quick survey of various straws on the internet gave me a rough average weight of about **13g** per straw. So what would happen if the straw was ejected from this hypothetical hypersonic straw machine, cut to length and then hit a solid object? Kinetic energy is:

{{< tex display="K = \frac{mv^2}{2}">}}

So that gives us:

{{< tex display="\frac{(0.013kg \times 1794m/s)^2}{2} = 20.92kJ">}}

Unfortunately for the poor people running this hypothetical hypersonic straw machine, this is *a lot* of kinetic energy. Not insane or anything, as it's about the same energy as a mere **0.25 milligrams** of TNT. But let's look at it this way; we can see from [this handy table][muzzle_energy] that the energy of a bullet from a 9mm handgun is **494J** or **~0.5kJ**, a mere **2.3%** the energy of our hypersonic straw. In fact, our straw has more energy than every single round on that list with the exception of an anti-tank round weighing in at 10kg!

So, how about we all just stop using straws so that no one need be destroyed by a hypersonic straw?


[reason]: http://reason.com/blog/2018/01/25/california-bill-would-criminalize-restau
[eco]: http://www.ecocycle.org/bestrawfree/faqs
[wolfram]: http://www.wolframalpha.com/input/?i=1.55e8+meters+%2F+86,400+seconds
[muzzle_energy]: https://en.wikipedia.org/wiki/Muzzle_energy#Typical_muzzle_energies_of_common_firearms_and_cartridges