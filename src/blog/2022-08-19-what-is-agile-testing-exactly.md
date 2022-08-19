---
title: What is Agile Testing exactly?
description: Testing is an art.  It's the art of uncovering weaknesses in
  software.  Here's a bullet proof strategy to make sure you're finding
  meaningful errors while testing software.
tags:
  - post
  - process
author: Kate Dames
date: 2017-07-12T10:36:55.765Z
image: /assets/blog/thisisengineering-raeng-_pdobi2xhky-unsplash-1-.jpg
imageAlt: Testing software is an art.
canonical: https://medium.com/teal-times/what-is-agile-testing-exactly-1dabb7f09e8
---
## Exploring the agility of a tester

In a recent [blog on defining agile testing](http://agiletester.ca/definition-agile-testing) by Lisa Crispin and Janet Gregory, some of the most respected authorities in software testing, they attempted to define agile testing.

Of course they did a great job to condense the essence into a short paragraph, yet I felt that defining “agile testing” shouldn’t be necessary, just like you wouldn’t bother defining “blue table”. The difference between a table and a blue table is merely its color. So too the difference between testing and agile testing is simply how you test and the mindset. Defining a term in itself to me feels a bit un-agile and left me feeling sad and misunderstood. The same feeling I had when writing a post on my personal testing journey in a blog called [The Good, The Bad and The Ugly of Agile Testing](https://everydayagile.com/the-good-the-bad-and-the-ugly-about-agile-testing-29b4b847c778).

# A step-by-step guide to the art of “agile” testing

So I decided to share how I test, or used to test and who knows, maybe will continue to in the future. I invite you to try it out for yourself and make up your own mind.

I view testing as the art of evaluating a user experience. I don’t separate UX and testing and merge the two into one, viewing testing from as many viewpoints as what is necessary to produce a whole, working system. Working meaning that it solves a problem, not that there are a bunch of features which behaves as expectedly in isolation.

For simplicity, I’ll use a digital marketing service provider website as baseline for explanation. A system is, however, no different than a simple website, except that I would possibly include more tools in my test planning, like drawing a context diagram, depending on the complexity. The process however remains much the same, except that it might be phased into smaller parts.

## Step 1: Understand what the offering is about

I usually start off with asking for only a url and analytics reports, if available. When the odd customer sends me a list of test cases, I usually ignore it until right at the end.

It’s counter productive asking me to evaluate something when you are going to tell me what to do. It’s kind of like hiring a gardener because you know nothing about gardening but then continue to tell him exactly which plants to buy and where to plant them, and then be surprised when the plants don’t grow. You hire the gardener for their expertise, so for the best results, leave it to the gardener to figure out which plants will go where, what soil is needed and how much water the plants should get.

I also don’t spend any time with the customer to get a brief as this already influences my thinking away from what a customer would think and experience the interaction. *The reason for investing in testing is to get an objective opinion regarding the readiness of the system or website for use in production. When the tester tries to please the employer, which more often happens than what I’d like to admit, it merely provides a false sense of safety.* It’s not really valuable hearing what you want to hear but no customers are clicking. You need to know why customers aren’t clicking so that you can do something about it. So the tester needs to wear the customer hat and be as far removed from the internal business politics as much as possible in order to stay objective and valuable.

I spend about a day going through the website and making a mindmap of all the different functions that’s available by systematically working through each and every page to see where they fit into the puzzle and what is available. This is kind of like reverse engineering, creating an object-oriented design of the system so that I don’t waste time retesting the same function unnecessary as the same code is re-used in different parts.

This also serves as my rough test plan to make sure I look at the complete picture. It’s a loose set of scribbles on a few pieces of paper and it never gets translated into a formal test plan or strategy.

The focus is to look at what **functions** are available and whether all the links navigate to the intended location. In the example of the digital marketing website, some functions might be signing up, setting up your profile, buying credits, using credits by submitting a request for adding a blog post, or SEO, cancelling a request and changing my website url. Traditional ways of testing only does this in great detail. I spend only enough time to know what the scope is and what the product or service offering is. I never write any detailed test cases, except when working with an intern or when developers need more guidance.

When I’m unclear on what the offering is about, I spend time analysing **why** rather than go to the customer to clarify the intention. My thinking is that if it doesn’t make sense to me, it’s not going to make sense to the customer. I’m not looking for an explanation as to why this was the customer’s thinking, I’m looking at a solution as to how it can make more sense to a user.

I only go to the customer for clarification if there are clear discrepancies, for example the terms might specify one set of products while the website specifies another set. In this case, I would ask which one is correct before I continue to save time.

## Step 2: Profile the customers

Most of my test planning time I spend on this step, which is from my experience, totally omitted from testing effort in the ‘traditional’ testing way. I see this step as the most important as ultimately the system or website is designed for users, so the users should be at the center of the test design too.

The focus is to identify the different **personas** and identify their possible **needs** during each phase of the user journey.

Most websites cater for at least two distinct types of users, with the first being the end-user and the second a service persona. The users can also vary distinctly. For one website there might a very specific niche market of local users, for another it might be more broad and international personas.

It is crucial to understand what the geographic distribution of your users are as standards and expectations are different for different countries. For example, in Asia, red is associated with something auspicious or good luck and is the perfect color for a call-to-action button. In Western countries, red is associated with danger and will stop potential buyers from clicking the buy button merely because of the color. Asians read from right to left, Westerners from left to right.

This is a super fun activity for me as it reminds me of role play while in kindergarten, imagining myself as one type of user or another. I literally become the person while I go through the website searching for what **value** means to this user. Are they looking for easy? reliability? information? community?

The output of this phase is a user persona summary.

## Step 3: Compile a test plan

The focus of this step is to use the output from step 1 (the functions) and the output from step 2 (the questions and personas) to compile a sequence of challenges for a user to complete, based on actions and expected results. I focus on value and a complete solution, never testing one function in isolation, unless I’m trying to isolate a bug, but that’s a different topic for discussion.

I compile a list of questions that each user might ask during the different phases of their user journeys. I center the questionnaire from a user point of view, but use the list of functions as reference to ensure completeness and that each function is covered at least once. For example, a few questions a typical user might ask while evaluating a product might be:

1. Does the service scale with my business growth?
2. What are the different options? And what is the best fit for my business
3. What is included?
4. What about privacy and security?
5. What are the costs involved?

The website needs to give answers to these questions in some form or another. There is no correct answer, there is just valid questions, which is the opposite way of traditional testing, where the requirements are the bible that all answers must lead to. For example, security might be the use of https or it might be the inclusion of a badge from a service provider, or it might just be a link to how privacy is handled on the website as a text page. What is important is that the question can be answered, not how.

These questions are used as guide for exploratory testing later on. It’s important to compile the questions totally from a user perspective, as the main criticism I have for the traditional test approaches are that they are focused on *what is*, totally ignoring that *what should have* or *what could have been*.

In traditional testing, the gaps are never identified and the product owner is trusted to know what should and could have been there, thus there is a fundamental flaw in the traditional testing as it ignores any faults of the product owner, and in my experience, more issues are as a result of the requirements than the quality of code. Even when a requirement is logged as defect, ultimately the product owner is the one deciding with their limited view.

At this point, I send the test plan for review to the customer who can then point out any discrepancies or misunderstandings.

## Step 4: Select primary test device and tools

Once I know what to look for and how I’ll go about it, I spend a few hours going through the analytics reports to see which browsers, devices and operating systems are most popular to help me decide what my primary device for testing will be. Maybe the majority of the users are iPhone users, other times, the majority might be using Chrome browsers on a Windows desktop. Depending on the audience, I select my primary device, again different to the traditional test lab where the test machine is static.

I also look for tools to help me achieve my goal faster. I might include a broken link checker to make sure that there are not any broken links. Or I might include some kind of emulator depending on what I’m testing. Anything that can be done better with a tool, I search for, **but never, ever, EVER do I include a test automation tool. Ever.**

Automating tests while you’re validating a function is counter productive for the simple reason that you are focusing your attention on writing test scripts and not evaluating the feasibility of the offering anymore, and the human brain can only focus on one thing at a time. That is why changing perspectives are often a big challenge for testers and it’s a skill that needs to be developed, just like an actor needs to develop their acting skills. You can’t be a good actor if you always play the same role.

*Automating tests are also much more expensive and ultimately un-agile. The moment you have scripted a test, which takes much longer than manually checking it, any change requires a change in the script.* I haven’t done the calculations, but it is at least three times slower to do automation testing than manual testing and the amount of errors caught with automation compared to manual makes it simply not worth the effort to automate so early in the process. I’ve also seen more test automation tools slowing down the entire development cycle than supporting it with everything being automated.

Automation testing is good for regression testing, which only becomes valuable *after* you’ve tested the system and after the bugs have been fixed. It should be a snapshot of the ideal system and it’s far from ideal if you haven’t accepted the story yet. If you’re following Scrum, that means that you would only automate tests in a regression suite after the stories have been accepted by the product owner, which means it happens in the following sprint. Once it hasn’t been accepted, it simply doesn’t make any sense automating it.

If the purpose of regression testing is understood and manual testing done well, regression testing should only need to cover about 20% of the system functionality, which is not adequate at all when you haven’t tested a system yet.

When the developers are available, I usually also spend time with them to understand what they have already covered in their unit tests or automated tests to ensure that I don’t duplicate the effort and know where to focus my test effort. I thus need to understand the technical architecture on a basic level in order to focus my efforts most efficiently.

## Step 5: Run Exploratory Tests

Finally you’re ready to start testing. I usually take one persona and gradually work my way through the questions before changing to a different persona, as the switch in perspective requires focus.

While I’m running the test I focus mostly on the **usability** aspects of the website or system. How fast do I get my results once I have clicked the button? How easy is it to find the information I’m looking for? Are there any unnecessary steps that can be omitted? How much feedback do I get to help me as user feel in control at all times? How delightful is the interaction and how much detail is tended to in the design? How do the colors complement the message and the mood? How do the images and icons help to guide a user to the answers they are seeking?

Functional testing, in my opinion, is mostly already done by the developers with their unit tests and TDD. Thus, when I’m testing, mostly, I’m expecting that the functions will work and usually they do. If not, I spend more time with the developers and give them prepared test cases to improve their quality of work, which usually, they’re very grateful for. In the end, everyone wants to do the best job they possibly can and only need someone to explain the rules of the game to them. By giving them test cases, they know what you are looking for and they will build it into the system, which makes the life of the tester so much easier and shortens development time as less bugs are picked up later in the process.

The issues and value add I bring to the table is giving the feedback that the unit tests ***don’t*** cover, which usually involves the end-to-end running of a scenario rather than a standalone function or a missing requirement. *I would say that on average 80% of failures are as a result of either bad design or bad requirements, not bad code.* With design, I intend to mean both the aesthetic layout and the solution design itself.

For example, the debiting and crediting of credits might work fine in a unit test, but using it in a different workflow might point out a failure in the system. The integration points are the weak points in any system, thus it’s important to understand where technically the integrations are and what is being integrated.

I spend extra time making sure that the integration points work in different cases. Standard functionality, however, only need to be proven to work with one or two cases.

The list of questions is my checklist to make sure that a user can do everything that they intend to do and I work my way through it, logging bugs as I go along.

I use one primary test device, then swap to different devices to do different tests to make sure that the functionality and layouts behave the same on different sized screens and browsers. I get the same results with this approach and testing on all devices and all systems, thus opt for the time saving option.

## Step 6: The Test Report

This is the most fun part of testing as here is where my creativity gets to play. My test report usually covers a one or two pages with the functional test results and errors, and then about 20 or 30 pages of a usability review and feedback on how to make it a better user experience.

I start with consolidating and allocating a star rating for the overall feel, the usefulness and functionality, and the design and layout. It is followed with recommendations on how to improve the website or system, looking at the latest design trends and simply how to make it a more engaging experience for a user. I include a lot of screenshots to show examples of how it’s used elsewhere and how it can improve your user experience. I add to each item a rating to indicate whether it is an enhancement or something necessary to look at in order to stay competitive.

I comment on the use of colors, the readability, the layout of test and pages, basically all the little things that never gets tested in a traditional test lab. Usually, designs are done upfront and development must be according to the visual design, whether it makes sense to the end user or not. The design itself is never tested, or at least, not anywhere where I’ve worked as a tester.

Depending on the customer, I either run them through the report, but I find it best that they go through it themselves as usually there is a lot to process. It is then up to the customer to decide which advice they choose to implement, and which they are willing to live with and our merry ways part until the next website or system is required for testing.

I also make sure that when I log bugs I do it in such a way that it is reproducible and have all the information so that the developers don’t need to bug me for more details as I really dislike that. This often takes more time trying to isolate an issue, but allows the developer to quickly fix it and I find it the most efficient way to resolve issues and learn in the process. When the developer don’t have the luxury of simply asking the tester, it’s amazing how fast they learn and improve the quality of their code.



*Originally published on Medium: https://medium.com/teal-times/what-is-agile-testing-exactly-1dabb7f09e8*