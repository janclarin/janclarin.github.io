---
title: Better Friend - Hackathon Winner
description: CalgaryHacks 2017 hackathon winner
layout: post
tag:
- hackathon
- javascript
- project
- webapp
---

Last week, my friends and I competed in the
[CalgaryHacks 2017](https://calgaryhacks.devpost.com/) hackathon.
The theme for the hackathon was automation and optimization, so we came up with
an ingenious idea.

In order to solve the issue of constantly having to monitor our social
networks, we created Better Friend. It's an application that allows you to link
your Facebook account and have it automatically respond to activity on your
feed and pages.

Better Friend allows you to feign interest in your friends' inane memes and
*responsibly* handle customer complaints for business pages. From automatic
replies like "Wow, I was just about to send this to you!" to "Thank you for
your continued support", your friends and fans will immediately notice a
positive change in your Facebook interactions with them.

To develop it, we used Node.js for the back-end to connect to the Facebook
Login and Facebook Graph API to allow commenting and posting on behalf of
users. For the front-end, we learned and used ReactJS to create a web page for
authenticating with Facebook and interacting with settings for the automatic
reply system in the back-end. To store users' preferences, we made use of
a MongoDB instance hosted in mLab. Finally, we used Heroku to host the Node
servers for the demos and testing purposes.

With all of this, we ended up taking first place in the hackathon.
For screenshots and details, check out the
[Devpost submission](https://devpost.com/software/better-friend).

GitHub repos:
[API](https://github.com/janclarin/better-friend-api) |
[Web app](https://github.com/ajr-zimmer/better-friend-client)
