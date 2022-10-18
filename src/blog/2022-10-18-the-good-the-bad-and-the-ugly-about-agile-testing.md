---
title: The good, the bad and the ugly about agile testing
description: Being agile is about responding to customer needs promptly, and the
  best way to do this, is to know what those customer needs are. Even though the
  Product Owner’s primary role is knowing their customer, it’s not possible to
  view the same thing from two different sides.  If you want to be really agile,
  invest in more manual testing.
tags:
  - post
  - process
author: Kate Dames
date: 2022-10-18T06:26:04.694Z
image: /assets/blog/pexels-kat-smith-568025-1-.jpg
imageAlt: Unlocking the secrets of the value of tetsing.
canonical: https://everydayagile.com/the-good-the-bad-and-the-ugly-about-agile-testing-29b4b847c778
---
*A story of testing and why it is important*

I accidentally stumbled into the world of testing. I had no clue what is was at the time, yet my first job title after I dropped out of University was **test engineer**.

I didn’t really care what my job title was or what I did to be honest. All I cared about was getting ***a*** job in order for me to not have to go back to the much-too-small hometown where I grew up, where big dreams were not allowed.

So when my friend said their company was looking for someone, I went for an interview and two weeks later started. Perfect! A job that will allow me to stay in the city, with the added benefit of having lunch with my best friend everyday. Life couldn’t get any better.

***Innocent inquiries…***

But soon friends started asking me what I did, and I realized I couldn’t really answer satisfactorily, so looked at my appointment letter to figure out what I’m supposed to answer. I understood the words written on the paper, but I didn’t understand what they entailed, so I innocently walked to my boss and asked him what it meant to be a test engineer. He chuckled, me not understanding why, and continued to patiently explain in lay men’s terms what I do every day, leaving him very amused and me blissfully satisfied, knowing what I am finally.

Equipped with this knowledge, I felt more important, more confident, and did my best to be the best test engineer ever, even though I really still didn’t have a clue what I was doing — only following instructions blindly.

## The good

With the same oblivion I continued my early career stumbling on different job titles as jobs managed to easily fall into my lap unasked for, allowing me to do the things I love while earning a salary.

> Each time I got a new job I followed the same approach. I contemplated exactly what it meant to be this new job title, and what you would need to become the best at it.

In retrospect, quite a useful and sensible approach! At the time though I was considered much the opposite of sensible. To this day this logic approach seems to be considered weird by most. I find it weird that more people don’t figure out what they’re supposed to be doing before they start doing it. But hey, each for their own.

My journey included, among other roles, that of being a test engineer, quality assurance consultant — including automation-, usability-, manual- and performance testing — , test manager and finally quality manager. Each time, treating the role as if it was a blank canvas, I invested great effort in researching what each role really personified, and the goal of each.

> I studied each role from all the possible angles, and each time would pride myself in mastering it.

As a test engineer I learned that the only way to verify that something is working, was to be very sure that you understand what it is supposed to be doing and why.

***Sensible standards…***

I came to understand the importance and value of standards, especially international standards, and how to systematically work my way through a standard, evaluating software (in this case gaming machines and systems) from all the possible angles — reviewing the source code, the artwork, the physical device, and that everything works well together.

Then, one step up as a quality assurance consultant, I learned that you don’t need a standard to test something, and learned about different requirement gathering techniques.

***Very virtuous…***

I then discovered the **V-model** and analyzed it’s meaning on each side of the “V” in detail, having countless arguments about the difference between verification and validation and each level of the model and what it means.

I learned about all the different test techniques and which to apply when. I also learned about how and when to use harnesses and data. *Most interestingly, I learned that depending on your viewpoint, everyone in the numerous arguments were in actual fact correct.* System testing to one means the same as unit testing to someone else. Integration testing to the developer means something different to the architect or the business owner.

I also learned about things like code coverage tools and the difference between stress testing, performance testing, and how to implement a test automation framework.

***World without end…***

When I was appointed as quality manager, I was surprised to find out that what I thought was the totality of the world of testing, was merely one drop in the ocean and that there was much more to learn. As testing only forms a small part of quality assurance, so quality assurance is also only a small part of quality management.

As I taught all the new employees on the ISO 9000 framework, I learned that quality is not about how fast, or how good, or how beautiful a system is.

> Quality is simply meeting customer expectations, fulfilling a need, solving a problem.

It’s not quality if you give someone looking for a fuel efficient, small car to use in the city, an expensive Lamborghini. *Bigger, fancier, more is **never** better.*

It’s quality only if you listen to the customer and give them what they want. It’s quality if you make decisions in collaboration with the customer, not telling — or worse, building — them what you think they need, based on advice from your best developer.

It’s also not necessarily about giving them what they ask for, as mostly they are using the wrong terms or examples and is simply trying to be understood. Rather, they are looking at you to advise them on what they need.

*As this knowledge dawned on me, I realized that I’ve been putting way too much emphasis on the functionality and technical capabilities, and way too little on finding out what the user needs or what their problems are.*

I changed my approach and I was overwhelmed with how many customers thanked me for helping them do their job easier, better!

> I tested less, yet the quality went up.

And just as I thought I had all the answers, they went and changed all the questions. *Agile was born.*

## The bad

Suddenly, my safe little island where I was the queen of my world, collapsed as we were pushed into a team where the world evolved around only the developers and their needs, with the testers the scapegoats having to take responsibility for all the errors right at the end of the development cycle.

While the developers had the luxury of “developing” at ease until the deadline, the testers had to make magic happen as the developers have already used up more than the allowed for time buffer.

To make this worse, they didn’t really seem to think that testers are needed at all and only saw them as an annoyance, hurting their sensitive ego’s each time a bug was reported. Something they would *much* rather do without. Understandably.

As if that wasn’t hard enough, we — the testers — were outnumbered by far with ratios as much as 8 developers to 1 tester in a team. With most agile coaches and Scrum Masters coming from a developer background, they never really understood the art of testing, and focused only on the technical skills, making the life of an agile tester less than a happy one.

The developers started learning skills like TDD (test driven development) and with the Product Owner giving the acceptance criteria, slowly but surely the testers were shifted out of the development life cycle, seen as waste by the ever ambitious line managers looking to optimize the process.

Not wanting to be seen as redundant, I worked hard to master what I call agile testing.

I experimented with exploratory test methods, and spent more time with the developers. I had handover sessions with them to understand what they have included in their unit tests already, thus lessening my work load, and understanding the architecture of what they have built, to optimize my effort. I also spent more time with the automation team who couldn’t keep up with the speed, compiling regression test suits that covers all the functions, without having to test everything.

And it worked!

> *I figured out that agile testing means better team communication, better judgement, and happier teams as the effort was split more equally.*

## The ugly

However, as the test and development team started to deliver higher quality work, the next problem became evident, namely the requirements. Or rather, the lack of customer-centered requirements. I realized that having a user story doesn’t mean the person that wrote it understands the user it is intended for.

The struggle started all over again, this time trying to get buy-in and understanding not from the developers as to the value of testing, but the Product Owners and business.

Finally, however, I admitted defeat, realizing that my fight for existence in a world that doesn’t want testers is futile. I was tired of having to fight for resources, and trying to convince the developers that I’m on their side.

I couldn’t stand another day of having to explain to the Scrum Master and the lead developers why they needed to include me in the technical sessions, or begged them to fix a critical bug before a customer has to suffer the consequence of the failure.

The final push came after visiting one of my best friend’s dying father for a week and seeing how devastated not only he, but also his family, was after being diagnosed with only a few months to live. Days went past where he didn’t even got up in the morning, and when he did, his eyes were empty and his focus somewhere else.

Two weeks later, having returned home, I followed up to find out how they were doing, just to hear that after the agonizing long wait because the doctor was on leave, that they made a mistake with the diagnosis. He wasn’t dying after all.

Working in the healthcare industry at the time, I realized that I was partly responsible for this trauma and have the power to prevent it. The only problem was that in reality I was totally powerless.

The developers simply didn’t have the empathy, being too removed from the patients themselves, and besides, they were only allowed to do what the Product Owner told them to do. If there isn’t a requirement, they won’t develop it and the requirements given by the Product Owner is not to be questioned or changed.

As a last resort, and with my passion for quality, understanding that quality evolves around meeting user requirements (not a Product Owner’s interpretation of it), I told this touching story to the responsible Product Owner in the hope that she at least will realize the impact of her decisions.

She listened with compassion, agreed that it was a terrible mistake to have been made, then turned back to her computer screen, not even considering the possibility that she can at change it.

Not willing to give up on my friend’s father and all the other users represented by him, I reached out to another Product Owner, hopeful for more empathy. Yet, the answer again was one of powerless shrugging of shoulders, being unable to influence the decisions of the Development Manager and business with regards to requirements.

Tired of this constant and ego-centered tug of war between disconnected parts of the business, I finally gave up.

## Back to Basics

As I walked away and started working on projects not related to software development at all, I gained perspective again, remembering why testing became so popular in the first place many years ago.

*The biggest benefit of testing has always been it’s risk mitigation.* By having an objective party look at the software, you exponentially decrease your risk of delivering faulty software to the end-user, thus exponentially manage to meet, or improve quality of the system.

> That’s the reason why pair programming works, and that’s the reason why you have to get an external auditor to prove compliance. There is a conflict of interest when the same person, or type of person, evaluates a piece of software as working.

Just like a person misses the huge turtle swimming past while they are engrossed in observing a beautiful nudibranch or other macro-sealife when diving, so too the developers are so absorbed in the details of the code they’ve written, that they easily miss what is obvious to someone external using the software.

Where pair programming gives an extra pair of eyes on the details of the code, so the tester gives a different perspective on the whole system from an external point of view. No matter how good a programmer you are, it is not possible to look at the same thing from two angles at the same time.

The tester, if trained well, has the primary role of seeing what the developers missed, and in my experience, even the best of the best still end up with errors in their code.

If you’re considering getting rid of your manual test team, ask yourself the following

> “Do you rather want to spend a bit more time during development to find and fix errors? Or do you rather want to fix the errors once the end-user discovers them?”

Because if the errors exist, they will be discovered eventually. *The question is, at what cost?*

# Conclusion

Being agile doesn’t mean that you don’t manually have to test software.

Being agile is about responding to customer needs promptly, and the best way to do this, is to know what those customer needs are. Even though the Product Owner’s primary role is knowing their customer, it’s not possible to view the same thing from two different sides.

When two people sitting opposite each other views a can of coke in the middle of the table, each sees something else, yet both are correct. Similarly, manual testing is that extra pair of objective eyes that helps you to be more agile.

If you want to be more agile, get a really good tester.

<!--EndFragment-->





*Originally published on Medium: https://everydayagile.com/the-good-the-bad-and-the-ugly-about-agile-testing-29b4b847c778*