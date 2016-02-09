+++
date = "2015-12-26T23:06:16-05:00"
subtitle = "What if an app existed solely to have the easiest, most rewarding setup process imaginable -- and that was it?"
teaser = "What if an app existed solely to have the easiest, most rewarding setup process imaginable -- and that was it?"
thumb = "glidera-thumb.png"
thumbleft = true
title = "rethinking onboarding"
weight = -12
previewlink = "show me"
bigimg = "glidera-big.png"

+++

### what does this thing do, anyway?

Mike, Mohammed, and Dave thought [their startup Glidera](http://glidera.io)'s web app looked bad. When I asked why, they couldn't articulate what about it didn't appeal to them, or what they would change. It just didn't feel hip or modern to them.

They brought me in to give the Glidera web app a "facelift," as they put it. So the four of us spent over an hour in one of [Techstars](https://techstars.com/)' conference rooms, talking through their design gripes---some large and abstract, others incredibly specific.

<img src="/img/glidera-casestudy1.jpg">

While I listened, I also tried to piece together what a facelift would do for their company. Sure, their app didn't fit my personal aesthetics, but I wasn't the target user. Their core business wasn't a web interface for consumers---it was a proprietary API for their partners: Bitcoin wallet developers. Curious, I asked, "Who actually needs to use the site? What does this thing do, anyway?"

"The site's just for end-users to connect their bitcoin wallet to us."

That one comment changed everything about the project. What they said meant that once the end-user got her account set up on Glidera---in effect connecting a bitcoin wallet to Glidera's API---then everything was good; the user was done and wouldn't need to use the Glidera web app again unless there were problems with her bitcoin wallet.

So the site needed to be fantastic at just one thing: onboarding users. That was all it did.

Everyone knows form follows function. Ideally, that means any quest to solve ugliness should start with a search for brokenness. It rarely happens that way, and sometimes for good reason---it's cheaper and faster to tweak colors and fonts than to tease out underlying design problems. 

But Glidera had time and wanted to prioritize design. 

We went full-bore. Knowing that the web app basically had one feature lent an entirely different perspective on the problem. The app's division across four pages seemed totally unnecessary, and even confusing for users who weren't already keenly aware of what the app was supposed to help them accomplish. It didn't guide them through the only feature that mattered to it: setup. And it certainly didn't reward them for completing setup.

### shifting gears

I focused on a new question: What would an app that existed solely to have the easiest, most rewarding setup process imaginable look like?

I came back to the Glidera team suggesting they scrap the front-end and rebuild it as a simple one-page app. They had only asked for a facelift, but I responded that the reason the site looked bad was that it wasn't actually designed to do its purpose. Its multiple sections didn't encourage users to complete signup---they distracted users with content that wasn't useful until setup was complete. And the setup page itself added to the confusion---it wasn't clear that the setup process had to be completed in a specific order, or that, at any given point in the process, the user had a "next step" waiting for them.

In the desktop version of the app, I turned the setup steps into a horizontal timeline that clearly indicated your next step in the process. The app also suggested its buy/sell functionality below in a non-distracting way. Clicking the "next step" node on the timeline would trigger a modal with a simple form and a huge green checkmark, celebrating each step you completed.

<img src="/img/glidera-casestudy2.jpg"> 
<img src="/img/glidera-casestudy3.jpg">
<img src="/img/glidera-casestudy4.jpg">

Once you finished setup, the timeline itself would vanish entirely. Then you'd only see three buttons on the upper-right that allowed you to manage or edit your information. You could also buy or sell bitcoin directly through the web app, but since that wasn't the app's intended purpose, it stayed low on the page, almost below the fold.

They liked the idea, and we ran with it.

<img src="/img/glidera-casestudy5.jpg">

### mobile, too

At least in some abstract sense, an ideal onboarding process looks different on mobile from on a desktop. If Glidera was to optimize onboarding for mobile, too, their site couldn't just be a normal responsive site. It would have to "respond" into a format that felt almost native---like the best mobile sites.

Since mobile users constituted a significant proportion of their new signups, I spent time tailoring the mobile site experience to make it even better than the desktop equivalent. The end result split the setup steps across five different, super-simple screens, navigated horizontally like intro screens in a native app.

<img src="/img/glidera-casestudy6.png">

### the ui kit

The completed project consisted of a copy/paste-able UI kit, written with HTML/CSS/JS, including all the different front-end elements Glidera would need to build out the new web app, both for desktop and mobile browsers.

