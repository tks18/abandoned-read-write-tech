---
date: '2019-09-12 11:18:07'
layout: post
title: Google Translate 6.2
subtitle: 'Fixes ‘Tap to Translate’ on Android 10, preps ‘Continuous Translation’'
description: 'Fixes ‘Tap to Translate’ on Android 10, preps ‘Continuous Translation’'
image: APK-Insight-Google-Translate-6-2_x7gyqn
image_source: 9 to 5 Google
image_source_url: 'https://9to5google.com'
category: app-insights
tags:
  - Google Translate
  - Continous conversation
author: Sudharshan TK
source_name: 9 to 5 Google
source_url: 'https://9to5google.com'
paginate: true
---
During the Android Q Betas, Google Translate’s “Tap to Translate” did not work. Following Android 10’s launch last week, a new version of the app fixes the feature and makes it more subtle. Meanwhile, version 6.2 hints at a continuously audio translation mode.

**About APK Insight:** In this ‘APK Insight’ post, we’ve decompiled the latest version of an application that Google uploaded to the Play Store. When we decompile these files (called APKs, in the case of Android apps), we’re able to see various lines of code within that hint at possible future features. Keep in mind that Google may or may not ever ship these features, and our interpretation of what they are may be imperfect. We’ll try to enable those that are closer to being finished, however, to show you how they’ll look in the case that they do ship. With that in mind, read on.

**Tap to Translate**

When Tap to Translate is enabled from settings, copying text will pop-up a chat bubble with the Google Translate icon. Pressing reveals a panel with what you copied already filled in.

Before version 6.2 today, the floating icon would not appear on Android 10 following a copy. There was no way to pre-populate the translation window with text, thus reducing the feature’s convenience.

![Translate](https://res.cloudinary.com/read-write-tech/image/upload/v1568267495/google-translate-6-2-tap-2_l3blxq.png "Translate")

Today’s update addresses the bug and returns full functionality on Android 10. On the new OS, Google has also made Tap to Translate work in a more subtle manner. Previously, the chat bubble would quickly disappear following each use and reappear with an annoying pulsing animation after every copy.

Now, its persistent with the alert in Android 10’s notification shade adding a manual “Show/Hide floating icon.” Users can copy text for other reasons and only open the chat bubble when a translation is needed.

**Continuous Translation**

Google Translate 6.2 reveals work on the ability to “continuously translate from voice input.” The existing single person “Voice” input is just speech-to-text and ends after you finish speaking. This upcoming functionality appears to be geared for longer entry, with only English supported initially.

```
<string name=”title_listen_welcome_dialog”>Continuous Translation</string>
```

```
<string name=”msg_listen_welcome_dialog”>This new feature lets you continuously translate from voice input. Place the phone as close to the audio source for best results.</string>
```

```
<string name=”msg_no_listen_mode_for_input_lang”>Only English input is supported</string>
```
