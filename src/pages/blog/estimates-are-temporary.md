---
templateKey: blog-post
title: Estimates Are Temporary
path: blog-post
date: 2020-10-14T09:20:00.000Z
description: Estimates are perishable. As soon as they're made, new information makes them obsolete. Unless updated frequently, whatever value estimates provide quickly diminishes.
featuredpost: false
featuredimage: /img/estimates-are-temporary.png
tags:
  - agile
  - estimates
  - estimation
  - lean
  - noestimates
  - waste
category:
  - Software Development
comments: true
share: true
---

This is the fourth of the [5 Laws of Software Estimates](/the-5-laws-of-software-estimates/). I expanded on the [third law of software estimates in my previous article](https://ardalis.com/estimates-are-wrong/).

Estimates are made for a given point in time, when a certain set of information and assumptions are known and held. As time passes, new information becomes available and assumptions change. The older the estimate, the more likely it is to be stale. Since by definition [estimates are wrong](/estimates-are-wrong/), the impact of time on estimates is simply to make them even more inaccurate. Imagine if three days ago the weather forecast called for sun, but looking out the window you see dark clouds rolling in and wind blowing trees all over. Do you take an umbrella or raincoat for that walk through the park, or trust the out-of-date estimate of what the weather could have been?

Of course, given that estimates grow stale, the only way to keep them fresh is to re-perform them periodically. If estimates are critical to a process's prioritization process, this is the only sensible approach, since otherwise the whole process will be based on bad information. That is, assuming the information was any good to begin with, given that [all estimates are wrong](/estimates-are-wrong/) and [estimates often only apply to the person who made the estimate, not whomever ends up doing the work](/estimates-are-non-transferable/).

But how can you make decisions about which work to perform if you can't make a cost-benefit analysis to try and calculate the ROI? Well, firstly, there's rarely as much effort put into estimating the actual "value" of a user story to the business as there is put into its "cost" (in terms of developer effort). And even if there were, it's likely very difficult to attribute "value" to a given user story for a business feature that requires dozens of such stories to be completed and in the hands of a customer (and even then, did the customer only make the purchase because of this feature?). The "value" side of the ROI calculation is usually very subjective as it is, so the illusion of being able to use the "hard numbers" of estimates to make decisions is just that, an illusion.

What you can do is prioritize based on the importance of the work item to the current set of goals, which ideally should correspond to a [vertical slice](https://deviq.com/vertical-slices/) of functionality. Secondly, you can try to break large work items into smaller pieces. The smaller the work items, [the quicker they flow through your development process](https://www.pluralsight.com/courses/kanban-fundamentals). Given a backlog of relatively small work items (small because they've been broken down, not based on any estimation), rough prioritization should be possible, and if estimates provide any value they can be done just in time by the developer about to perform the work. The purpose of these estimates might be to provide an opportunity to further refine the work, since any estimate in excess of a certain threshold might indicate that the work wasn't understood well enough when the story was created. Such estimates are made at the last responsible moment, by the person who will be doing the work, and thus overcome the issues with estimates being non-transferable and temporary. Such estimates are also less likely to need to be redone, further minimizing the potential for [waste](/estimates-are-waste/).

Learn more about the [5 Laws of Software Estimates](/the-5-laws-of-software-estimates/), and share your own experience in the comments below.
