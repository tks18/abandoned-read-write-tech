---
date: '2019-09-10 19:44:51'
layout: post
title: >-
  Private Instagram posts and stories can be shared publicly using just a web
  browser
subtitle: A serious flaw in how Instagram handles private accounts
description: A serious flaw in how Instagram handles private accounts
image: akrales_180614_1777_0229.0_edwv11
image_source: The Verge
image_source_url: 'https://theverge.com'
category: blog
tags:
  - Instagram Flaw
  - Private Accounts
author: Sudharshan TK
source_name: The Verge
source_url: 'https://theverge.com'
paginate: true
---
Instagram has a security flaw in the way it handles posts on accounts that have been set to private, BuzzFeed reported today. The report illustrates how a series of mouse clicks on any web browser can expose the persistent URL of private posts and stories cached on Facebook servers.

Anyone can use a web browser, like Google Chrome, to inspect the source code on a web page using the “Inspect Elements” tool. By tabbing over to the “Img” section of the Network header, you’re able to find the URL of any Instagram image you’ve clicked on, be it a disappearing story or a photo posted to a user’s feed. That URL can then be shared and the photo viewed by anyone, including people who do not follow the private account in question.

The Verge was able to independently verify that this process does indeed work. The process is somewhat finicky, but usually by reloading the page of a private account (in this case, my own) and loading the “Img” section, I was able to find the right URL and confirm it could be openly shared. Previews of the image even load in chat applications like Slack. We also confirmed another user was able to find the same URLs, to rule out the possibility that Instagram was only making available this type of data to a user looking at their own private account.

In addition to revealing persistent URLs for photos posted to a private account, the same source-code trick also lets you pull URLs for profile photos of other Instagram users who may have interacted with that post and may have their accounts set to private as well. Of course, you must follow the private account in the first place to have access to the user’s feed and stories, but the flaw and the ease of exploiting it represent an oversight for Instagram’s privacy and security teams.

According to BuzzFeed, these URLs will still retrieve images from Facebook servers even after the posts have been deleted. This appears to be true both for photos posted to the feed and for stories, which delete after 24 hours. BuzzFeed says URLs for private stories will return the story for multiple days after the expiration date. The report also states that the same method works for retrieving URLs of private Facebook posts and photos, although The Verge has not yet been able to independently verify that.

According to Facebook, this type of behavior — seeking out the URL of a private photo so it can be more easily shared publicly — is not dissimilar from taking a screenshot of a pos. The company says it has not seen any abuse related to this feature of its network. “The behavior described here is the same as taking a screenshot of a friend’s photo on Facebook and Instagram and sharing it with other people. It doesn’t give people access to a person’s private account,” a company spokesperson tells The Verge.
