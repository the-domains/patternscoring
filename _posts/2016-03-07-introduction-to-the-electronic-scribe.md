---
inFeed: true
hasPage: true
inNav: true
inLanguage: null
starred: false
keywords: []
description: ''
datePublished: '2016-03-07T20:44:36.509Z'
dateModified: '2016-03-07T20:43:32.696Z'
title: Introduction to the Electronic Scribe
author: []
authors: []
publisher:
  name: null
  domain: null
  url: null
  favicon: null
sourcePath: _posts/2016-03-07-introduction-to-the-electronic-scribe.md
published: true
url: introduction-to-the-electronic-scribe/index.html
_type: Article

---
### Introduction

This site provides real-time scores for precision aerobatics events that are in progress or have been completed and that are using our scoring system. This system is also able to utilize an iPod + game controller based electronic scribe system for enhancing the score keeping at precision aerobatic events. The system was designed to be loosely-coupled to the underlying PC (or Mac)-based scoring program so that we can accomodate any scoring application, as long as that application provides some set of interfaces for accessing the contest data (contest name, what classes are being flown, the contestants in each class, etc.) as well as a way to provide score data for each maneuver from each judge.
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/44915a0b-c73a-4a2b-beb3-b9d9b4dcb86c.jpg)

At the moment, the only fully supported scoring application is the [Master Scoring App][0] developed by Scott Smith in NSRCA D1 to support the matrix format required by the NATS, though it also fully supports standard local contest formats, MAAC F3A formats, etc. Click the Master Scoring link on the left to download the Master Scoring app for Windows.

Working with Scott Smith, we've built an [adapter][1]that runs alongside the MasterScoring app to deliver electronic-scribe based scoring and hosts a local scoreboard website that can easily be displayed at the field using a simple 19" or larger LCD TV with an HDMI port connected to a simple Raspberry Pi System-on-a-Chip computer (or any computer with an HDMI port) running the Chrome browser. In fact, the adapter application is also what's running on the site here for this page and all the contest scoreboards.

### Why?

The first question that comes to many pilots is "why?" Why change the paper-based scoring system we've been using for years? Well, consider:

* At a contest with 20 pilots flying 6 rounds there are 4560 individual scores to be entered into the scoring computer. That's 4560 chances for an error to be made in data entry, requiring each pilot to cross-check 228 scores.  
* A judge must simultaneously keep their eye on the plane while reading the maneuver description/Aresti and mentally counting downgrades, then write the score down without losing sight of the airplane.  This essentially impossible task (unless a scribe is provided, which is very rare at a local contest) means judging often degrades to "impression judging" because of the task loading we impose on judges.  
* For the score keeper, they are typically unable to participate in the camaraderie of a contest and cannot learn from watching other pilots fly or relax prior to their competition flights because falling behind in score entry delays the entire contest.

The electonic scribe system is designed to solve all of the above by providing a very simple, eyes-free scoring interface for the judge and wirelessly transmits the scores to the scoring computer after the judge has had a chance to review while the next pilot prepares to compete.

* Each maneuver is read to the judge through earbuds or other headphone device (at the judge's discretion).
* A simple game controller allows the judge to tally downgrades as they are seen with simple button clicks without taking their eyes off the plane.  Pull a trigger to advance to the next maneuver.  
* The current score is voiced through the headphone as it changes so the judge is always aware of the score and knows that their button click was successfully registered.

### How?

The easiest way to learn the scoring system is to use it in a low-pressure environment, while rolling the system out I try to be at the field with the system on the practice day prior to a contest for everyone to use it. If that's not possible, it's been my experience that a brief intro like the video below and having someone help with the first 1-2 contestants during a contest will get you up to speed using the system quite quickly. If you can manage an RC plane transmitter with switches, etc. to fly a plane, you can manage this controller!

[https://youtu.be/RIKztfcOmOo][2]

[0]: http://amapatternscore.blob.core.windows.net/clickonce/setup.exe
[1]: https://www.dropbox.com/s/kb1rw5uvyt7n0hm/ScribeAdapter.exe
[2]: https://youtu.be/RIKztfcOmOo