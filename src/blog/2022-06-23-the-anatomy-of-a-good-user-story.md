---
title: The anatomy of a good user story
description: Crafting user stories that’s not too big and not too small is an
  art. Visualizing these parts and interactions greatly aids a shared
  understanding and reduces the errors as a result of missed or misunderstood
  requirements.
tags:
  - post
author: Kate Dames
date: 2022-01-31T07:13:54.379Z
image: /assets/blog/didssph-pb80d_b4g7c-unsplash.jpg
imageAlt: Crafting user stories are a bit like nested Russian dolls.  So how do
  you get the size just right?
 canonical: "https://experiencestack.co/a-rough-guide-to-crafting-user-stories-thats-just-right-bc0c70a98f90"
---

## A rough guide to crafting user stories that’s just right

> ”Once upon a time, there was a little girl named Goldilocks. She came upon a house and when no one answered, she walked right in.
>
> At the table in the kitchen, there were three bowls of porridge. Goldilocks was hungry.”

The story of Goldilocks and the three bears is a story about finding balance. She first finds something too big or too hot or too much, then something too small or too cold or too little. Finally, somewhere in the middle of these two extremes, however, she finds that one that’s _just right_.

We have all come across the problem of getting user stories _just right_. Few people manage to master the art of crafting user stories and it is probably one of the most challenging aspects of implementing Scrum. Either the stories are too big or too small. Or there is too little details or too much. Getting a user story just right is hard. But not impossible by all means.

## What makes a good user story?

There are many reasons why user stories are hard to get right, so it’s important to understand the anatomy of a user story. But first, what is a user story? What makes a user story good?

Think of a user story as an app on your mobile phone. Each individual app is designed to do one thing, while combining a number of apps turns your mobile phone into a personalized micro computer.

![](https://miro.medium.com/max/1400/1*rehJlYdUJz3rhYFQPXa4jg.jpeg)Photo by [PhotMIX Company](https://www.pexels.com/@wdnet?utm_content=attributionCopyText&utm_medium=referral&utm_source=pexels) from Pexels

But let’s analyze the parts of a good user story following the analogy of an app on a mobile phone.

### 1. A user story is the smallest possible item of value

The first element of a good user story is that it is a complete unit that clearly contributes to the value of the existing system. It is in essence a micro version of an MVP (minimal viable product). **_It is a fully functional, complete unit that adds value to a user._**

A good user story has as outcome an independent (or rather *inter*dependent) part that provides value to the stakeholders of the system who uses it. Sometimes these stakeholders are users who uses it, other times it is customers who pay for the product, at other times it could even be the internal team.

Sometimes value is something tangible a user can use, like a new feature that allows them to do something to improve their workflow. Other times it is something intangible like a performance or security improvement that improves the experience and trust without changing any features. At other times, it is something invisible to the user but enables the internal team to better support and maintain the product and thus improve the end-user experience.

> Whatever the content of the user story, the **outcome** should be clear and **why** it is valuable.

### 2. A user story fits into and is affected by a bigger system

Where a single user story is the smallest possible part of value of a system, the value is diluted greatly if it doesn’t interact with the bigger system or environment around it.

Think of a user story like a piece of lego which in itself might be useless without the other pieces to make something. While the part is valuable in itself, the real value becomes evident only when it interacts with the other parts of a bigger system.

When you are clear where a user story is used within a larger system, the value can increase by making it re-usable, and thus more valuable with a higher return on investment.

Going back to the metaphor of a mobile phone with apps, an app that works on Android doubles in value if it can also work on the Apple store and increases value again when it can work on a desktop, tablet or other apps within the app store.

> A user story that can be re-used is more valuable than one that has single use.

### 3. A user story has clear boundaries

True for any system, whether it is the human system, a family system, an organization, or a piece of software, strong boundaries increase the effectiveness and productivity of the part.

When there isn’t clear boundaries to a user story or an app, it becomes confusing. You are not sure where to start and where to end and can easily fall into a deep rabbit hole distracting you from the core value proposition and using all the time on catering for edge cases that might never happen.

Clear boundaries means it is for a specific user (or group of users), it has a specific function or use case, and it has a specific outcome.

> Grey areas only cause confusion. Be explicit.

## The anatomy of a user story

Understanding the parts, how do we put these layers together to craft a meaningful and useful user story?

> „And then she went to the porridge of the Little, Small, Wee Bear, and tasted that; and that was neither too hot nor too cold, but just right.“ — Robert Southey, book Goldilocks and the Three Bears

![](https://miro.medium.com/max/1400/1*UJOgDwnklSVtA48oYziCYQ.jpeg)Photo by [RF.\_.studio](https://www.pexels.com/@rethaferguson?utm_content=attributionCopyText&utm_medium=referral&utm_source=pexels) from Pexels

Using the metaphor of a human body, the three main layers of a good user story can be summarized as the skeleton of the body, the different organs, and finally, the flesh and outer appearance of the body.

Each layer of the user story uses different tools to help the process, just like developers make use of different tools to aid their process of development. For example, a developer might need a code editor, a repository manager or even a library or test automation discipline to turn requirements into functional, reliable code.

The same is true for requirements, with a large number of tools available to make it easier to turn confusion into clarity. But let’s look at the structure and which tools could be useful in each layer. I’ll drill down into each tool in separate future posts.

### The skeleton

The primary structure that keeps a user story together is the foundational part of a good user story. Like a human skeleton allows us to walk, run, dance and play, so too the skeleton of a user story gives structure and form to a feature.

There are three primary tools to build a good skeleton for a user story:

#### **1.Process flow diagrams**

A process flow diagram contextualize a bigger system flow. It maps the inputs, outputs and steps to change the inputs into the outputs in explicit, standalone steps. It is typically a limited perspective of a part of a bigger system.

The process flow diagram is probably the most useful tool to validate whether a user story is too big, too small or _just right._ By splitting a bigger function into the concrete steps, unknowns are highlighted at a glance and too complicated flow diagrams point out a sizing issue on a single page.

#### **2.User experience journey map**

Similar to a process flow diagram, but from a user focused design perspective rather than a system optimization perspective. The user journey map focuses on a single user (persona) and the journey they will make through a system to reach a specific goal.

It differs from a process flow in that it is an end-to-end experience from a user perspective, whereas the process flow diagram is an end-to-end map from a system part perspective.

#### **3. Service blueprint**

A third tool, and possibly one of my favorite tools, is a service blueprint, which merges the system and the user perspectives into a whole system blueprint highlighting the interaction between users and systems, and parts of the system, more clearly.

### The organs

Once you understand the structure and context, the next layer is to focus on the specific parts and what their unique function in the system will be.

In the body, each organ, or organ system, is responsible for a specific function in the body. Even though the body requires all the organs to interact to be in a state of health, each organ can be described with a primary function. The heart is responsible for pumping blood throughout the body. The liver is responsible for getting rid of toxins, the brain is responsible for processing electrical impulses that allow us to interact with the world at large, and the stomach is responsible for processing food that in turn is used to nurture the body.

In a system, the organs can be on a higher level or a lower level in the form of functional units or departments (like operations, design, support, logistics etc). or it can be a specific feature within the system like the payment processing feature, the shopping cart feature, or the login and user authentication feature.

Depending on the team, size and skills of the team, these features will look different in different teams. However, they all have one thing in common — namely that they have a clear purpose and function and well-defined boundaries.

There are many tools available to flesh out the organs of a system and it greatly depends on the team, however, one tool that I find the most useful for complex systems is the use of a Context Diagram.

#### **1.Context diagram**

A context diagram can be roughly described as a zoomed in version of a bigger system from a specific perspective. It can also be described of an abstract summary of a number of use cases grouped together to show the interactions and complexities of any given function and how it interacts with another system, part of a system or user.

Read [here](https://www.cs.uct.ac.za/mit_notes/software/htmls/ch06s06.html) for a concise (if not rather old but still valid) summary of context diagrams. It is a more abstract and visual representation of an ERD (entity relationship diagram) diagram.

It helps you identify boundaries, complexity and impact of a system.

#### **2. Epic map**

Most people are already familiar with Jobs-to-be-done and User stories and there is a lot of material available on both topics, so I won’t delve into details on these two, except for highlighting the context of how and where these two tools fit into a bigger structure.

A user story is a specific business rule or function and the flesh of a system (see the next layer), with the Epic the higher level feature that can be used to contextualize the parts of the system without getting lost in the detail.

Mostly user stories and epics are only visible in a prioritized list, but it can also be mapped into a system map with an above the line of current features, and below the line for wish list items that still needs to be developed per process phase. This will more clearly visualize the relationships and boundaries of a given epic or user story.

#### **3. Example Mapping**

A newer technique that I recently discovered and can be used to turn problems into user stories is Example Mapping, which takes real world examples and extracts the requirements from these examples in an affinity mapping type exercise.

The original [Example Mapping](https://cucumber.io/blog/bdd/example-mapping-introduction/) as designed is a tool to add flesh to an already defined user story, however, I modified this useful tool to map out high level user stories.

### The flesh

The flesh of the body is what is seen and visible to other people. It includes the aesthetics of the feature and provide an interface to interact with the underlying features. It is the part of the system that holds all the parts together in a whole.

#### **1.UI designs and mockups**

The most widely used tool to communicate the lower level features to the team is using UI designs, mockups and concepts. On this level the details are all thought through and the developer simply have to translate what is on the screen designs into working functions.

It is a very useful tool for larger systems or new products, however, it is also a very expensive and slow tool relative to other methods. A cheaper and faster method is to use low fidelity mock-ups which communicates all the main interactions without the detail and a reference to a design system or existing components as base for a discussion.

These mock-ups can even be in the form of a comic strip only focusing on the key frames rather than each individual step. The purpose is to show the trigger (WHEN a user does something), the action (THEN they expect something to happen that will help them achieve a goal), and the outcome (SO THAT they can achieve a goal). A good comic strip (or story) also include the aftermath and how this goal positively impacted their life after it was completed.

#### **2.Acceptance criteria**

The user story usually focuses on _what_ needs to be done and _why_, while the acceptance criteria focus on how you would know if it is successful. The acceptance criteria is a high level scenario planning though and aims to cover the different perspectives that need to be taken into consideration for a single user story.

The acceptance criteria opens up technical discussions on actual implementation, but still does not go into the next level of detail, which can be found in test cases.

#### **3.Example mapping**

The original example mapping method is a detailed, useful tool using actual data as examples to map out test driven development test cases.

Using example mapping at this level ensures that the requirements are explicitly clear on a very low level and the first phase of development. It bridges the Product and Development team’s perspectives by mapping out the low level business rules in a set of use cases (where the acceptance criteria can be seen as the higher level scenarios).

## Conclusion

Crafting user stories that’s not too big and not too small is an art. A good user story is an independent valuable unit with clear boundaries and interact with other parts of the same system, or another system.

Visualizing these parts and interactions greatly aids a shared understanding and reduces the errors as a result of missed or misunderstood requirements.

_If you need help to craft your user stories and get them just right, book a time slot to start the conversation on [www.funficient.com](https://www.funficient.com/) ._

Originally written here: https://experiencestack.co/a-rough-guide-to-crafting-user-stories-thats-just-right-bc0c70a98f90
