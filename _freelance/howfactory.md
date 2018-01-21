---
title: HowFactory
path: howfactory
layout: project
slogan: Creating know-how has never been easier
color: '#00a9eb'
website: https://howfactory.com/
date: 2016-05-13
timeline: May 13, 2016 - Present
description: Platform for medium/large companies to capture know-how from current employees to train new employees. Offline-first Android/iPhone app to view and edit your company's know-how documentation.
location: Cedar Falls, Iowa, USA
status: in-dev
---
**What I am building:**

* Android, iOS native apps.
* Mobile app development lead.
* Development consulting.

## What is HowFactory?

![How factory logo](/img/freelance/howfactory/logo.png)

Manufacturing companies have a problem. The baby boomers are retiring and being replaced by new employees. What's what with that? The employees that have been working at that company for potentially decades have all of the know-how trapped inside of their head. The company is running of the risk of losing efficiency by all of this captured knowledge retiring and not being shared with new employees.

HowFactory is the solution. It is a SaaS product designed for process heavy companies to capture the knowledge of their employees on how to do certain tasks. These tasks can then be used to easily train all employees on how to use a machine, or how to perform an action.

HowFactory was part of the Iowa Startup Accelerator, [TechCrunch Battlefield](https://techcrunch.com/2015/05/04/howfactory-debuts-a-better-way-to-create-employee-training-and-instruction-manuals/), and raised $195k in seed round of funding.

## What does the app do?

**The Android app** gives the ability for users to create new processes (and edit existing processes) and view processes with full offline support.

**The iOS app** gives the ability for users to view processes online or offline.

## What technologies, tools, libraries did I use to build the app?

Android:

* Kotlin programming language (~60% of codebase is Kotlin. Started with 100% Java)
* Retrofit
* Eventbus
* Realm-java
* RxJava
* Shutter-Android

iOS:

* Swift 3
* Alamofire
* RxSwift/RxCocoa
* Realm-swift
* ObjectMapper
* Mac

## Technically, what is impressive about the app?

* **Full offline support**

The Android and iOS apps both have full offline support. Once you login, every action performed in the app is instantly saved to the device and synced with the backend system as soon as the user is online. What does this mean? 1. No loading screens. Everything you do in the app is instant. 2. Customers of the HowFactory app have moments where they are offline on the floor. With that in mind, they are able to view processes and edit them while on the floor offline and they will sync when they get back in the office.