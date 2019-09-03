---
title: YouTube Music 3.31 hints at retail mode push for Google’s streaming service
date: 2019-09-02 19:16:00 Z
categories:
- App Insights
tags:
- youtube music
- retail mode
layout: post
subtitle: YouTube Music 3.31 reveals work on a “retail mode” to help increase adoption.
description: YouTube Music 3.31 reveals work on a “retail mode” to help increase adoption.
image: https://res.cloudinary.com/read-write-tech/image/upload/v1567526715/APK-Insight-YouTube-Music-3-31_wxtblc.webp
optimized_image: https://res.cloudinary.com/read-write-tech/image/upload/c_scale,h_200,w_380/APK-Insight-YouTube-Music-3-31_wxtblc.webp
author: shan
paginate: true
---

After adding Waze integration, library sorting, and new “Released” playlist in recent weeks, the latest version of Google’s primary streaming service is rolling out. YouTube Music 3.31 reveals work on a “retail mode” to help increase adoption.

***About APK Insight:*** In this APK Insight” post, we’ve decompiled the latest version of an application that Google uploaded to the Play Store. When we decompile these files (called APKs, in the case of Android apps), we’re able to see various lines of code within that hint at possible future features. Keep in mind that Google may or may not ever ship these features, and our interpretation of what they are may be imperfect. We’ll try to enable those that are closer to being finished, however, to show you how they’ll look in the case that they do ship. With that in mind, read on.

***Retail mode***
In May, Bloomberg reported that there are 15 million YouTube Music subscribers a year after launch. The app has slowly added new features and rolled out to more countries around the world.

```xml
<string name=”retail_mode_intro”>A new music streaming app. Made by YouTube.</string>
```

YouTube Music 3.31 reveals that a “retail mode” is in development. This is presumably aimed at increasing adoption by letting people test the service in stores when they’re also buying phones. Google could make YouTube Music a part of future Pixel demos, as the Pixel 3 last year offered six months of YouTube Music Premium.

Google introduces the service as “A new music streaming app. Made by YouTube.” Touted functionality includes official versions — along with “Live performances, remixes & covers” — and “Personalized recommendations.” All these features are already found in the app today, while past advertising efforts included sponsoring New Year’s Eve coverage and music awards.

```xml
<string name=”retail_mode_albums_header”>Official albums, singles &amp; more</string>

<string name=”retail_mode_albums_subtext”>Listen to official songs, albums, charts, and playlists for any genre and mood</string>
```
```xml
<string name=”retail_mode_catalog_header”>Live performances, remixes, &amp; covers</string>

<string name=”retail_mode_catalog_subtext”>Explore our catalog and discover hard to find songs, remixes, and more</string>

```
```xml
<string name=”retail_mode_recommendations_header”>Recommendations based on taste, location, &amp; time of day</string>

<string name=”retail_mode_recommendations_subtext”>Personalized recommendations to help you discover new music</string>
```
***Allow external devices to start playback***
YouTube Music is getting another feature from Play Music that allows “external devices to start playback.” This includes wired headsets and when your phone is connected to a car over Bluetooth.

```xml
<string name=”pref_restore_on_media_button_title”>Allow external devices to start playback</string>

<string name=”pref_restore_on_media_button_summary”>For example, car Bluetooth, wired headsets</string>
```
![Play Music](https://res.cloudinary.com/read-write-tech/image/upload/v1567526909/play-music-bluetooth_hyxahn.png)

***How to update?***

YouTube Music 3.31 is rolling out now via the [Play Store](https://play.google.com/store/apps/details?id=com.google.android.apps.youtube.music).
