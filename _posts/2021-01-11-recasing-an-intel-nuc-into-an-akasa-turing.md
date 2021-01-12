---
layout: post
title: "recasing an Intel NUC into an Akasa Turing"
description: "Fitting the NUC8i5BEK into the BladeRunner-esque looking case"
date: 2021-01-11
tags: ["Intel NUC", "Akasa Turing", "server"]
---

I've had an Intel NUC (NUC8i5BEK) running as my Linux server for a little while now, but was always unimpressed with the factory case. Its cooling solution is a laptop impeller-style fan, which quickly accumulates dust.

Recently, I was looking for alternate cooling solutions and came across the [Akasa Turing case](http://www.akasa.com.tw/update.php?tpl=product/product.detail.tpl&no=181&type=Fanless%20Chassis&type_sub=Fanless%20NUC&model=A-NUC45-M1B) for 8th Generation Bean Canyon Intel NUCs.

![nuc-turing-1](/assets/images/nuc-turing-1.jpeg){: .center-image}

While smaller than it looks in promo images, it sits much heavier than you might assume - nearly a 6 pound aluminum block! And for good reason too, the whole thing is one massive heatsink!

Impressed by the build quality, design, and reviews, I decided to get one and recase my NUC into it.

&nbsp;

First things first, I popped off the NUC's base and removed the RAM & SSD.

![nuc-turing-2](/assets/images/nuc-turing-2.jpeg){: .center-image}

&nbsp;

After carefully detaching the wifi cables & front panel array, the motherboard comes out with some gentle prying.

![nuc-turing-3](/assets/images/nuc-turing-3.jpeg){: .center-image}

&nbsp;

Next up: removing the cooling solution.

You'll notice that there's dust caked in the impeller - I had only just cleared it a few months earlier.

![nuc-turing-4](/assets/images/nuc-turing-4.jpeg){: .center-image}

&nbsp;

After wiping the dies clean with rubbing alcohol & dabbing a bit of thermal paste, the motherboard is ready to get fitted into the Turing!

Before:

![nuc-turing-5](/assets/images/nuc-turing-5.jpeg){: .center-image}

After:

![nuc-turing-6](/assets/images/nuc-turing-6.jpeg){: .center-image}

And in the case!

![nuc-turing-7](/assets/images/nuc-turing-7.jpeg){: .center-image}

The motherboard rests on top of a small aluminum block, which will transfer the heat away from the dies to the giant metal fins.

&nbsp;

The only downside of the Turing case for this NUC model is that it doesn't provide any heatsink for the M.2 SSD - I had to get one separately. However, there is a lot of headroom in the case for taller SSD heatsinks.

![nuc-turing-8](/assets/images/nuc-turing-8.jpeg){: .center-image}

&nbsp;

Finally, it's time to fit the RAM and SSD back onto the motherboard. All the components are in the new case now!

![nuc-turing-9](/assets/images/nuc-turing-9.jpeg){: .center-image}

&nbsp;

And the recasing is complete! Very straightforward assembly. I wish I had taken performance screenshots before recasing, but the NUC now runs about 10° C cooler with the Turing.

The blade design and top metal plate give off a BladeRunner/industrial vibe that really stands out:

![nuc-turing-10](/assets/images/nuc-turing-10.jpeg){: .center-image}

![nuc-turing-11](/assets/images/nuc-turing-11.jpeg){: .center-image}

![nuc-turing-12](/assets/images/nuc-turing-12.jpeg){: .center-image}

I wish I had taken before/after thermal benchmarks, but I rushed to get the NUC recased. However, if you're interested in the thermal performance of a similar NUC (10th Gen) into the next iteration of this case, [this blog](https://nucblog.net/2020/07/akasa-turing-fx-review-frost-canyon-fanless-case/) goes into great detail.
