---
title: "TimeFlow"
headline: "Your day as a gentle river."
tagline: "A calm daily planner: your day as a river flowing past a NOW line."
description: "A calm daily planner that shows your day as a river flowing past a NOW line. Private by design: no account, and your tasks never leave your device."
platforms: ["iOS", "Android", "Web"]
tech: ["Flutter", "Dart", "Riverpod", "SQLite (drift)", "Local notifications"]
featured: true
weight: 3
year: "2026"
timeline: "Ongoing"
client: "Rinse Repeat Labs (in-house product)"
image: "/images/timeflow.png"
cardImage: "/images/timeflow-card.png"
webUrl: "https://imcmurray.github.io/TimeFlow/"
githubUrl: "https://github.com/imcmurray/TimeFlow"
gallery:
  - "/images/timeflow/1-timeline.png"
  - "/images/timeflow/3-new-task.png"
  - "/images/timeflow/4-share.png"
  - "/images/timeflow/5-shared-link.png"
  - "/images/timeflow/2-welcome.png"
legal:
  - title: "Privacy Policy"
    url: "/legal/timeflow/privacy-policy/"
  - title: "Terms of Use"
    url: "/legal/timeflow/terms-of-service/"
---

## Overview

TimeFlow is a daily planner that shows your day as a river. A NOW line stays in place while tasks drift toward it and flow past as the minutes go by, so you always see what's happening now, what's next and what's behind you. It's Rinse Repeat Labs' own product, built with Flutter from a single codebase for iPhone, iPad, Android and the web.

## The Challenge

Calendar grids make time look like a set of boxes to fill. For visual thinkers, and for many people with ADHD, that grid is stressful and makes it hard to *feel* time passing. The goal was a planner where the present is always in view and the day moves on its own.

## Our Solution

**A timeline that moves**
The NOW line is fixed and the day scrolls past it in real time. Scroll away and one tap brings you back.

**Planning in seconds**
Long-press anywhere to add a task at that time, long-press and drag to move one, and swipe to complete or delete (with undo).

**Repeats that make sense**
Daily, weekdays, chosen days, every few weeks, monthly or yearly. Edit one occurrence, that one and the rest, or the whole series. Times hold steady across daylight-saving changes.

**Gentle reminders**
Notifications arrive even when the app is closed, with Done and Snooze right in the notification.

**Hand over your day**
Share a day or a week as a link that a pet sitter, babysitter or caregiver opens in any browser. The schedule travels inside the link and is never uploaded.

**Private by design**
No account, no ads, no analytics, no servers. Tasks live on the device, and backups are files you save.

## How It's Built

- One Dart codebase for iOS, Android, web and desktop
- On-device SQLite database through drift, with tested schema migrations
- Share links encode the schedule in the URL fragment, so nothing is uploaded
- Automated tests and CI on every change, with automatic web deploys to GitHub Pages

## Status

Web app live; iOS in TestFlight beta with the App Store listing in preparation; Android 1.0. Desktop builds are experimental.

## Where to Find It

- **Try it in your browser:** [imcmurray.github.io/TimeFlow](https://imcmurray.github.io/TimeFlow/)
- **Android:** the APK is on [GitHub Releases](https://github.com/imcmurray/TimeFlow/releases) until the Play listing is live
- **iOS:** App Store listing coming soon, as **TimeFlow Planner**
- **Source code:** [github.com/imcmurray/TimeFlow](https://github.com/imcmurray/TimeFlow)
- **Support:** [imcmurray.github.io/TimeFlow/support.html](https://imcmurray.github.io/TimeFlow/support.html)
