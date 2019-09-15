---
date: '2019-09-15 18:30:41'
layout: post
title: Google app 10.61 Insight
subtitle: Google app 10.61 preps ‘Smart Screenshots’ with Lens
description: Google app 10.61 preps ‘Smart Screenshots’ with Lens
image: APK-Insight-Google-App-10-61_kiwe47
image_source: 9 to 5 Google
image_source_url: 'https://9to5google.com'
category: app-insights
tags:
  - Google Assistant
  - Google App
  - Google Lens
author: Sudharshan TK
source_name: 9 to 5 Google
source_url: 'https://9to5google.com'
paginate: true
---
Google app 10.61 is rolling out as the latest beta and reveals work on a new “Smart Screenshots” feature that integrates Lens. A bug with the “Preferred input” setting for Assistant has also been resolved.

**About APK Insight:** In this ‘APK Insight’ post, we’ve decompiled the latest version of an application that Google uploaded to the Play Store. When we decompile these files (called APKs, in the case of Android apps), we’re able to see various lines of code within that hint at possible future features. Keep in mind that Google may or may not ever ship these features, and our interpretation of what they are may be imperfect. We’ll try to enable those that are closer to being finished, however, to show you how they’ll look in the case that they do ship. With that in mind, read on.

**Google Podcasts Bookmarks**

In addition to a Material Theme revamp, Google Podcasts is working on the ability to let users add bookmarks when listening to episodes. The redesigned player gains a save icon next to the sleep timer. When tapped, the current timestamp is stored and a snackbar that appears afterwards will let you view a list of all saves.

Alternately, the Podcasts homescreen gains a new “Bookmarks” tab. Users will also be able to share an episode with that exact timestamp.



![Google Podcasts](https://res.cloudinary.com/read-write-tech/image/upload/v1568552674/google-app-10-61-podcasts-bookmarks-3_vpbeyc.png "Google Podcasts")

**Smart Screenshot**

The Google app has long had an “Edit & share screenshots” ability where captures made within Search would reveal cropping and annotation tools. Meanwhile, Assistant has long maintained a “What’s on my screen” capability that analyzes what you’re currently viewing for search suggestions.

```
<string name=”smart_screenshots_summary”>Edit your screenshots, explore them with Lens, share them with a link, and more!</string>
```

```
<string name=”smart_screenshots”>Screenshot editing, sharing and actions</string>
```

```
<string name=”smart_screenshots_answer_1″>Annotating</string>
```

```
<string name=”smart_screenshots_answer_2″>Cropping</string>
```

```
<string name=”smart_screenshots_answer_3″>Sharing</string>
```

```
<string name=”smart_screenshots_answer_4″>Exploring with Lens</string>
```

Google app 10.61 reveals work on “Smart Screenshots” that combine those two features. Like before, a toolbar — which interestingly uses a four-color light bar — appears after you take a screenshot. A small preview is shown at the left with a pencil button overlaid. You can open the system share sheet, but the Google app also suggests a frequently used app.The most interesting addition is Lens. “Exploring with Lens” could be intended as a “Screen search” replacement given that Lens is increasingly taking over visual lookup throughout first-party apps, like Chrome. After taking a capture, Smart Screenshots have an easy way to invoke Lens for search, OCR, and finding visually “similar items.”

```
<string name=”screenshot_lens_button”>Lens</string>
```

```
<string name=”screenshot_lens_tooltip_text”>Find similar items</string>
```

The existing editing tools (Annotating, Cropping, and Sharing) will remain and this new functionality appears to even use the same settings toggle to enable.

```
<string name=”smart_screenshots_step_1″>Next time you search for something, take a screenshot</string>
```

```
<string name=”smart_screenshots_step_2″>”You may need to turn on the feature in your Settings. From the app home screen, go to ‘More’ &gt; ‘Settings’ &gt; ‘General’ &gt; ‘Edit &amp; share screenshots'”</string>
```

It’s unclear if this functionality once live will again be limited to screenshots taken within Search, or if it will expand to be systemwide and invokable anywhere. A notification from the Google app could appear after capturing a screenshot.

```
<string name=”smart_screenshots_notification_content”>The Google App has saved a screenshot</string>
```

```
<string name=”smart_screenshots_notification_title”>Screenshot saved</string>
```
