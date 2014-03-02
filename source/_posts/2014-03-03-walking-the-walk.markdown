---
layout: post
title: "Walking the walk"
date: 2014-03-03 08:00:00 +0100
comments: false
categories: [Mob programming, Agile]
author: Lennart Fridén
published: false
---

### Monday morning, weekly planning meeting
_\- How about mob programming this on Wednesday?_

Over the past few weeks, the team had worked in pairs on separate parts of a new system. However, the previous week had been interrupted by illness and meetings so I felt that we had to pool our collective knowledge in order to grasp where we were and where we were heading. Thus, we set aside a day intent to bring everyone up to speed.

The days before the scheduled mob programming session me seemed to me ever so slow. I didn't feel exceptionally motivated in general and despite my intentions I never took the initative to pair program. Pleasently enough I was ambushed by our most recent addition to the team with a "I'm going to pair with you now". It's really not more difficult than that. 

### Wednesday, first day of mob programming
We got going at around 10 o'clock as that's when the entire team can be expected to be in the office. The morning was used to go through the various parts we already had, taking note of missing or poorly understood pieces and tasks. Most importantly, we settled on a bare minimum of things that had to be done before we could reach something shippable. Just before lunch we got started on the actual mob programming. A conference room, a beamer, a computer, and someone making sure that the driver was swapped every fifteen minutes. It doesn't take more than that to start.

Shortly after lunch, one of us had to leave early, and as would be shown over and over again during our mob programming sessions, here's when one of mob programming's greatest strengths comes into play. Had the abscent team member being working alone on a task, the work would simply stop. Mob programming mitigates this problem as the rest of the mob simply continues working. It's similar to what would happen in a pair programming session, except that there's practially no degradation in performace. Phrased differently, if pair programming is RAID 1, mob programming is RAID 5 with spare disks [^1].

_\- So how did this feel?_

At the end of the day we had made some progress, primarily in understanding where we were and where we were going. We held a short restrospective to gauge what the team though of the day. Unanimously we agreed to continue the next day.

### Thursday, second day of mob programming

The second day went smoother than the first day. We continued to be a team member short, but that didn't stop us. Just like the day before, we held a brief retrospective. Just like the day before, we agreed to continue the next day. Though no-one questioned mob programming being effective given our set goals, the question regarding efficency was raised. I certainly don't got a definitive answer, but to me there are so many more aspects to factor in than those that can be directly measured and quantified.

For example, of all my experiences during our mob programming experiment, this day held the most surprising one of them all. Walking home from the comuter train it struck me that I generally liked my team better. Not that I didn't like each and everyone before, I just liked them _more_ after _continously_ working together.

### Friday, third day of mob programming

At this point, we had really gotten into rythm of mob programming. We concluded the week with slightly longer retrospective and hesitantly I spoke my heart's desire.

_\- Well, since there's work still left to be done and the office will be mostly vacant next week, thus freeing up the conference room, how about extending this experiment to all of next week?_

The resounding "yes" and "let's finish what we've started" I got in response almost made me wish that the weekend would pass swiftly. I took heart in that the following week would be one of mob programming. Because the team chose to.

### Monday, fourth day of mob programming

_\- We don't need to open a pull request._

Over the weekend a team member fell ill, but we regained another so on the whole the mob remained four strong. One of the first things pointed out to us by the returning team member was that we really didn't have to use a feature branch as there was no branching going on, especially as the new app was yet to be deployed to production.

The weekly planning meeting had us pause the ongoing work in favour of a number of smaller, but higher priority tasks. Admittedly, for two out of these, the mob turned out to be overkill and in hindsight we would probably have been better served by splitting off one or two team members to tackle them while keeping the mob focused on the main task. Nevertheless, it was a valuable learning experience to handle even these simple tasks as a mob.

In the afternoon, following a failed ice cream break turned into a coffee break, an iOS developer sat in out of curiosity just as we touched upon something that required his input. While it's not a particular property of mob programming itself, being able to pick a stake holders' brain directly while working is not be underestimated.

### Tuesday, fifth day of mob programming

Tuesday saw us returning to the main task in earnest. The day started slowly with various technical hickups during setup wasting time. I can stress the value of having a good setup when mob programming, but at the time we deemed what we had good enough for the experiment.

During the daily retrospective the concern that compared to when pair programming, it took longer time to agree on what to focus on and make decisions. The counter point was made that consensus is worth taking time and that any decision thusly made would be stronger.

In the end we settled on the currently having the keyboard being the tie breaker.

### Wednesday, sixth day of mob programming

Despite another round of technical problems and fiddling with editor themes to make the code visible enough we made good progress and got no fewer than twenty rotations done. The format of taking timed turns at the keyboard, rotating through the entire mob, rather than the usual ping-pong pair programming style we're accustomed to did not impress everyone.

_\- I feel I get to code to little, it's hard to stay focused on the main task, and frankly, that's a bit boring._

_\- I was like that last week, but I've gotten better. I can't say that will be the case for you too._

The exchange [^2] between two of my team mates left me both heartend and disheartend. Without the entire team getting behind mob programming, I didn't see it happening much beyond the current experiment.

### Thursday, seventh day of mob programming

Even in a nearly empty office, you can't spirit away the entire backend team and occupy the main conference room without curious colleagues wondering what we were up to. Not only did I get to talk about what mob programming is about, but our marketing department snapped a few shots of the mob and asked a couple of questions for a report in our internal weekly morning report app [^3].

### Friday, eight day of mob programming

Our last day of mob programming was also the first day we had the entire team present. 

Friday: CSS, testing, final polishing of MVP. Lengthy discussion that in the end built consensus and resulted in another finished task.

[^1]: [Wikipedia on RAID](http://en.wikipedia.org/wiki/RAID).
[^2]: Somewhat paraphrased and abbreviated, but accurate enough.
[^3]: You don't expect a company building a publishing platform to use email for its internal newsletter, do you?
