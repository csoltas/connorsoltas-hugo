+++
date = "2015-12-26T23:04:43-05:00"
weight = -10
thumb = "specless-thumb.png"
thumbleft = false
teaser = "Aspect ratio is so last year."
subtitle = "How making a design tool for online advertisers led to big questions about image editing and the responsive web."
title = "designers without borders"
previewlink = "huh?"
bigimg = "specless_big.png"

+++

### some context 

Designers of online ad campaigns have to think inside the box. That is, their tools constrain them to canvases whose fixed dimensions don't reflect the near-infinite variety of proportions their ad, once published on the web, will eventually take on.

It's a problem for them because most designers don't know how to code their ad to respond under different aspect ratios. They just have to design a ton of variations one-by-one, then share all those with developers. Which takes time and money.

[Specless](http://gospecless.com) solves that. Their founders Steve and Shashank brought me in to do a ground-up redesign of Specless's flagship enterprise web app---a design tool that writes code for the ad automatically, allowing ad designers to create just one ad for all possible shapes and sizes, and visualize precisely how it'll look.

<img src="/img/specless-casestudy1.jpg">

### big questions

Turns out the problem is really hairy.

The challenge fundamentally isn't to design a nicer experience for creatives. It's to make the front-end coding framework that underpins context-aware ads into something that's no less visually intuitive than Photoshop. If the app itself can get designers to think like front-end developers (whether they know it or not), then the automatically-generated code will be simpler and it will behave better in a wider array of situations.

This is hard because it means uniting the way designers work with the way developers think. Traditionally these are seen as polar opposites.

<img src="/img/specless-casestudy2.jpg">

Nobody tells you where the line between "not enough" and "too much" abstraction is.

For instance, the app would have to encourage designers to think about hierchical [Cascade](http://cascade-framework.com/) concepts like "flowlanes" and "breakpoints." But should it force these concepts to the fore, at the expense of a simple interface? It would have to be a graphics editor without defined canvas boundaries. But should it display one canvas, or several---as it really is? It would have to convey branching conditional logic without outright teaching designers how to code. But how deep down the rabbit hole should the app push them?

<img src="/img/specless-casestudy3.jpg">

But I figured as long as I could nail the few genuinely tricky interface questions, then the rest of the tool could parrot a stripped-down Photoshop---making for a mostly familiar experience.

### familiar solutions

Over the course of a month I met every few days with Steve, Shashank, and their lead frontend developer Michael. I'd storyboard the wireframes in their most recent state---and the three of them, usually Steve, the CEO, would call out issues as we went.

Making branched logic visual seemed like a dead-end, so at first, I tried to avoid designs that wore the full complexity of Cascade on their sleeve. I pretended breakpoints and flowlanes were equivalent concepts (when really the former is always a child of the latter), and I designed digital [slide rules](https://en.wikipedia.org/wiki/Slide_rule) and [squares](http://lumberjocks.com/assets/pictures/reviews/32463.jpg) as digital analogues of flexible measurement devices users might already be familiar with.

<img src="/img/specless-casestudy4.jpg">

The outcome looked okay (if somewhat heavy-handed), but Steve wanted something that more transparently matched the way the code would actually be generated. The app needed to be honest about the code it wrote, we agreed. Flowlanes were flowlanes and breakpoints were breakpoints.

So, back to the drawing board. Instead, I turned to familiar digital tools as control analogues. Stacked "timelines" and "playheads"---borrowed from video editing, with which designers might be even more familiar---provided a simpler solution that more accurately reflected the ways CSS rules can overwrite one another. To create a new breakpoint, the user could just click the "+" where the rulers intersected and drag a new breakpoint across the ruler. Moving between breakpoints and flowlanes was easy, too, since big swaths of the canvas or ruler could be activated as giant buttons. And adding animation/interactivity was also straightforward---you just opened the drawer beneath the layers panel.

<img src="/img/specless-casestudy9.jpg">

The completed project was an [InVision](https://invisionapp.com/) workflow showing how the new product could reproduce Specless's latest client project---a huge responsive ad for Netflix, which took 2-3 days of hand-coding---in about 5-10 minutes. Steve and the Specless team were thrilled with the result, went on to a successful fundraise, and began immediately building out the redesign of their new flagship web app in testable pieces.

<img src="/img/specless-casestudy6.jpg">
<img src="/img/specless-casestudy7.jpg">
<img src="/img/specless-casestudy8.jpg">