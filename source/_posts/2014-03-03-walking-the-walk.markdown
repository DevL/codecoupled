---
layout: post
title: "Walking the walk"
date: 2014-03-03 22:30:00 +0100
comments: false
categories: [Mob programming, Agile]
author: Lennart Fridén
published: false
---

## Week 1

### Monday morning, weekly planning meeting
_\- How about mob programming[^1] this on Wednesday?_

Over the past few weeks, the team had worked in pairs on separate parts of a new system. However, the previous week had been interrupted by illness and meetings so I felt we had to pool our collective knowledge in order to grasp where we were and where we were heading. Thus, we set aside a day intent on bringing everyone up to speed.

The days before the scheduled mob programming session seemed to me ever so slow. I didn't feel exceptionally motivated in general and despite my best intentions I never took the initative to pair program. Pleasently enough I was ambushed by our most recent addition to the team with a "I'm going to pair with you now". It's really not more difficult than that. 

### Wednesday, first day of mob programming
We got going at around 10 o'clock as that's when the entire team can be expected to be in the office. The morning was used to go through the various parts we already had, taking note of missing or poorly understood pieces and tasks. Most importantly, we settled on a bare minimum of things that had to be done before we could reach something shippable. Just before lunch we got started on the actual mob programming. A conference room, a beamer, a computer, and someone making sure that the driver was swapped every fifteen minutes. It doesn't take more than that to start.

Shortly after lunch, one of us had to leave early, and as would be shown over and over again during our mob programming sessions, here's when one of mob programming's greatest strengths comes into play. Had the abscent team member being working alone on a task, the work would simply stop. Mob programming mitigates this problem as the rest of the mob simply continues working. It's similar to what would happen in a pair programming session, except that there's practially no degradation in performace. Phrased differently, if pair programming is RAID 1, mob programming is RAID 5 with spare disks[^2].

_\- So how did this feel?_

At the end of the day we had made some progress, primarily in understanding where we were and where we were going. We held a short restrospective to gauge what the team though of the day. Unanimously we agreed to continue the next day.

### Thursday, second day of mob programming

The second day went smoother than the first day. We continued to be a team member short, but that didn't stop us. Just like the day before, we held a brief retrospective. Just like the day before, we agreed to continue the next day. Though no-one questioned mob programming being effective given our set goals, the question regarding efficency was raised. I certainly don't have a definitive answer, but to me there are so many more aspects to factor in than those that can be directly measured and quantified.

For example, of all my experiences during our mob programming experiment, this day held the most surprising one of them all. Walking home from the commuter train it struck me that I generally liked my team better. Not that I didn't like each and everyone before, I just liked them _more_ after _continously_ working together.

### Friday, third day of mob programming

At this point, we had really gotten into rythm of mob programming. We concluded the week with a slightly longer retrospective and hesitantly I spoke my heart's desire.

{% img left http://i948.photobucket.com/albums/ad326/DevLCSC/Codecoupled/IMG_1812_zpsfd729abf.jpg 390 At the end of the first week %}

_\- Well, since there's work still left to be done and the office will be mostly vacant next week, thus freeing up the conference room, how about extending this experiment to all of next week?_

The resounding "yes" and "let's finish what we've started" I got in response almost made me wish that the weekend would pass swiftly. I took heart in that the following week would be one of mob programming.

Because the team chose to.

## Week 2

### Monday, fourth day of mob programming

_\- We don't need to open a pull request._

Over the weekend a team member fell ill, but we regained another so on the whole the mob remained four strong. One of the first things pointed out to us by the returning team member was that we really didn't have to use a feature branch as there was no branching going on, especially as the new app was yet to be deployed to production.

The weekly planning meeting had us pause the ongoing work in favour of a number of smaller, but higher priority, tasks. Admittedly, for two of these, the mob turned out to be overkill and in hindsight we would probably have been better served by splitting off one or two team members to tackle the smaller tasks while keeping the mob focused on the main task. Nevertheless, it was a valuable learning experience to handle even these simple tasks as a mob.

In the afternoon, following a failed ice cream break turned into a coffee break, an iOS developer sat in out of curiosity just as we touched upon something that required his input. While it's not a particular property of mob programming itself, being able to pick a stake holders' brain directly while working is not be underestimated.

### Tuesday, fifth day of mob programming

Tuesday saw us returning to the main task in earnest. The day started slowly with various technical hickups during setup, wasting time. In hindsight, I cannot stress the value of having a good setup when mob programming, but at the time we deemed what we had to be good enough for the experiment.

During the daily retrospective the concern that compared to when pair programming, it took longer time to agree on what to focus on and make decisions. The counter point was made that consensus is worth taking time and that any decision thusly made would be stronger.

In the end we settled on the person in front of the keyboard being the tie breaker.

### Wednesday, sixth day of mob programming

{% img right http://i948.photobucket.com/albums/ad326/DevLCSC/Codecoupled/IMG_1825_zps397aea7c.jpg 288 Rotations %}

Despite another round of technical problems and fiddling with editor themes to make the code visible enough we made good progress and got no fewer than twenty rotations done. The format of taking timed turns at the keyboard, rotating through the entire mob, rather than the usual ping-pong pair programming style we're accustomed to did not impress everyone.

_\- I feel I get to code to little, it's hard to stay focused on the main task, and frankly, that's a bit boring._

_\- I was like that last week, but I've gotten better. I can't say that will be the case for you too._

The exchange[^3] between two of my team mates left me both heartend and disheartend. Without the entire team getting behind mob programming, I didn't see it happening much beyond the current experiment.

### Thursday, seventh day of mob programming

Even in a nearly empty office, you can't spirit away the entire backend team and occupy the main conference room without curious colleagues wondering what we were up to. Not only did I get to talk about what mob programming is about over lunch, but our marketing department snapped a few shots of the mob and asked a couple of questions intended for a report in our internal weekly news app[^4].

Such distractions aside, this day turned out to be very productive and even the most sceptical of us agreed that it had been a good day.

### Friday, eighth day of mob programming

Our last day of mob programming was also the first day we had the entire team present. The morning saw us testing and polishing what we had built. Even after a lengthy discussion and a longer break around lunch than usual we managed to complete an unplanned, but high priority task. As one of us had to leave early, we decided to postpone the overall mob programming retrospective until the week after. Of course, it turned out that another team member is on vacation then.

Bonus lesson learned: don't postpone retrospectives, rather have more of them if and as needed.

## Conclusions

Both Kim and I have previously tinkered and toyed with the concept of mob programming in various contexts[^5], but I feel that this was the first time I got to mob program _for real_. Working as a mob for a few hours or a day at most simply doesn't capture the many nuances and experiences that the past week and a half has brought me. 

After recapitulating the events of our mob programming experiment, what was the outcome? Will we continue mob programming? As I write these words, I've yet to find out for myself.

Personally, I wish I could say it was successful in convincing the team and beyond to keep mob programming more or less all the time. However, I have my doubts that will be the case. I do hope we will revisit the concept, adapt it in whatever manner needed to make sure we get the most out of it without having qualms over perceived efficiency and attention span get in the way.

Nevertheless I consider the experiment to be successful beyond my wildest expectations. It was successful in the sense that we got the job done. It was successful in the sense that we spread knowledge and shared insights about all the moving parts. It was successful in engaging and motivating the entire team to work closer together.

Above all, it was successful in the sense that we had fun together. At the end of the day, I can't think of higher praise to be given by a team than this:

_\- This was fun, let's do it again!_

{% img http://i948.photobucket.com/albums/ad326/DevLCSC/Codecoupled/IMG_1827_zps2ea09470.jpg?t=1393870040 The team with me behind the camera %}

[^1]: [An introduction to mobprogramming.org](http://mobprogramming.org/mob-programming-basics/)
[^2]: [Wikipedia on RAID](http://en.wikipedia.org/wiki/RAID).
[^3]: Somewhat paraphrased and abbreviated, but accurate enough.
[^4]: You don't expect a [company building a publishing platform](http://www.magplus.com) to use email for its internal newsletter, do you?
[^5]: See [Mob Refactoring](/blog/2014/02/01/mob-refactoring/) for a record of Kim's experience at her work.
