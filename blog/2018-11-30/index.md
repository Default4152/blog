---
date: '2018-11-30'
title: 'Sprint 2018-11-30'
category: 'General'
---

## Individual Accomplishments

[@Nulcon](https://github.com/Nulcon)

![Contribution Graph](https://i.imgur.com/bbaVVrd.png)

### Completed this week
* Image cache
* Performance optimizations
* Google Auth integration
* Stripe Payment integration
* Bug fixes
* UI Improvements

## Tasks Pulled

### Front End

- Ticket 1
  - https://trello.com/c/BLGTHhgA
  - https://github.com/Lambda-School-Labs/Labs8-OfflineReader/pull/59
- Ticket 2
  - https://trello.com/c/S9V6u7nH
  - https://github.com/Lambda-School-Labs/Labs8-OfflineReader/pull/68
- Ticket 3
  - https://trello.com/c/6LXKekNa
  - https://github.com/Lambda-School-Labs/Labs8-OfflineReader/pull/75
- Ticket 4
  - https://trello.com/c/O0dHYka5
  - https://github.com/Lambda-School-Labs/Labs8-OfflineReader/pull/82
- Ticket 5
  - https://trello.com/c/3je9xmx8
  - https://github.com/Lambda-School-Labs/Labs8-OfflineReader/pull/87
- Ticket 6
  - https://trello.com/c/dtT6sgci
  - https://github.com/Lambda-School-Labs/Labs8-OfflineReader/pull/91

## Detailed Thoughts

We implemented Google OAuth, Stripe payments, and made improvements to the performance of the application. Google OAuth is what we'll be using moving forward as the main authentication for our users. Stripe works with the Django backend and successfully POSTs a charge to the Stripe payment account. There were also improvements made to the way images were being dealt with - the images are now cached and not reloaded if downloaded once. This allowed the UI to work more smoothly if there are a lot of images on screen.

## Weekly Summary
This week went pretty well and the application is coming together. We have the ability to login with users and display the users appropriate articles. Users can also buy a subscription to for premium features via Stripe payments. Communication has gone up considerably between team members as everything becomes more and more tied together.

Instead of writing our scraper manually, we'll be using a library called "Newspaper" which does Instapaper style extraction for us. This really allowed us to get the scraper working to a basic functionality for scraping articles that a user enters.

Web frontend with Auth: https://anywhere-reader-test.netlify.com

Web backend: https://anywhere-reader-test.herokuapp.com

iOS: https://github.com/Lambda-School-Labs/Labs8-OfflineReader/tree/master/ios