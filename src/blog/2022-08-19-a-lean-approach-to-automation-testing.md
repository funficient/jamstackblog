---
title: A Lean Approach to Automation Testing
description: Automation is an insurance policy.  First, you have to make sure
  that you have a product worth insuring before you start investing in the
  premiums.  Here's a leanapproach to automation testing.
tags:
  - post
  - process
author: Kate Dames
date: 2017-07-20T10:16:35.733Z
image: /assets/blog/alex-knight-2ejcsulrwc8-unsplash-1-.jpg
imageAlt: Automation is an insurance policy.
canonical: https://medium.com/teal-times/a-lean-approach-to-automation-testing-ad6fcdcf41e3
---
## A test strategy process defined

In a previous post I looked at [**what** agile testing is](https://medium.com/@funficient/what-is-agile-testing-exactly-1dabb7f09e8) after commenting on a discussion by [Lisa Crispin](https://medium.com/u/a59f796c6fc6?source=post_page-----ad6fcdcf41e3--------------------------------) and [Janet Gregory](https://medium.com/u/e4cbf86c42e8?source=post_page-----ad6fcdcf41e3--------------------------------) on [defining a definition for agile testing](http://agiletester.ca/definition-agile-testing/). My view is that (functional end-to-end) automating too soon is not agile. To be really agile, manual testing is by far the fastest and most flexible in most cases. This post aims to drill into **how** I automate and what to include and exclude.  It focuses on validation testing from an end-user perspective.

In essence, I view automation as an insurance policy. It makes sure that the software still works the way it was intended to work when other parts of the system has changed. Once I’ve automated a part of the system, I trust that it does the testing and I don’t have to look at it anymore, allowing me to focus my full attention on the new bits and pieces that were added.

## The strengths and constraints of automation

*As with all things in life, nothing is perfect. Just like you wouldn’t use a pasta machine to make cookies, so too you pick the right tool or technique to get the most out of the testing experience. That means knowing what humans are good at and their constraints, and what automation is good at and its constraints.*

Humans are good at spotting discrepancies. They are also good at figuring out *why* something isn’t working or *where* the error lies. Technology, however, is much better at repeating the same work over and over and over and over again. Where humans get bored and distracted and accustomed to what is in front of them, technology thrives when able to repeat the same thing over and over again. When a human is asked to do the same task over and over again though, chances are high that they will miss errors.

Technology is thus an excellent partner to take over everything that becomes boring to a human being after it’s been proven to be stable. It is however expensive and inflexible. In order to change a test, you need to change the tool, which is inherently much slower than a human being simply checking something manually. The more tests you add, the more resources you need, but everything is double the cost as you have to pay for the hardware and possible software licenses as well as the human being managing it.

Technology also becomes unmanageable very soon when *everything* is being automated, which often tends to be the case. Soon it takes longer to run the automated tests and get the results than simply doing it manually. In my opinion, it’s of little value having an automation test but not being able to get results on demand. It’s like having a health insurance policy but when you have to go to hospital for an emergency treatment, they tell you that they can only help you in a few weeks’ time. You need the treatment now in order to stay alive and the insurance policy means nothing if it doesn’t give you the re-assurance that it is intended to give and what you signed up for.

Trying to make sense of the automated tests becomes increasingly harder the more tests are added, meaning it takes more and more time for the engineer to find the right tests and update all the relevant tests with each change to the system.

Technology also only does what it’s told. It doesn’t find an error when it hasn’t been automated whereas a human being would more easily be able to spot a new bug that was introduced.

Finally, users do things differently. Everyone has slightly different preferences, settings and work flows and not all transactions require the same workflow. It’s impossible (or at least impractical) to test all the different combinations, and thus impractical to automate it all. Technology looks at exactly the same work flows and data every time, so any work flow or accidental click that happens in real life, is omitted when only automating.

Automation is thus really good for stable parts of the system which is used often and in a repeatable way.

# An automation test strategy

Taking these strengths and constraints of automation in place, here is how I decide what to automate.

As a rule of thumb, I automate 20% of the tested function(s), according to the 80/20 Pareto rule that states that roughly 80% of effects come from 20% of the causes.

> *The art of testing is knowing which 20% to automate.*

## Deciding what to exclude

First, I look at what can be excluded by spending time with the developers to find out what is already covered in unit tests and how the architecture is designed. Often, the same code is used in different places but from a front-end point of view it’s impossible to tell, and often times, when I do guess that it’s the same code being re-used, I’m wrong.

So my step number one is to really understand what makes sense to automate and what can safely be excluded.

Secondly, I exclude unnecessary details. These vary greatly from one system and work flow to the next. It might be considered unnecessary in one case to test all the different inputs into a new data field to ensure that the field validations and error messages works, whereas in a different case, this might be the most important tests to automate.

> Context is everything.

It’s all about evaluating risk within context. Is it risky for the business? Is it risky for the technology? Is it risky for the users? For example in health care there are patient safety requirements which might look as unnecessary details when viewed in relation to the system functions, but these might cause some form of harm to the patient and is absolutely crucial to include in the automated tests.

However, when there are 10 different work flows of which only 2 are commonly used, I would only automate the 2 most-used ones and exclude the rest, based on a risk assessment. Or, I would add variations of these 8 less used work flows into other tests.

> *Knowing what is important and what is not requires conversations.*

Speak to the Product Owner, speak to user support, speak to the customers, and speak to the developers. They all provide valuable insights that will help you decide what, from an operational perspective, is important and what not.

Regression and automation testing, from my perspective, becomes needed and important when you move into the Ops part of DevOps. It is no longer good enough to only speak to the technical team and the focus must shift to how it’s being used in the field.

## Deciding what to include

The first place to look for inclusions is to go through the errors identified during the sprint and see where the weak spots in the system lie. In plumbing, when a pipe has a weak spot, it tends to start leaking in the same spot rather than a random new spot. The same principle applies to software, thus it’s crucial to include high risk errors or areas where there were a lot of errors in the automation.

Second, I evaluate the risk areas from a business perspective. Some things might seem trivial to a developer but is super important to the business function and reputation of the company. These items you want to at least cover somewhere.

Third, I look at the users and which areas of the system they use most. Where does most of the work get done and what kind of data is used? If possible, I speak to real users and get samples of real data to include. Analysing real data is a super helpful tool to understand how users really use the system as opposed to how they ‘should’ be using the system.

I once met a guy who built hiking trails for a living and I asked him how he knows his trails are successful. He told me that he uses it himself, and he looks for evidence of how users are using it. It’s quite easy to spot where users get off the trail and can then add a clear marker. He doesn’t try to force the users to use the trail as he intended it to be built, he takes feedback from the real users and adapts the trail accordingly. The same should be true for software. The real users should be telling us how the system is being used and what the needs are. Where do users get confused? Where does users input wrong data in the fields?

Finally, I look at what has already been automated and how this can be re-used, or possibly made redundant. When automated tests keep passing consistently, it might be safe to modify them or even remove them. When automated tests keeps failing, it might be necessary to add more tests to make trouble shooting easier.

I then build a test suite trying to cover most of these inputs into the least amount of test scenarios as possible, by including for example different combinations of data in different work flows to get as much coverage as possible with the least amount of effort.

The key differentiator between unit tests and regression tests in my opinion is that unit tests cover the small, standalone functions. Regression tests should always aim to include an entire work flow from logging in to logging out after completing a specific objective or task. The log in function might work and the next function might also work separately, but logging in and then immediately trying to do something in a sequence are where the value of regression comes in.

# Conclusion

It’s easy to add just one more test and just one more function. The art of testing is trying to remove just one more test and still cover all the functions.

Automating tests should be kept lean in order to consistently add value.





*Originally published on Medium: https://medium.com/teal-times/a-lean-approach-to-automation-testing-ad6fcdcf41e3*