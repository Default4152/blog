---
date: '2018-12-07'
title: 'Sprint 2018-12-07'
category: 'General'
---

## Individual Accomplishments

[@Nulcon](https://github.com/Nulcon)

![Contribution Graph](https://i.imgur.com/bbaVVrd.png)

### Completed this week
* Code organization
* Theme UI
* Layout fixes
* Bug fixes

## Tasks Pulled

### Front End

- Ticket 1
  - https://trello.com/c/0jLyhxKX
  - https://github.com/Lambda-School-Labs/Labs8-OfflineReader/pull/98
- Ticket 2
  - https://trello.com/c/kBEemEfN
  - https://github.com/Lambda-School-Labs/Labs8-OfflineReader/pull/107
- Ticket 3
  - https://trello.com/c/I4aZjL2h
  - https://github.com/Lambda-School-Labs/Labs8-OfflineReader/pull/109
  - https://github.com/Lambda-School-Labs/Labs8-OfflineReader/pull/112
- Ticket 4
  - https://trello.com/c/4XuFNONL
  - https://github.com/Lambda-School-Labs/Labs8-OfflineReader/pull/120


## Detailed Thoughts

We removed a lot of old code and Pods this time around, including Stripe. We found that you cannot use Stripe as a payment processor if your application is going to have subscription & go on the App Store. Because of this, we're currently working to implement Apples payment system. The authentication system switched from Google to Facebook but there are issues with the Facebook SDK so it may require it to be implemented manually.


## Weekly Summary

This week was all about clean up, bug fixes, and improvements to the UI. We spent time trying to break the application and fix the bugs as they came up. There were some changes to the Themer built into the Detail View of the application, now with predefined themes and a brightness slider. Additionally, we improved the documentation of our code as it was lacking. 

I made a lot of updates to the constraints for both Landscape & Portrait modes of various devices such as iPad 9.7 & 12.9, iPhone 6s & 6s Plus, iPhone 8, and the iPhone XR. Each view should now look much better despite the orientation of the screen. Coming up, we'll need to connect to the backend once it's finished to get a users articles displaying correctly.

Web frontend with Auth: https://anywhere-reader-test.netlify.com

Web backend: https://anywhere-reader-test.herokuapp.com

iOS: https://github.com/Lambda-School-Labs/Labs8-OfflineReader/tree/master/ios

BST Whiteboard: https://youtu.be/IqDNX9JTWyg