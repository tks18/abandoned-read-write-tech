---
date: 2020-05-24 17:51:40 +0530
layout: post
title: Google Messages prepares end-to-end encryption for RCS
subtitle: End-to-End Encryption for RCS
description: End-to-End Encryption for RCS
image: https://www.xda-developers.com/files/2019/10/Google-Messages-featured-810x298_c.jpg
image_source: XDA
image_source_url: https://xda-developers.com
category: app-insights
tags:
  - Google Messages
  - RCS
  - EndtoEnd
author: Sudharshan TK
source_name: XDA
source_url: https://xda-developers.com
paginate: true
---
Earlier today, our friends at AndroidPolice got their hands on Google Messages 6.2.031 and uploaded it to APKMirror. Our friend Quinny899 notified us that this APK is actually a dogfood build, meaning it was not supposed to be released to the public. Sometimes, these dogfood builds have a lot of interesting code for features that are in development, and Messages 6.2.031 is definitely one of those cases. This dogfood build hints that Google is preparing end-to-end encryption for RCS messages, Google Fi account integration to sync calls, texts, and voicemails, and manual cloud restores of backups.

#### End-to-End Encryption for RCS

RCS is widely seen as the successor to SMS. With RCS, users can exchange media files in high quality, see read receipts, see typing indicators, start group chats, and do more over mobile data and even Wi-Fi. Rather than wait for carriers to adopt the RCS protocol on their own, Google started to roll out RCS support in the Google Messages app for everyone in the UK and France. They later rolled out RCS support in the Messages app for people in the US, Spain, Italy, Singapore, Portugal, Argentina, Pakistan, Poland, and Turkey.

One feature that popular messaging apps like WhatsApp and Telegram support but RCS hasn’t is end-to-end encryption, but it looks like Google is preparing to add support for that on their own end. The biggest new feature that is in the works in Google Messages 6.2.031 is “End-to-End Encrypted Rich Communication Service message[s].” According to the strings, you’ll have the option to send messages with end-to-end encryption or, if your data connection is poor, without encryption by falling back to SMS/MMS.

#### Google Fi integration

Another new feature that many users are looking forward to is Google Fi integration. Although Google Hangouts is on its way out, it’s still recommended to users who want to see and respond to their calls, texts, and voicemails on multiple devices. That could change soon, however, as Google Messages is preparing to pick up the slack.

When you sign in to your Google Fi account in Google Messages, you’ll have the option to transfer conversation history from Hangouts to Messages. Unfortunately, you won’t be able to sync messages or voice calls to a computer if you enable RCS in Message. If you disable multi-device sync in settings, you’ll also be unable to access calls and voicemails on the web but you’ll continue to be able to text from the web.

#### Backup & Restore

Finally, two layout files were added hinting at a new settings page to restore messages backed up on the cloud: restore_activity_layout.xml and restore_fragment_layout.xml. The backup service in Google Play Services, as well as the backup service in Google One, can backup and restore your messages when you initially sign into a new device. It seems that Google Messages will let you choose to manually restore a previous backup of your conversations.

You can download the latest version of the Google Messages app from the Google Play Store link below. Note, however, that the dogfood build version 6.2.031 won’t be available through Google Play and can only be downloaded through APKMirror.