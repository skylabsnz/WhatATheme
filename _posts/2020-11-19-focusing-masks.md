---
title: "Comparing different focusing masks for camera lenses."
layout: post
post-image: "/blog/assets/images/003_bahtinov_spikes_night_photography.jpg"
description: Focusing a camera lens in the dark represents the most challenging operation for amateurs and professional astrophotographers, and night photographers. Traditional Bahtinov masks have been in use for astrophotography in relatively large aperture telescopes. This type of mask delivers a diffraction pattern, creating a set of three fine spike lines around a bright star. Once the three lines are aligned in a single spot, the focus is achieved.

tags:
- Astrophotography
- Night Photography
- Focusing Mask
- Bahtinov
---

Focusing a camera lens in the dark represents the most challenging operation for amateurs and professional astrophotographers, and night photographers. Traditional Bahtinov masks have been in use for astrophotography in relatively large aperture telescopes. This type of mask delivers a diffraction pattern, creating a set of three fine spike lines around a bright star. Once the three lines are aligned in a single spot, the focus is achieved.

There are many options in the market, and it is easy to get lost due to the obscure propaganda from the sellers and misleading experiences from different users.
I do manufacture, sell, and actively contribute to open-source focusing masks projects.
This article provides an in-depth analysis of the suitability of each type of focusing mask for camera lenses in order to avoid common frustration. To conduct these tests, I have used a Canon 100D (crop sensor) and two lenses, the stock 18-55mm and 75-300mm.

<img src="/blog/assets/images/003_bahtinov_order.jpg" width="45%" class="center" /><img src="/blog/assets/images/003_bahtinov-masks.png" width="45%" class="center" />

## About Bahtinov Mask
Several types of masks have long been used as focusing aids for astrophotography. The distinctive pattern delivered by the popular Bahtinov mask was invented by Russian amateur astrophotographer Pavel Bahtinov in 2005.

When the stars are not in focus, the default pattern would be an Airy disk as a result of a circular aperture. If the Bahtinov mask is in place, the pattern exhibits asymmetric spikes representing the transform of the mask pattern's spatial frequency and orientation.

## What you really need to know
You will find several Bahtinov masks in the market defined by the size of the mask (aperture). Unfortunately, to generate a useful pattern, the shape of the mask ALSO depends on the focal length and the Bahtinov factor.

The Bahtinov factor is defined as:

<center>BF = f/s</center>

Where “*f*” is the focal length and “*s*” is the size of the slit+space. To get enough resolution, the Bahtinov factor must be at least 150, ideally 200. Obviously, the more lines, the better.

That means that the real limiting component is the focal length. The shorter it is, the smaller the slits and spaces have to be. As cuts get too small, you can multiply the “*s*” number by 3 and use 3rd order spectrum, as it has no visual difference compared to the 1st one.

The following image represents a tri-Bahtinov mask I created for a 75mm lens with BF=200, using the 3rd order spectrum. The slits are ~0.6mm wide, which sits almost at the limit of 3D printing.

<img src="/blog/assets/images/003_tri_bahtinov.png" width="80%" class="center" />

Using the Bahtinov mask on shorter focal lengths can be done, but the BF will decrease, and it will introduce a lot of light obstruction, to the point is not going to be useful.

To overcome this challenge, I developed a Bahtinov mask based on optical level acrylic material, which offers 92% light transmission, excellent optical characteristics, light stability, and low internal stress levels for consistent performance. The CNC etched surface ensures very accurate and thin slits that generate a precise diffraction pattern with a minimal light obstruction. The slits are 180µm thick, which is similar size as the diameter of human hair. As a result, it delivers the brightest diffraction spikes for achieving an incredibly accurate focus.

This new type of Bahtinov mask allows increasing the number slits in a small area, and it is several times brighter than traditional ones. In the particular case of [Skylabs Enhanced Bahtinov V2](http://skylabs.co.nz/enhanced_bahtinov_mask.html), the "*s*" value goes down to 650µm. That give a BF=65 for the popular Samyang/Rokinon 14mm f/2.8 lens and a BF=111 for Samyang/Rokinon 24mm f/1.4. Since those values are lower than the ideal, you may need to take some pictures with the mask before getting the right focus.

The video below provides a quick overview of the user experience using 50mm and 75mm and two types of Bahtinov masks.

<iframe width="560" height="315" src="https://www.youtube.com/embed/BQ5zj6Sm_1w" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

The following images have been taken with a canon 18-50mm stock lens provide at 50mm f/5.6 using an artificial star out of focus. As you can see, the number of lines contributing to the diffraction pattern in the Skylabs Enhanced Bahtinov mask V1 and V2 are significantly higher than the 3D printed ones.

There are other brands in the market. The Skylabs Enhanced Bahtinov masks are compatible with the most popular square filter formats (Haida, NiSi, Lee, K&F Concept, Cokin, BENRO, Formatt-Hitech, etc.), which also ensures that it can be used across multiple lens sizes.

The Skylabs Enhanced Bahtinov will outperform with bright lenses (low f-number) and long focal lengths. As the f-number grows, the resolution of the diffraction pattern fades out. Avoid stopping-down your lenses while you are evaluating the focus. If you are working with a short focal length (<14mm) and high f/number (>2.8) consider pointing to a very bright star or a distant light bulb further than the hyperfocal distance. A torch covered with a foil and a pinhole will work.
Technology has been able to bring this useful tool to short focal lengths; unfortunately, extremely short focal lengths require sensors with very small pixels. If you want to use a fisheye 8mm or shorter, check first if the size of the pixels of your sensor is over 4µm.

Tri-Bahtinov masks in camera lenses are a challenge because the shape of the mask must fill-up the complete aperture. Otherwise, the spikes generated by the outer pattern are not bright enough, because it is not exposed or it is just partially exposed.

## Conclusions
- If you are using focal lengths over 75mm, you can use a very affordable Bahtinov mask lens cap.
- If you are working over 50mm, you will take real advantage of using a mask similar to the Skylabs Enhanced Bahtinov mask.
- If you are using focal lengths over 14mm and slow lenses, optical grade acrylic is the only option.
- Short focal lengths with a high f-number (slow lenses) will not work even using a Skylabs Enhanced Bahtinov mask V2.
- If you are using fisheye lenses, the limitation will be on the size of the pixels of your sensor.

If you live in New Zealand, you will find Skylabs Enhanced Bahtinov on [Trademe](https://www.trademe.co.nz/Browse/Listing.aspx?archive=1&id=2814754675). Check the [Skylabs NZ](http://skylabs.co.nz/enhanced_bahtinov_mask.html) website to place international orders.
