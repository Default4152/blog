---
date: "2018-11-09"
title: "Sprint 2018-11-09"
category: "General"
---

![Contribution Graph](https://i.imgur.com/S8PeAB8.png)

### Completed this week
* Completed setting up the main project with a project structure that follows best practices. 
* We used `git` quite heavily to ensure everyone was on the same page - this was very helpful when there were changes to discard.
* Implemented `AuthService` to prepare for connection with backend. This included code for User sign up / sign in / logout.
* Implemented an account tab with a account view & billing view.
* Added a `.gitignore` which included specific iOS folders and files that are being unnecessarily tracked. https://www.gitignore.io

### Front End
* Ticket 1
    * Github - https://github.com/Lambda-School-Labs/Labs8-OfflineReader/pull/5
    * Trello - https://trello.com/c/7xOZvatg
* Ticket 2
    * Github - https://github.com/Lambda-School-Labs/Labs8-OfflineReader/pull/7
    * Trello - https://trello.com/c/fKuOLjGo
* Ticket 3
    * Github - https://github.com/Lambda-School-Labs/Labs8-OfflineReader/pull/19
    * Trello - https://trello.com/c/RHHSJSoz

### Detailed Thoughts
Amongst the work done this week, I had the most fun creating the Account tab for users. I took advantage of Stack Views for this layout and they really came in handy for laying out a sort of "form" view. Additionally the stack views make it much easier to setup views for landscape mode.

As a team we decided to implement a segmented control instead of giving each Billing / Account view their own tab at the bottom of the application. This provides a cleaner interface for users.

![Account View](https://i.imgur.com/Hmabxhz.png)

![Billing View](https://i.imgur.com/jIJdNrQ.png)


### Forming a team
Forming a team was an awesome experience - I've already learned so much about how important it is to communicate with a team so we all stay on the same page. Version control was very handy in enforcing this communication - no changes go through without approval. That being said, I made sure to communicate all of my changes by reaching out directly to teammates and discussing them even before implementation.

Being on a team is a big advantage for work completed. Being able to delegate particular portions of work to others allows idea to be more specific but also get iterated more quickly.

Occassionally a team might disagree on ideas and it's good to get objective feedback from team members to ensure that the idea is the correct step forward. This will help provide users with a more cohesive project all around.


Web frontend: https://upbeat-shockley-073b78.netlify.com/

Web backend: https://likjshfiljsundiclues.herokuapp.com/

iOS: https://github.com/Lambda-School-Labs/Labs8-OfflineReader/tree/master/ios