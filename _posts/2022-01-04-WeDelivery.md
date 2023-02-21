---
layout: post
topmost: false
title: WeDelivery
categories: FullStackWebsite Java Spring ReactJS Hibernate AWS
description: WeDelivery
keywords: FullStackWebsite
---

Time: Dec.2021 - Jan.2022 &emsp; Location: Seattle, USA

[WeDelivery](https://github.com/Leluth/WeDelivery) is a Spring and React based dispatch & delivery management application. Our service is to use robots and drones to help users in San Francisco deliver small and medium-sized packages.

Front-end part is implemented by Javascript, CSS, html and React, backend is executed in Java environment, with assistance of libraries of Spring framework, Hibernate and Tomcat. Database used for storing users' input was established on MySQL instance of AWS RDB system.

The introduction of details could be seen in [slides](https://github.com/Leluth/WeDelivery/blob/main/images/LaiDelivery%201.0%20Demo.pdf).

The demo video could be seen at [demo link](https://www.youtube.com/watch?time_continue=1&v=04vbk0RKcxw&feature=emb_title)

## What can we do on this website
1. At beginning, here's the welcome page that you could start our webapp or enter a tracking number to know where your package is.![welcome](/images/posts/java/wedelivery-welcome.png)

2. At first page, please enter the account and password for log in. If it's your first time visiting the website, please hit *Register* button on top-right corner

2. Enter the information about your account, please note that error might pop-up if the content does not meet requirements.

3. After registration, you should be able to get back to home page, then enter your registered account and password. Hit the eyeball could show the password you entered.
![register&login](/images/posts/java/wedelivery-login.gif)

4. Here's the main page of creating new package or organizing previous package list, hit add *Add new package* button if you want to add more packages.
![packagelist](/images/posts/java/wedelivery-packagelist.gif)

5. Input the information of the package you would like to deliver.
![packageinput](/images/posts/java/wedelivery-package_input.gif)

6. Options will pop up so that you could choose to use either drone or robot as your preferred delivery carrier. Use *radio button* for making decision.
![options](/images/posts/java/wedelivery-options.png)

7. Hit *add* button to add to be delivered packages into cart, and press *Cart* to see the total price and added orders. Hit *CheckOut* if you wish to complete the order.
![checkout](/images/posts/java/wedelivery-checkout.png)

8. Once checkout completes, you will get an notification sent to your email address for the use of tracking your package. 
![mail](/images/posts/java/wedelivery-notification.png)

9. You could enter the package number at welcome package or hit *Track* button on top-right corner to head into tracking page. Here you could know where your package is, and the estimated pick up / delivery time.
![track](/images/posts/java/wedelivery-tracking.png)

10. Ready for your or your friend to receive the gift!