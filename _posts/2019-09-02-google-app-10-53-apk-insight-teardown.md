---
title: Google app 10.53 hints at next-gen Discover more Ambient Mode
date: 2019-09-02 16:50:00 Z
categories:
- App Insight
tags:
- Google
- new gen feed
- discover
layout: post
subtitle: The latest beta release also reveals more work on the Ambient Mode.
description: The latest beta release also reveals more work on the Ambient Mode.
image: https://res.cloudinary.com/read-write-tech/image/upload/v1567525447/APK-Insight-Google-App-10-53_vzbt6x.webp
optimized_image: https://res.cloudinary.com/read-write-tech/image/upload/c_scale,h_200,w_380/APK-Insight-Google-App-10-53_vzbt6x.webp
author: shan
paginate: true
---

Google app 10.53 rolled out late Friday evening with hints about a “next-gen Discover.” The latest beta release also reveals more work on the Ambient Mode and what type of information will be displayed.

**About APK Insight:** In this ‘APK Insight’ post, we’ve decompiled the latest version of an application that Google uploaded to the Play Store. When we decompile these files (called APKs, in the case of Android apps), we’re able to see various lines of code within that hint at possible future features. Keep in mind that Google may or may not ever ship these features, and our interpretation of what they are may be imperfect. We’ll try to enable those that are closer to being finished, however, to show you how they’ll look in the case that they do ship. With that in mind, read on.’

**Assistant on Pixel’ settings**
In early August, we enabled Google Assistant preferences in the Settings app on Pixel devices running Android 10. With Google app 10.53, it’s now rolled out in Settings > Apps & notifications > Assistant. Since last month, the graphic has been updated to show the four color light bar.

This page brings together all the ways you can “Access your Google Assistant on Pixel.” “Say ‘Hey Google'” links to Voice Match settings in the Google app, while a shortcut to Active Edge is also available. “See all Assistant Settings” directs users back to to the main preferences also housed inside the Google app.

![Assistant](https://res.cloudinary.com/read-write-tech/image/upload/v1567525577/google-app-10-53-assistant-on-pixel-settings_y2r85i.webp)

**Next-gen Discover**

Discover was introduced last September at an event celebrating Google’s 20th anniversary. The Google Feed rebrand focusses on discovering and highlighting your interests. It displays more types of content, including videos, AMP Stories, and evergreen articles that may be be new to you.

Google app 10.53 suggests that a “next-gen Discover” is in development. This “next generation” phrasing was previously used for the upcoming version of Assistant shown off at I/O 2019 and debuting on the Pixel 4 this fall.

```xml
<string name=”use_next_gen_feed”>Use next-gen Discover</string>

<string name=”use_next_gen_feed_details”>Help test our next-gen content framework</string>

<string name=”use_next_gen_feed_preference”>use_next_gen_feed_preference</string>
```

This new iteration will still be a “feed,” with strings referring to it as a “next-gen content framework.” Users — presumably Googlers — are invited to “help test” it out.

***Ambient Mode: Notifications and detailed weather***
Our last look at Google Assistant Ambient Mode revealed a familiar greeting, the weather, music controls, Assistant suggestions, and the ability to display phone notifications. Work on the latter functionality continues in Google app 10.53, while more weather information than just the current temperature and condition will be featured.

```xml
<string name=”amb_mode_personalized_suggestions_setup_prompt”>See your notifications in Ambient Mode.</string>
```

For example, the high and low temperatures will be noted, along with the precipitation chance. A forecast for tomorrow could also be displayed with the Ambient Mode linking to the web for more detailed results.

```xml
<string name=”ambient_weather_detailed_info”>High: %1$s\xb0 \u2e31 Low: %2$s\xb0 \u2e31 Precip: %3$s%%</string>

<string name=”ambient_weather_tomorrow”>Weather tomorrow</string>

<string name=”ambient_weather_disclaimer”>More on weather.com</string>
```

***How to update?***
You can sign-up for the [Google app’s beta program here](https://play.google.com/apps/testing/com.google.android.googlequicksearchbox) or by heading to the Play Store listing on Android and scrolling to the bottom. The latest beta version of the Google app is immediately rolled out when it’s available.

Thanks to JEB Decompiler, which some APK Insight teardowns benefit from.
