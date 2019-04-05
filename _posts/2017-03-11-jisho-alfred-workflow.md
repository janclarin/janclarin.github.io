---
title: Jisho Alfred Workflow
description: Alfred workflow for Japanese-English searching
layout: post
tag:
- project
- python
- extension
---

As I have been learning Japanese, I've found [Jisho.org](http://jisho.org/),
an online Japanese-English dictionary, to be a great asset. In order to to make
it easier to access Jisho, I created an [Alfred](https://www.alfredapp.com/)
workflow. I called it, unsurprisingly,
[**Jisho Alfred Workflow**](https://github.com/janclarin/jisho-alfred-workflow).

It's an improvement in speed and reliability over the existing
[Jisho v1.0](https://github.com/kylesezhi/alfred-jisho) workflow that is no
longer maintained. Jisho Alfred Workflow conservatively waits for the user to
finish typing before making a request to the Jisho API and cancels existing
requests if the user starts typing again instead of waiting for every response.

Even cooler, one of Jisho.org's creators
[loved it enough](http://jisho.org/forum/58cad15912a53744f5000168-new-alfred-workflow-for-searching-jisho-dot-org)
to finally purchase an [Alfred Powerpack](https://www.alfredapp.com/powerpack/) 
in order to use it.
