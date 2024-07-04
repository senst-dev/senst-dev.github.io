---
layout: ../../../layouts/ProjectPostLayout.astro

title: 'Prepped'
description: 'A Weekly Meal Planner Implemented Using React'
gh: 'https://github.com/senst-dev/prepped'
image:
    filepath: '/src/images/projects/prepped.png'
    alt: 'A screenshot of the Prepped app, showing a table of all days in week with a meal selected for breakfast, lunch, dinner.'
---

## What is it?
Prepped is a super simple React project that is designed to have do meal planning over a week. It lets you add meals, customising some attributes like calories, a description and so forth. You can then select a meal for 3 main meals across the week

## But why?
This was mainly cause I was using a spreadsheet or MyFitnessPal to try track this, but was a little tricky to use, or hard to see an entire week at once. Reusing meals and adding a bit of extra info for them was also a pain point.

So I made a small webapp to freshen up my React skills from Uni, and have a place where I can quickly navigate to - URL pretty easy to save/autocomplete and browser local storage for a bit of text is not a problem 

## What's next
- Could do CSV import and export for integration with things like MyFitnessPal
  - If a person is already paying for a premium service, unlikely this is going to be a huge value add. So not a big deal.
- Customisation for different numbers of meals, snacks etc - flexibility in how meal plans are created.
  - There's some simple extensions that can be done, but ultimately, doing some real user research would be key here.
- LLM integration to hop on the hype train. For instance, recommended a meal, estimating calories in a given meal and so forth.
  - Its expensive for a tiny web app 💸