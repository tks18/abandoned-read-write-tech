---
date: '2019-09-08 20:34:29'
layout: post
title: Google app 10.57 Insight
subtitle: 'preps Continued Conversation on phones & more languages, Assistant dark theme'
description: 'preps Continued Conversation on phones & more languages, Assistant dark theme'
image: APK-Insight-Google-App-10-57_hjgcyh
category: app-insights
tags:
  - Assistant Dark Theme
  - Google App
author: Sudharshan TK
source_name: 9 to 5 Google
source_url: 'https://9to5google.com'
paginate: true
---
In addition to a Material Theme redesign of Podcasts, Google app 10.57 preps Continued Conversation on phones and four more languages. Work on a dark theme for Search and Assistant is still underway.

**About APK Insight:** In this ‘APK Insight’ post, we’ve decompiled the latest version of an application that Google uploaded to the Play Store. When we decompile these files (called APKs, in the case of Android apps), we’re able to see various lines of code within that hint at possible future features. Keep in mind that Google may or may not ever ship these features, and our interpretation of what they are may be imperfect. We’ll try to enable those that are closer to being finished, however, to show you how they’ll look in the case that they do ship. With that in mind, read on.

**Google Podcasts preps Material Theme redesign**

![Google Podcasts](https://res.cloudinary.com/read-write-tech/image/upload/v1567953035/google-podcasts-material-theme-1_d5ic8y.png "Podcasts App")

**Continued Conversation: Phones & more languages**

One aspect of the next-generation Assistant is Continued Conversation. Google app 10.57 readies the feature with a new animation that shows CC running on a phone and taking back-to-back voice commands without users having to repeat the “Hey Google” hotword. It leverages Android 10’s Assistant light bar to indicate when you’re speaking.

```
<string name=”opa_continued_conversation_optin_screen_title”>Turn on Continued Conversation to talk to your Assistant without repeating \u201cHey Google\u201d.</string>
```

```
<string name=”opa_continued_conversation_optin_screen_message”>”If Continued Conversation is off, you’ll need to say \u201cHey Google\u201d every time you ask your Assistant a follow-up question.”</string>
```

```
<string name=”opa_continued_conversation_optin_screen_secondary_message”>You can change this setting anytime in Assistant Settings.</string>
```

Strings also detail the prompt that users will see to enable the functionality. Meanwhile, an updated message for Googlers this release shows how Continued Conversation is still being tested internally in Germany, and soon Spanish, French, Italian, and Japanese. It’s important for Google to expand the functionality’s reach before it launches on phones and other Assistant devices.

```
<string name=”assistant_settings_summer_time_mode_availability_clarification_override”>”Continued Conversation is currently available for English. If you use devices not shown here, the person with the primary account on those devices may turn Continued Conversation on or off in their Assistant settings.\nWe are also currently dogfooding the following locales:German, Spanish, French, Italian and Japanese.”</string>
```

**Google app dark theme**

Following Android 10’s launch on Tuesday, the Google app and Assistant are still lacking dark themes. Google app 10.57 continues development on the look with the setting now called “Theme.” Google Search is also using a shorter header.

![Google App](https://res.cloudinary.com/read-write-tech/image/upload/v1567955423/google-app-10-57-dark-theme-2_dmg8lt.png "Google App")

**Assistant Updates FAB**

Back in June, we spotted a FAB to add reminders, events, and notes to the Assistant Updates feed. The latest iteration slides up a panel with those three options and “shopping item.”
