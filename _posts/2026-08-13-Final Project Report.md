---
layout: post
title:  "Final Project Report"
date:   2026-08-13
categories: Project Status
---

## Introduction

My vision for this project was primarily to learn and implement a new
programming language for a personal project I am passionate about. My overarching
goal was to create an Android companion application for my online WaniKani account to
be able to complete my reviews directly from my phone.

## Background

The project is about using the WaniKani API to complete radical, kanji and
vocabulary reviews through an Android application. It was developed using Kotlin
through Android Studio. WaniKani hosts its own API that stores all the data for their
learning platform as well as individual data for each of its users. A part of this data
includes the review system they implement to have their users learn through review
“cards”. There are 8 different levels a review can have and the higher level a review, the
less likely it appears in a user's review stack. Using this data set from their API, I aimed
to pull my active reviews, complete them, and send back the completed review to
WaniKani.

This entire system was important for me to learn because while it is simple from
afar, it is much more complex when you dive in to learn how certain pieces of data
relate to another. A main goal I had for myself was to learn how WaniKani works behind
the scenes and what is needed to mimic a barebones version of their site on my phone.
I took this as an opportunity to test myself on how to learn and use a new programming
language and IDE. Professionally, it gives me a project I am proud to showcase and the
confidence to pick up new programming languages to learn.

## Methodology, Materials and Methods

Professor Guinn was a big help in getting started. He directed me to the Android
Studio development tutorial which helped to get me started in Kotlin. My project builds a
good amount from the introduction I received in their Mars app project.
The WaniKani API was another brilliant source of helpful information throughout
my project. I spent a good amount of time reading and rereading pertinent sections of it
to understand what I needed to do to get data from them. It also helped me parse
through the data from my GET requests to see what information I needed and which I
could set aside for future use.
Methodically, I set out with weekly goals and a calendar to stay on track. I also
granted myself some leeway in case I ran into hurdles or if life just happened. This was
a great help in the beginning, and helped me prioritize necessary parts of the project,
rather than veering off course on tasks that were not pertinent to my MVP.

## Results

I learned a lot more on how to implement API calls, especially through Kotlin. I
also learned the intricacies of learning a new programming language. It is challenging,
but not as challenging as I had expected. The basics can easily translate at times, but
figuring out semantics and the quirks of a new language can be a hill to climb at times. I
also learned how to actually start a project. I have found starting a project from scratch
a very difficult thing to do since starting this program. I tend to have an idea of the end
product, but starting it from scratch has always been a wall I have needed to push
through. This project taught me that starting is always going to be difficult, but once I
was able to print a kanji on screen, it felt like an incredible hurdle was crossed.
I had to use two GET calls and one POST call to make the basic functionality of
the app work. For the first call I had to use a lot of google (plus trial and error) to make it
work. The second call I used my knowledge from the first to help make it work. The last
one was the trickiest, as it was a POST, but I learned from the other two that the
fundamental knowledge was the same. Going back and reviewing my code, I am able to
look and explain each part of it.

Throughout my project, I had 5 specific assessments:

1. Research WaniKani API, fetch GET requests via Insomnia
2. Set up basic app with API to fetch all reviews
3. Display one review at a time
4. Accept user answers & validation
5. Post completed reviews back to WaniKani

And I had 1 overarching goal:

1. I can access my reviews directly from my own phone. I should be able to
complete daily reviews without needing to access the site via a PC.
I was able to reach every one of these goals, though not as quickly as I had liked.

## Discussion / Reflection

Setting up small achievable goals week-to-week was a helpful strategy to hit my
ultimate goal of having a true (bit barebones) companion app. Splitting the larger project
into smaller tasks that build on top of each other was a very helpful way of
accomplishing this project. Before the proposal, I was overwhelmed with the details and
specifics of this project. I have a tendency of jumping forward 10 steps, when I should
be concentrating on the first step.

I am proud of the work I have done so far on the project. I consider my MVP
done, but I do not consider the project complete yet. I had three stretch goals at the
beginning of the semester:

1. Caching reviews to be available offline
2. Custom UI for reviews
3. Notifications for when reviews become available

Working on the project has only made me want to continue working and polishing my
work by implementing these (and other features) to my project.

## Conclusion

The confidence I gained from this project has helped keep me motivated and
hopeful for my work once this program ends. I am excited to start working on projects I
am passionate about. With this new experience of starting from scratch, it helps me
keep a sort of sanity when I think back to older project ideas that I thought were too out
of my skill level. It makes me want to revisit those ideas and give them a true try.

First, my next plan is to keep working on this project. WaniKani is something I
use on a daily basis, so being able to improve my companion app is a top current
priority. I have also enjoyed using Android Studio and Kotlin, so I am thinking of
continuing with some more projects that focus on these two tools. I have struggled to
think of what kind of industry or area I would like to work in, but working with Kotlin has
me excited to pursue that route.

## References

1. <https://developer.android.com/courses/android-basics-compose/course>
2. <https://developer.android.com/codelabs/basic-android-kotlin-compose-getting-data-internet#0>
3. <https://lysine.dev/retrofit/>
4. <https://www.freecodecamp.org/news/hide-your-api-keys-in-android/>
5. <https://developer.android.com/develop/ui/compose/layouts>
6. <https://kotlinlang.org/api/core/>
7. <https://www.geeksforgeeks.org/kotlin/kotlin-programming-language/>
