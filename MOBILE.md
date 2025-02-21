# Mobile Project Portfolio Overview
**Michael Wielgosz**\
Last edited on: February 20, 2025

This document highlights mobile applications that I have developed or worked on to some capacity

## Table of Contents

[The Helping Friendly App (Android)](#the-helping-friendly-app-android)

[The Helping Friendly App (Flutter)](#the-helping-friendly-app-flutter)

[Simple-Calendar](#simple-calendar)

[Simple-Contacts](#simple-contacts)

[Simple-Commons](#simple-commons)

[Secret Dreams Music Festival (Flutter)](#secret-dreams-music-festival)

[Resonance Music and Arts Festival](#resonance-music-and-arts-festival)

[Sekwel Tablet App](#sekwel-tablet-app)

[Sekwel Mobile App](#sekwel-mobile-app)

[AOSP Project Work](#aosp-project-work)

## The Helping Friendly App (Android)

<https://github.com/mwielgosz/TheHelpingFriendlyApp>

Written in Kotlin utilizing Jetpack Compose. Developed by myself from the ground up in order to provide a native Android app. This app utilizes the [phish.net](https://api.phish.net/) API and displays data to users. Still in development – a very large update is near completion and will add network and database functionality.

-   Uses Retrofit and OKHttp libraries to pull JSON data from the RESTful API asynchronously and with error checking

-   The entire UI is created with Jetpack Compose

-   Room is being implemented for local database storage and retrieval options as to not pull from the API unless an update is required

-   Migrating from MVVM to MVI design patterns

## The Helping Friendly App (Flutter)

<https://github.com/mwielgosz/The-Helping-Friendly-App_Flutter>

Written in Flutter/Dart and developed by myself from ground up in order to provide a cross-platform codebase for Android and iOS applications. This app utilizes the [phish.net](https://api.phish.net/) API and displays data to users. Still in development.

-   Pulls show data from the “show.json” endpoint and displays to user in the “All Shows” bottom navigation button. Displays full show details upon user click

-   Pulls setlist data from the “setlists.json” endpoint and displays to user in the “Setlists” bottom navigation button. Displays full show details upon user click

-   User can search for a specific setlist by date in “YYYY-MM-DD” format. Will warn user on invalid input

-   Deployable to both Android and iOS platforms

## Simple-Calendar

<https://github.com/mwielgosz/Simple-Calendar>

A fork of a maintained version of the AOSP Calendar, I have updated this package to use the latest dependency versions, build against Android platform 35 (Android 15), and corrected any build time, runtime, or UI errors. Most notably, the introduction of “EdgeToEdge” in Android 15.

-   Updated all dependencies

-   Enabled edgeToEdge() on applicable Activities

-   Added inserts so app does not draw behind the notification or navigation bar on applicable Activities

## Simple-Contacts

<https://github.com/mwielgosz/Simple-Contacts>

A fork of a maintained version of the AOSP Contacts, I have updated this package to use the latest dependency versions, build against Android platform 35 (Android 15), and corrected any build time, runtime, or UI errors. Most notably, the introduction of “EdgeToEdge” in Android 15.

-   Updated all dependencies

-   Enabled edgeToEdge() on applicable Activities

-   Added inserts so app does not draw behind the notification or navigation bar on applicable Activities

## Simple-Commons

<https://github.com/mwielgosz/Simple-Commons>

A fork of a library which all of the “Simple” app families utilize. This package has been updated to use the latest dependency versions including Kotlin 2.0 and Compose compiler.

-   Updated all dependencies

-   Enabled edgeToEdge() on applicable Activities

-   Added inserts so app does not draw behind the notification or navigation bar on applicable Activities

-   Removed dead links and app checks that were causing crashes

## Secret Dreams Music Festival

[Secret Dreams Music and Arts Festival](https://www.secretdreamsfest.com) information app built from the ground up by myself in Flutter/Dart and is cross-platform with Android and iOS. Distributed on the [Google Play](https://play.google.com/store/apps/details?id=com.infiniwaresolutions.secret_dreams.release) and [Apple Stores](https://apps.apple.com/us/app/secret-dreams-music-festival/id1628198649) since 2022. While I did not create the graphics, I did resize and optimize them for mobile.

-   Shows attendees all available information concerning the Secret Dreams music festival in categorized screens

-   Implements left hand drawer navigation for easy screen navigation

-   Utilizes a “bulletin board” API that operators of Secret Dreams can post to. The app sends REST requests to the API and displays them as “News & Updates”

-   Distributed on Google Play and Apple Stores

[<img src="https://infiniwaresolutions.com/gallery/google-play-badge-ts1630024561.png?ts=1721078052" width="150">](https://play.google.com/store/apps/details?id=com.infiniwaresolutions.secret_dreams.release) [<img src="https://infiniwaresolutions.com/gallery/apple-app-store-black-ts1661025588.svg?ts=1721078052" width="150">](https://apps.apple.com/us/app/secret-dreams-music-festival/id1628198649)

## Resonance Music and Arts Festival

[Resonance and Arts Festival](https://resonancemusicfest.com) information app built from the ground up by myself in Kotlin for Android and Swift for iOS. Distributed on the [Google Play](https://play.google.com/store/apps/details?id=com.infiniwaresolutions.entertainmentschedule.resonance) and Apple Stores in 2021 (still available on [Google Play Store](https://play.google.com/store/apps/details?id=com.infiniwaresolutions.entertainmentschedule.resonance)). While I did not create the graphics, I did resize and optimize them for mobile.

-   Shows attendees all available information concerning the Resonance music festival in categorized screens

-   Implements left hand drawer navigation for easy screen navigation

-   Distributed on Google Play and Apple Stores


[<img src="https://infiniwaresolutions.com/gallery/google-play-badge-ts1630024561.png?ts=1721078052" width="150">](https://play.google.com/store/apps/details?id=com.infiniwaresolutions.entertainmentschedule.resonance)

## Sekwel Tablet App

Not all work can be bulletpointed

Proprietary app developed while I was working at [Sekwel Systems](http://sekwel.com). A specialized application developed for large- scale enterprise use of Android tablets as desktop interfaces. Written in Java for Android tablets, there is no part of this app that I did not either modify or build.

-   Sync with custom remote RESTful API database

-   Integrated Bluetooth connectivity and SIP calling

-   Deep integration to custom Android Open Source (AOSP) firmware. Sekwel AOSP firmware work is not listed here as it is a repeat of my resume.

## Sekwel Mobile App

Proprietary app developed while I was working at [Sekwel Systems](http://sekwel.com). Developed mobile Android application for monitoring and control of Android tablet application myself from the ground up. Android application written with Java and iOS written in Objective-C.

-   Sync with custom remote RESTful API database for tablet lock status and interaction

-   Displays notifications on device notifying user of tablet/workstation lock status

## AOSP Project Work

[Savaged-Zen ROM](https://github.com/savaged-zen)

[Crossbones ROM](https://github.com/crossbones)

Custom Android Open Source (AOSP) firmware built and distributed for specific devices.

-   Custom kernel optimized for device speed

-   Built and deployed app in order to control kernel configuration

-   Implemented upgrades to Android Open Source Project applications such as the MMS app. This application originally relied on cell towers to split long SMS messages and some networks do not automatically handle this. Added the option for users to enable the app to split message by encoding type and display how many messages will be sent and how many characters the user has remaining in current message
