---
layout: post
topmost: false
title: A Gesture-based Wheel-type Interaction Scheme on Android
categories: MobileApp Android Java
description: A Gesture-based Wheel-type Interaction Scheme on Android
keywords: Android MobileApp
---

Time: May.2018 - July.2018 &emsp; Location: Wuhan, China

During my internship at Wuhan Internet Accessible Company, I designed and implemented this interaction scheme to assist blind people with handling mobile phones more easily, which was then adopted throughout the mobile operating system for the blind. To enter an application, the blind people may spend over 2 minutes to find it with traditional mobile interaction scheme, while 2 seconds are enough in our mobile system.

![@2x](/images/posts/android/interaction-scheme.png){:height="70%" width="70%"}

In detail, the users can touch any part of the screen to activate a disk of the menu listing different applications. When they move a finger toward an application, the name of the app will be announced and the users can release the finger to enter into the application. 

![@2x](/images/posts/android/interaction-scheme2.png){:height="70%" width="70%"}

I conduct this interaction scheme by building an Android custom view with around 1400 lines of code in Java and XML. It can be called out on top of different applications, and then get and list interactive items of the current screen, providing a faster way for the blind people to operate mobile phones.

