---
title: Testing complex systems with play
description: If your system under test is too complex or complicated to
  adequately cover with test cases, or if there are simply too many variables to
  test within limited timeframes, consider adding playful test to your test
  strategy.  This post looks at a structured approach to playtest complex
  systems.
tags:
  - post
  - featured
  - process
author: Kate Dames
date: 2020-07-10T18:21:24.409Z
image: /assets/blog/pexels-amina-filkins-5561177.jpg
imageAlt: Sometimes traditional methods just don't do.
canonical: https://medium.com/teal-times/testing-complex-systems-with-play-122760e03d00
---

## Accelerated results with playful design

I’ve been testing software for a long time. In fact, my first job was as a tester. In an industry where it evolves faster than what it is possible to keep up with, I wouldn’t consider myself — or anyone as a matter of fact — as a master in software testing, but I have completed the 10, 000 hours of mastery required to qualify me as, at least, competent in the art of software testing.

Over the years I’ve seen testing being more integrated into the developer role with Test Driven Development and I remember the great relief and freedom that exploratory testing brought to the industry. Then there was the introduction of crowd sourced testing which solved the problem of configuration related issues, but it comes at a high cost and doesn’t guarantee issues to be identified.

Other than that, the field of software testing has changed very little over the past decade, while the complexity of what we’re testing has increased exponentially.

## A short history of everything

Testing was easy back when the methods were created. A detailed requirements specification was the baseline from which you drew up a detailed test plan. You then executed each step of the plan meticulously in sequence until completion.

O, the good old days when things were simple…

Systems had clear boundaries as integration wasn’t common. It was a safe little black box that you had full control over and a methodical test plan was a very good idea.

There were little to no competition with mostly niche markets paying a premium for automating a part of their value chain specific to their needs. The users’ primary roles were to input data into the system. Catering for multiple use cases for a single function was not common. Rather, the software developers told the users how to use the system. In fact, there was full training courses developed to teach users how to use complicated systems.

But then came commercial internet, the Google app store and MOOCs which allowed anyone to build any piece of software and make it accessible to the entire world. On top of that open-source became popular and choices became abundant. You no longer had to pay expensive premiums to use software as there were an abundance of free or lower costed options available.

And then, of course, the shadow side of software emerged with a growing competition to own data with Google and Facebook at the fore-front. Their solution to owning the data was simple — control the log-in point. API’s to handle log-in and as a result access to other user data was introduced and integration became a user expectation. If you wanted to compete you had to integrate to the big players. Which is great for the users and the data gathers on the other side, but terrible for the software developers who no longer had full control over what they were building.

Testers were suddenly overwhelmed with all the possible permutations to include in any user test and quality eroded despite the longer hours and more fancy tools to automate part of the process.

## Complicating complexity

Suddenly, test planning and design had to take into consideration different devices and configurations far beyond anyone’s control. Integrations and personalization further added to the already complex systems making it impossible to use the existing software testing methods to ensure coverage.

Where a decision table to plot the possible test cases were a great tool to ensure coverage, now a decision table is inadequate for even a small step such as onboarding. The number of permutations and variables are simply too many. You have to test self sign-up as persona type one, two and three; self sign-up via invite from persona one, two and three; self sign-up with an existing invite active; sign-up with multiple invites pending from different invitees; sign-up using facebook, google, twitter, email, phone, different types of phones, different browsers, different locations….

You catch my drift.

And that’s just sign up. A mere _prerequisite_ to actually using your system.\
Even if you do have unlimited budget and can afford to add more and more testers, by the time they would finish the planned tests the market place would have shifted so much that your solution would no longer be a fit for what it was designed for.

_So what do you do?_

You could scream and pull out your hair while throwing around your weight as test manager demanding more from your already overworked testers. And it might even work for a short while.

But you don’t use a hammer to fasten a screw and you don’t use a muffin tray to bake a bread. So what if there was a better, easier tool to test complex systems with?

> “The creation of something new is not accomplished by the intellect but by the play instinct.” — Carl Jung

# Playtest or Playful test?

In gaming the word used for the equivalent of validation or acceptance testing is called _“playtesting”_. When I first heard that word, I was immediately intrigued. _Playtest?_

Being very interested in play mechanics and using play as a tool to engage and motivate teams, I explored a bit more. What I discovered is that it’s nothing other than acceptance testing with the difference being the attitude of the player and the involvement of the developer. It’s effectively blending functional testing and usability testing into a single iteration of test.

Makes sense.

However, it lacked the element of play I was so interested in, except for the fact that you were testing a game rather than more serious work. So I invented my own playful test method by adding an element of play onto all the most effective test methods out there — namely exploratory testing, mob testing and of course, usability — or play — testing. After all, if it’s not a good user experience, nothing else really matters.

# Let’s play

## Context and Prerequisites

Playful test can be used for anything, but is ideal for overly complex and complicated system design. When you have different devices, different personas each with their own dashboards, with a lot of variables and many to many relationships between different users or elements within the system, playful test outshines other methods.

For example, a rental agent management app has different functionality and information displayed on interfaces designed for tenants, agents or home owners. Each interface is in effect a separate system, with the user experiencing it as one integrated system. The platform allows each persona to have an optional and many-to-many relationship with a property. A tenant might, for example, be invited to join the system by a rental agent and a landlord at the same time. Or a tenant might sign up themselves and be an active tenant as well as a landlord. A property can be listed by multiple agents and the owner. Once signed up, there is a number of possible actions that can be performed in no specific order. In fact, all most of the rules can be broken in some way. A property can be occupied and available for potential tenants to view at the same time. A rental agreement can be terminated early, even though contractually there is a specified termination date. An agent can manage another agent’s property (or not). The list goes on.

> When the requirements are fuzzy and the variables too many to list on a decision table, it’s time to play.

# Setting up the play-test

Playful test follows the basic rules of testing. Determine a strategy, spend some time planning what and how to test, execute and report. The main difference in test planning is that there are no set sequence as in traditional planning with one test case following the next. Rather, it can be seen as playing with lego where each piece can be used to build something different.

The first step is to create the different building blocks.

## Step 1 — Pick a personality

On small index cards, write the different persona types adding an adjective to describe the personality. For example the angry tenant, the snobbish agent, the busy landlord.

Adding an adjective gives more context to a user. It describes how they will interact with the system and what their unique needs will be. An angry tenant might be impatient in getting a response. A snobbish agent might be more pedantic in finding issues when doing an inspection, and a busy landlord might want to bypass parts of the workflow or do an action in a more efficient way than an agent.

The adjective is also the _invitation_ to play.

But that’s all it is.

An _invitation_.

> There’s no such thing as forced fun.

It’s up to the participants to accept or reject this invitation freely and without any repercussion. A more playful tester might, for example, immerse himself totally into this role, actively role-playing as a different persona to his usual personality. Another tester might not feel comfortable role-playing and simply act his normal self without any playfulness.

Most teams are not ready to be playful if they’re used to a management and control type of environment. To be ready for play there needs to be a strong foundation of trust. To learn more about the prerequisites for play read [The Rules of Play](https://medium.com/teal-times/the-rules-of-play-a6109c363b3a).

Create at least two cards more than all the participants to allow each person a choice but will ensure coverage.

## Step 2 — Define test scenario’s and objectives

Next, based on the functions within the system, write down test objectives — one per index card — for each scenario as you would in a usability test setting. Be sure to keep the objective cards separate from the persona cards.\
For example, a tenant might want to search for a new home, or report an issue, or give notice. An agent wants to renew a lease, terminate a lease or do a credit check on a prospective new tenant. A landlord might want to list a new property, sign up a new tenant, or resolve a maintenance request.\
For a complete user experience evaluation, consider using the Game Thinking framework to help define all scenarios.

![](https://miro.medium.com/max/1400/1*HXlOQhRthKpq4rH33hgnuQ.jpeg)

Low-tech is always more agile.

Order and group these into small related groups and place them face down. For example, keep all sign-up and login related cases in one pile, all agent cases to list a property in another, cases to sign a lease in yet another, etc.

These cards will be your main play cards during the play phase with players randomly picking a test objective to perform.

Probably the most basic rule of play is the concept of randomness. To create a more playful, and more realistic, test plan, add random events on index cards and shuffle them into the main test object cards. Include an element of fun by adding, for example, a geyser burst, you got a job offer abroad and need to terminate your lease agreement early, or you — as agent — might resign and have to hand over your properties to someone else.

## Step 3 — Team setup

Once you’ve prepared all the different index cards, **_it’s time to play!_**

Get the team together, consisting of at least the developers, business analysts, designers and testers. Ideally, include a customer proxy and some third party users who has no relationship with the system. Aim for a representative, cross-functional team.

Break the group into 3–5 players per group and let each player pick a random role, ensuring each persona is represented per group. For example, each group has to have at least one tenant, while another might have 3 tenants and no landlord, or a landlord and agent etc.

Allocate different devices to different players and request them to use different browsers, representative of the test plan. One player might use a Windows laptop using Chrome, another an iPad, yet another a mobile phone with Opera as browser.

Make sure each device has screen capturing and recording software pre-installed and everyone knows how to use it.

## Step 4 — Play time

Once all the logistics are sorted and everyone knows what to do, it’s time to play.

Assign a persona personality card and explain how to play. For larger groups consider splitting the group into players and observers, with the observers responsibility for observing the players as they play and making notes and logging bugs as they occur.

With all the scenario cards face down, let each player pick a card from the top of the pile and complete the test objective, while the scribe (and game master) walks around making notes and observing. Each player attempts to complete their test objective taking annotated screendumps or screen recordings where issues are discovered.

Don’t spend too much time on bug reporting, rather, get just enough information or record the entire session to allow for an uninterrupted play session.

## Step 5 — Retrospective and closure

Once all the cards are finished, or when there has been sufficient bugs logged, wrap up the test session. In a round-robin fashion, ask for feedback and insights gained during the play.

Consider adding a target on a whiteboard for players to plot their perspective of system readiness and ask for advice on where they feel attention is needed or what the next steps should be.

# The rules of the game

The key to a playful experience is to provide enough structure to create an immersive experience while leaving adequate room for exploration and play.

If your system under test is too complex or complicated to adequately cover with test cases, or if there are simply too many variables to test within limited timeframes, consider adding playful test to your test strategy.

_Read more about play and playful design or visit [www.funficient.com](http://www.funficient.com) :_

_[The rules of play](https://medium.com/teal-times/the-rules-of-play-a6109c363b3a)_

_[Design better products with Game Thinking](https://uxdesign.cc/design-better-products-with-game-thinking-3cde5ce21c26)_

_[The top 10 ingredients of fun](https://medium.com/teal-times/top-10-ingredients-of-fun-b9b14b82f1d6)_

Originally written at https://medium.com/teal-times/testing-complex-systems-with-play-122760e03d00
