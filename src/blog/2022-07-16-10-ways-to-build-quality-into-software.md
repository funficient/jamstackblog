---
title: 10 Ways to Build Quality Into Software
description: “Can Quality be built into software?” Ultimately, the level of
  quality in the software is a reflection of the level of responsibility within
  the organization. Own it. Don’t wait for someone else.  Quality is everyone's
  responsibility.
tags:
  - post
author: Kate Dames
date: 2019-02-19T10:28:45.912Z
image: /assets/blog/towfiqu-barbhuiya-0zuobtlw3y4-unsplash.jpg
imageAlt: Quality is an inside job.
canonical: https://funficient.medium.com/10-ways-to-build-quality-into-software-459726031fd5
---
## Exploring the possibilities of high-quality software

*“Can Quality be built into software?”*

*“Obviously yes!”* Was my answer to this question when posed at a Lean Coffee recently. In all honesty, I was surprised that this was even questioned. I thought the discussion would have been around *how* to build in quality, rather than questioning the *possibility* of whether it can be done or not.

Maybe it’s because I don’t think *anything* is impossible. Maybe it’s because my eyes start shining when I am presented with an obstacle *(I simply looovvvee solving problems)*.

![](https://miro.medium.com/max/800/1*YsdBDzWzsP8OjyrD_98bLA.gif)

Or maybe, it’s because I have a strong background in Quality Management — not to be confused with QA or Testing — and might assume a lot of things that might not be so obvious.

Many people think of software testing when they think of Quality, but testing is but one of many ways of *assuring* quality, with quality assurance one of the four main components of [Quality Management](https://en.wikipedia.org/wiki/Quality_management). Quality is much bigger than testing only.

> Quality is essentially about meeting user expectations. Consistently. Reliably. Confidently.

It’s not better. It’s not bigger. It’s not more. **It’s considered quality if you get what you asked for.** No buts or small print or nasty surprises once you’re hooked in. No fancy features and bells and whistles you didn’t ask for or need.

> ***Quality is when it’s just enough.*** It’s good enough if it does what you asked for explicitly. It’s *delightful* if it does what you asked for **and** fulfill your unspoken needs. It becomes annoying when it does more or less than what you need to meet your goal. **Quality is the mother of Productivity.**

Essentially, Quality Management is a customer-centered approach to process improvement. The Quality Manager is the custodian of the organization’s *processes*. All of them. Development, Testing, Project Management, HR, Finance. Everything.

The heart of Quality Management is the well-known P-D-C-A cycle of Plan, Do, Check, Act, also inherently part of the Scrum process with it’s Sprint Planning *(Plan)*, typical 2–week Sprints *(Do)*, Review *(Check)* and Retrospective *(Act)*.

# Building Quality In

When looking at quality from a testing perspective, I would agree that it is not possible to build software quality in. To build quality in you need to look at the bigger picture.

There are many ways to *improve* quality. It all depends on the problem. Maybe, you can automate something that previously had to be done by a human being. Maybe, you need training to better use the tools you have. Maybe you need to find a better tool to do the job. Or maybe, you need a checklist to remind you of what you need to look at. The possibilities are endless.

That’s not what I’m talking about when I talk about building quality in. Building in quality requires a more general, big-picture approach. Here are a few guidelines I consistently use to consistently build quality into software:

## 1. Slow down to speed up

When you drive at 60km per hour in the Kruger Park — one of the worlds biggest and best game reserves and close to my home town while growing up — you’ll probably miss the majestic elephant grazing behind a tree, or the lion gazing in the sun, or the leopard observing its prey from the tree tops.

It feels impossible to miss such majestic animals that’s only a few feet away. Yet, we nearly drove into an elephant once because we literally didn’t see it until I was a meter or two away.

I didn’t see this massive animal for the same reason errors in software remains undiscovered until a user finds it. One — we weren’t expecting it. Two — we were going too fast (45km per hour), on our way to the resting camp after a long morning of searching for game.

> You either do it fast, or thoroughly.

Do it fast and fix it later. Or do it slow and you don’t have to fix it at all. What’s more important? Short-term gains or long-term profits?

Rule number one when it comes to building in quality is to go slow. Give ***all*** your attention to what you are doing and do it slowly, and thoroughly. It might feel counter-productive in the short term, but it ends up being much faster doing it slowly once, compared to two or more times redoing the same thing fast.

## 2. Keep the user in mind at all times

This sounds obvious, yet, the biggest cause of bad quality software (in my opinion) is that we often forget who we’re building the software for.

I’ve witnessed first hand how requirements, designs and code were all completely done (and working well) just to discover it’s in the wrong application and for the wrong user, thus rendering it null and void.

The requirements were good quality, with designs and code to match, but everyone was so entrenched in the intricacies of the function that they forgot who it was intended for. No-one noticed it was developed in the wrong application until right at the end.

> The story isn’t done until the *right* user can use it.

A more frequent example of the user being forgotten during the development process is missing requirements. The things that weren’t built, but should have been.

The solution? *Involve the user.*

In game design an iterative design process is followed. A prototype is built and then undergoes play-testing. Real users are asked to play the game and based on their feedback, the design is adapted, until there’s a design that delights.

In many software development environments, we’re not there yet. The requirements or user stories are compiled by a Product Owner who spends more time explaining stories to the team than what they spend with the customer validating their ideas or discovering needs.

*Thank goodness for **The Lean Startup** being thrown into the mix!*

We arrogantly believe we solved the right problem with the user first seeing it *after* it’s built and tested. We also stubbornly believe that running tests on the back-end produces the same results as using it from the front-end.

Ultimately, quality is about user expectations and fulfilling *their* needs. If you don’t involve the user from the word go, chances are you’re not going to get it right. Involve the actual users more, earlier. Validate your ideas and spend as much (or more) time with the customers than what you do with the team.

## 3. Focus on the integration points

Developers usually work on an isolated piece of software or a specific function. A part of a bigger machine. They make sure that the new or changed function works as intended, assuming that the unchanged parts remain working.

Yet, more often than not, it doesn’t. Just like a a pipe in the plumbing will tend to break where it connects to other parts, so too software tends to break where it connects to other parts of the same system, or other systems.

*Integration is probably the biggest cause for coding errors, understandably.*

To solve integration issues, define end-to-end acceptance criteria upfront, based on actual user workflows. A user never does just one, isolated, thing. They follow a sequence of events. They log in, then add a new user, then view the new report. They never *only* view the report.

**Unit tests are not enough.** It will prove that the software is working, but not that it is working correctly with all the other parts, or that it was the right software to build in the first place.

## 4. Make it visible

Ever come across a defect that was rejected or closed (or worse, not even logged) because it couldn’t be reproduced?

The solution to this problem? Make it visible.

What you can see, you can fix. And the biggest benefit of software is that whatever you want to know, you can.

If you’re a lazy developer (and hopefully you are, otherwise you might be in the wrong industry), spend time adding valuable logging (balancing it with the performance cost as a result of the logging) and breakpoints at strategic points to slow down the execution process. Or, add (temporary) user feedback to indicate the state of a program to isolate an issue. It will cost you a few hours and save you weeks of debugging.

And if you’re really clever (aka really lazy), you’ll build in a switch to switch logging on and off on demand.

## 5. Error handling for humans

Ever run software and ran into a run-time error or something that looks like error code X87378xxx088788? Ever knew what it meant? Probably not. But don’t feel bad, the person who wrote it probably also doesn’t know.

![](https://miro.medium.com/max/1040/1*5OfXrqbI1oKGgEdl9KezDQ.jpeg)

*Source: [Magnt](http://magnt.com/404/) as obtained from [The Next Web](https://thenextweb.com/dd/2015/04/21/the-art-of-error-12-clever-404-pages/).*

If you’re human, you can be sure that you didn’t think of everything. There will be errors. That’s ok. But how do you handle it?

The fastest, and most productive, way to solve errors is to translate it into something useful that will enable someone to fix it (or at least reproduce it).

It might be a generic message like this 404 page, or something a bit more descriptive, but it does tell you what’s wrong and what to do next.

When you code, think one step ahead. *What would the next person need to understand this without having to bug me?*

## 6. Stop and fix errors when they’re found

If you’re familiar with the words ***‘Done-done’***, you’re guilty of not following this guideline.

The intention of the Definition of Done is to give an explicit guideline as to what criteria needs to be met for a story to be considered ready to be used by a *real* customer in the *real* world. If you are creating a list of bugs planning to fix it later, possibly even in a different sprint, you’re exponentially increasing the cost of the errors and reducing the quality of the software.

When an error is discovered, either by the developer or someone else, regardless of their role, report and fix it ***as soon as possible***. Now is good. Now-now is acceptable. Tomorrow doesn’t cut it. You only need to log it if you need to remember it. The longer you wait the harder and more expensive it gets to fix, and no-one likes to redo the same work over and over again.

> *Done means done. End of story.*

Don’t accept commonly accepted levels of errors.

## 7. Prevent it from occurring again

When, in the world of Quality, a non-conformance (anything that is not as expected) is discovered, two things *always* need to happen. The first is to fix the immediate problem as discussed in the previous point, also called the *corrective action*. The second it to prevent a similar issue from happening again, called *preventative action*.

Fixing a bug is part of the solution, however, it’s a short-term and unsustainable solution. What are you doing to prevent it from happening again?

Do a fault root analysis to uncover what caused the problem from happening in the first place and put a measure in place to prevent it from happening again.

There are a million ways to prevent issues, just as there are a million ways to improve quality, with one of the more common solutions to include test automation. However, take into consider the price of automation. You can’t, and shouldn’t, automate everything. **The more you automate the more you need to maintain, the slower it gets. *Is it worth the investment?***

*For a strategy and step-by-step approach following the 20/80 Pareto principle in test automation, read [A Lean Approach To Automation Testing](https://medium.com/teal-times/a-lean-approach-to-automation-testing-ad6fcdcf41e3).*

## 8. Reduce the noise

If there is one company that got this guideline right, it’s Apple. Microsoft and Android and Google and most companies out there focus on ***more***. More features. More options. More users. Apple, in contrast, focuses on how *little* they can do. What can they take away without negatively impacting the user experience?

The result? People love Apple. So much so that they wrote a love song to Apple years ago.

[FAttY SPiNS - Apple Store Love Song](https://cdn.embedly.com/widgets/media.html?src=https%3A%2F%2Fwww.youtube.com%2Fembed%2FeVmvBnNS7Tw%3Ffeature%3Doembed&url=http%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DeVmvBnNS7Tw&image=https%3A%2F%2Fi.ytimg.com%2Fvi%2FeVmvBnNS7Tw%2Fhqdefault.jpg&key=a19fcc184b9711e1b4764040d3dc5c07&type=text%2Fhtml&schema=youtube)

> Good design is simple. Good design is also good quality.

Focus on what you can remove to make the core function stand out better. It’s only useful if you can find it.

## 9. Reduce. Re-use. Recycle.

On a similar note, but from the developer, rather than user perspective, focus on maintainability. There is no use having all those genius resources hidden away in a code repository that no-one can find when they’re looking for it (and that’s also the reason why a public Github repository is not unsafe).

*Pre-written code only becomes an asset when you can re-use it. You can only re-use it if you can find it and understand what it is intended to do.*

A code base is organic. Factor in time for rewriting code and cleaning up code, just like you would spring clean your house regularly or clean up your desk. Don’t wait for it to become a problem, pro-actively clean it up.

Use standard naming conventions that your grandmother can understand and include comments for dummies. You already know what the code intends to do. Explain it to convince someone else to use it (or not break it when they think they’re fixing it).

## 10. Don’t rely on someone else to discover errors

> Re-spon-si-bi-li-ty — The ability to respond when you see something out of place or something that needs attention.

Just because it’s not your job, doesn’t mean you shouldn’t be responsible. If you see something wrong, do something about it. If you can fix it, do it. Immediately. If you can’t, tell someone who can.

The sooner you discover an error, the sooner you can fix it, the cheaper and faster it is.

# What are you waiting for?

Ultimately, the level of quality in the software is a reflection of the level of responsibility within the organization. Own it. Don’t wait for someone else.

Respond. React. Change. Now.





*Originally published on Medium: https://funficient.medium.com/10-ways-to-build-quality-into-software-459726031fd5*