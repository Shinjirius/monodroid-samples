---
name: Xamarin.Android - LocationUpdatesPendingIntent Sample
description: "Demonstrates how to use the Location API to get updates about a device's location using a PendingIntent (Android Oreo)"
page_type: sample
languages:
- csharp
products:
- xamarin
extensions:
    tags:
    - androidoreo
urlFragment: android-o-androidplaylocation-locupdpendintent
---
# LocationUpdatesPendingIntent Sample

This sample demonstrates how to use the Location API to get updates about a device's location using a PendingIntent.

![LocationUpdatesPendingIntent Sample application screenshot](Screenshots/Main.png "LocationUpdatesPendingIntent Sample application screenshot")

## Instructions

Sample shows implementation using an IntentService as well as a BroadcastReceiver.
Press the “Request Updates” button to start the location updates service and listen any location changes.
Press the “Remove Updates” if you do not want to listen any location updates.

## Build Requirements

Using this sample requires the Android 8.0 (API 26) and the Xamarin.Android 7.5.x or higher.

## License

Copyright (c) 2017 The Android Open Source Project, Inc.  
Ported from [Android LocationUpdatesPendingIntent Sample](https://github.com/googlesamples/android-play-location/tree/master/LocationUpdatesPendingIntent).  
