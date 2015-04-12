---
layout: post
title:  "Screens Update"
date:   2015-03-26 16:00:00
---
At the end of 2014 we took the plunge to replace the large screens in the front of the sanctuary. Here's the why and how. 

# Our Principles

As part of running the various technical services in St Columba's and its church plants we have a few principles:

1. Don't waste money - when we can, we tend to go for a high quality implementation that requires a small amount of our time, rather than paying top dollar for equipment. However, we recognise that sometimes this is counter productive and it's best to wait, save and purchase the right piece of equipment.
2. Standardise - don't mix technologies when you don't need to. Choose the best one that fits the requirements (and future requirements) and implement it across the board.
3. Tech in church should be unobtrusive - we don't like tech that's distracting, we don't like visible cables and we don't like when tech fails and people notice!

Over the years, these principles have served us pretty well. We have a slick, relatively low cost technical infrastructure in the building that allows us to run services, record sermons in video/audio, live mix, live stream and enable the same quality and level of sound throughout the Sanctuary as well as have overflow (or a completely separate event) in the lower hall.

# Background Knowledge

## Aspect Ratio

When we talk about screens you'll often hear people talking about the aspect ratio - this is the screen ratio width versus height. Not so long ago televisions were fairly square (and bulky) and were in an aspect ratio of 4:3 (the width was a bit bigger than the height). Nowadays, what's commonly referred to as widescreen televisions are in the aspect ratio of 16:9. From a video point of view (nearly) everything is produced in 16:9 - for broadcast television and importantly for us, YouTube.

## VGA vs HDMI

VGA (analogue connector) has been the connection of choice for transmitting video signals for many years (it's the blue connection from your screen to your desktop computer), that is until they brought in the HDMI standard. Most people will be using HDMI now to connect their television to their set top box, games console or BluRay player. HDMI has a major advantage over VGA as it's digital. Without getting too in depth into the differences between analogue and digital signalling, basically HDMI will either work perfectly or not at all. There is no in between, no degradation of quality, no need to amplify the signal etc. This becomes more important when you start sending signals over distance.

## VGA/HDMI over Cat5

Cat5 is the cable commonly used in networking. It's fairly cheap - <£50 for 305m and you can get it shielded as well. The shielding helps further protect the signal from interference from other cables in close proximity to the Cat5 cable. Large VGA/HDMI cables are hard to find, bulky and not ideal. The alternative is to use Cat5 convertors so you end up with 

`PC<--VGA/HDMI-->Transmitter<--Cat5-->Receiver<--VGA/HDMI-->Projector` 

This allows you to have short VGA/HDMI cables and a long Cat5 cable. Because HDMI is digital when you send it over Cat5 there is no loss in quality. However when you send VGA over Cat5 the quality of the picture is dependant on the signal received. VGA Cat5 Receivers usually have a gain and a focus setting to allow you to amplify and (try to) correct the signal coming out of the VGA Cat5 Receiver unit.

# Current Solution

In 2008 when I came to St Columba's, the screens had only been up for a few years. The connection was fairly simple - VGA out of the PC into a really long VGA cable which arrived into a splitter which was then connected to Projector Left, Projector Right and the Lectern Screen. However there was a major issue. The primary use for screens in St Columba's is to show the words for the songs being sung during a service. In this setup configuration there was an interference problem. What was happening was when the presenter was singing, the signal was going into the loop system which was interfering with the video signal to the screen causing a constant visual disturbance. This happened when everyone was looking at the screens so it was very noticeable. Since we couldn't give up the loop system we looked for a way to sort the issue. We did try ferrite cores which help absorb electrical interference but weren't very successful with them. We then looked at converting the signal to Cat5 knowing that we could purchase FTP (Foil Twisted Pair) Shielded Cat5 Cable which would provide some protection. After much discussion, we took the decision to try it out and picked up some Lindy VGA Cat5 Transmitter/Receiver Pairs a box of Cat5 FTP and a Cat5 Patch Panel. For the last 5/6 years the solution worked with no more interference on the screens. However in that time we've also added a 50" Screen at the Balcony, a 40" Screen at the Front Door, a ~20" Screen in the Baby Corner and replaced the lectern screen because it broke. On top of the new screens we have a conference video camera with large optical zoom for recording sermons and live streaming the General Assembly and weddings. When you have multiple things to show on the screens you need a video switch or a video matrix so we've been running with a VGA matrix as well as some splitters. Below is how the video connections were made:

![Video Distribution Setup with VGA](/public/images/2014-07-05-video-distribution-setup.png)

The solution was getting messy. We were using three different types of connection and because of the addition of the extra screens we were also using two different aspect ratios. The two different aspect ratios meant we had to create the same graphic for the two different screens - one at 1280x960 and another at 1280x720 which was inefficient. It was time to standardise and move completely to digital.

# The Solution

We needed to do two things:

1. Move everything to widescreen
2. Move all video signalling to digital

To achieve this we had to change the projectors, the screens and the Cat5 converters. We wanted to ensure that we solved the issues and that the solution we implemented would last at least 10 years.

## The build

After much research we decided that between us we would have the skills to build our own screens which is (for two screens) about £1,500 cheaper than buying two equivalent sized screens. We have a fair amount of space in which we can install the screens so we determined the size based on the standard size of a piece of wood - 2400mm. The height is simply 2400/16*9. 

![Screen Frame](/public/images/screen-frame.jpg)

This gave us a screen size of 108" (that's the diagonal corner to corner). So we ordered up material that is about 130" diagonally which would give us enough to be able to staple it to the surrounding frame.

![Screen with extra material](/public/images/screen-with-excess-material.jpg)

The next step is to staple the screen which sounds easier than it actually is. It took three of us to do it - two to pull the material tight and one to run around stapling in a pattern like [this one](http://www.carlofet.com/images/howTo/stretch-and-staple-technique.png). Here's the first screen:

![Screen Stapled](/public/images/screen-stapled.jpg)

We'd read a lot that adding a black felt border really helps you focus on the screen correctly, so we added some black felt as per below:

![Screen with felt](/public/images/screen-with-felt.jpg)

Because we have rear screen projectors we weren't able to have cross supports. Instead we used an 'A' frame style support:

![Screen with supports](/public/images/screen-with-supports.jpg)

After we got the projectors up and aligned properly we tested the image by bringing up one of the graphics for 'Carols by Candlelight' and here's the result:

![Screens installed](/public/images/screens-installed.jpg)

## The Projectors

We needed projectors with a high quality, bright output and HDMI connectivity. We've had a BenQ projector in the Lower Hall for a couple of years and were really satisfied with the performance of it. They are relatively low cost and in our experience appear to be good quality projectors. We therefore decided that we would continue to standardise and buy two more BenQ projectors for the main Sanctuary. There were two models that we could choose from - the [W1070](http://www.amazon.co.uk/gp/product/B009SJB6F2?tag=andmfras-21) and the [W750](http://www.amazon.co.uk/gp/product/B00CFVHXHK?tag=andmfras-21). In terms of future proofing the 1080p projector made sense. However, we couldn't justify the cost and therefore decided to go for the 720p W750, but waited for Black Friday deals to see if we could find better prices for the better model. After a bit of searching we found the W1070 at Richer Sounds for £400 (at time of writing it's on Amazon for £577), since the price was in the range we were looking for, we ended up getting two W1070s - bonus!

![BenQ W1070](/public/images/benq-w1070.jpg)

## The Converters

Whilst the Lindy VGA Converters have served us well, we needed to replace them with HDMI converters. There was a lot of good reviews of the [Neet HDMI Converters](http://www.amazon.co.uk/gp/product/B002ECYEYA?tag=andmfras-21) and the price is reasonable so we're using them between all screens and the booth.

## The Connections

For ultimate flexibility, a HDMI matrix of at least 4 in and 8 out would have been ideal. Unfortunately they're very expensive. For example the Kramer VS-88H is retailing for around £2,000 - a little out of range. We had to compromise on the flexibility in order to build a cheaper solution so we're using a mix of a HDMI switch and a much smaller HDMI matrix as well as a few HDMI splitters. Given our main use cases it was possible to group the screens into two groups, those inside the Sanctuary and those outside the Sanctuary. With these two groups we then only require a 2 in 2 out HDMI matrix which is under £100. Below is how the new setup is connected.

[!HDMI Setup](/public/images/2015-04-12-video-distribution-setup.png)

# Conclusion

We did it! We standardised the aspect ratio of the screens around St Columba's, the method of sending video to the screens, the connection type and the size of graphics we create. Regardless of our budget, building screens was the best solution for us as they fit into the building better, look professional and are as big as we possibly could make them. If we had a larger budget we'd spend more on the screen material the projector projects onto but we'd still build the screens ourself.

We're slowly working to open up what we do in terms of technical services at St Columba's. If you want to know about something specific, leave a comment and we'll try and answer it.