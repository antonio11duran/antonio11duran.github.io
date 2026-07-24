---
layout: post
title:  "Week 9 Project Update"
date:   2026-07-16
categories: Project Status
---
This post is a part of a series of weekly status updates for an Android app project I am doing as a part of the Professional Development in Computer Science class at the University of Colorado Boulder.

## What did you do last week?

Last week I implemented the validation for my reviews. I was a bit worried about implementing it for radicals and vocabulary without meanings, but was able to just implement a simple check to see if any correct readings were available. If empty, I would bypass the Reading check entirely and continue to the next review.

I was also able to do a bit of a feature request where the application requests a Japanese keyboard when answering reading sections of reviews. Now the keyboard will automatically switch without having to do it manually. I also did some formatting fixes with the vertical and horizontal alignment, as well as making the font a comfortable size for viewing.

![Screenshot of virtual phone with Vocabulary Reading Requested](/images/jp-kb-screenshot.png)

## What do you plan to do this week?

This week my goal is to implement the POST request to WaniKani with my completed reviews. I will probably start with getting familiar with the /reviews endpoint.

## Are there any impediments in your way?

I took a quick look at the reviews endpoint and realized I need to make some additions to my validation function. Inside of it, I need to implement a way to track and map the number of times each answer is entered incorrectly to the assignment id.

## Reflection on the process you used last week, how can you make the process work better?

My process last week worked really well. I have started to dedicate more time throughout the week to work on this project, which has led to me being able to make big strides at the beginning of the week, rather than the end. This strategy helps keep me motivated each week as I realize that I have made more progress than I expected. Moving to using my phone as my testing device has helped cut on distractions, since it is being occupied by my application.
