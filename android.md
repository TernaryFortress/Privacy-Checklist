# The problem child: Android

Many cheap or foreign android phones have built-in spyware, and there may literally be no help short of turning off your phone, depending on who made your phone and shipped your software.

Google has built backdoors into practically everything. I have yet to find a solution to their telemetry that doesn't involve just disabling Google Play Services and the Google Store entirely.

As soon as you enable Google Play Services, it force enables access to your on-device files, sensors, location, and a host of other permissions, with no ability to remove them.

The best way around this is to use Android's new Work Profile, however there's no clean application for actually configuring this. The only one in the Google Play Store, Island, collects your usage data *as well*.

Your phone carrier collects your usage data. It is impossible to prevent your phone's network provider from knowing where you are. Your location is necessary knowledge to enable 5G to work.

## My location needs to be private right now!

Enable airplane mode and leave it on until you're done. Google Services still collects your location data during this time unless disabled.

Use offline maps if you need to navigate while off the grid. Google Maps has an incognito mode, Magic Earth has good offline maps if you can protect the APK (see our Security Checklist).

Street cameras will still leak your location. You can't fix this - stick to highways as much as possible.

## Google services still has access to my microphone!

Android 14 has hardware disable buttons for the microphone. Turn it on. Turn it back on after every phone call.

## Google services still has access to my camera!

Android 14 also has a hardware disable button for the camera Turn it on. Turn it back on after every picture you take.

## Sensors are still leaking information!

Yes, it's a thing.

In developer mode, there's a setting to enable a hardware disable button for sensors. Search how to do this for your specific manuacturer

## Domain Name Service (DNS) is leaking information.

Even if you use a private DNS, Google still collects telemetry on your data usage using the domain "*-dnsotls-ds.metric.gstatic.com" because why would private mean private, right?

You'll want to use a service that enables blacklisting of domains (Cloudflare after submitting a "Do not sell my telemetry" request, pihole, etc)

You can use TernaryFortress's, which is: v9gab9k06l.cloudflare-gateway.com

If and only if you trust us, that is. We do not log your data, but we have the ability to, and without you ever knowing. Be aware.

Even then, some browsers use their own DNS servers, and can leak your website queries.

## My browser is leaking information.

Startpage has an android application built on Chromium that claims to not track you, if you're used to the Chrome experience.

Otherwise, check out our Firefox settings page if you prefer the Gecko experience.

## Google Keyboard is leaking my text information.

Yup, that's a thing too!

Typewise has a paid version of their app that has no telemetry.

OpenBoard and AnysoftKeyboard are both telemetry free, but don't have versions in the Google Play Store. You'd need to sideload the APK.

## This sucks and nothing functions anymore. How do I configure an android phone so that I can still do everything that I did before?

You can set up a work profile, though I'm still searching for one that is both monetarily free AND telemetry free.

If you want to play around, android has a demo available: https://www.android.com/enterprise/work-profile/

In the demo, you can't use the real Play Store, but you can still log in to your google account and install applications to the work profile using adb by adding the --user 10 parameter to the install command.

I advise against using the Island app that's in the Play Store, as they collect all your data.

Android has a "demo" work profile that you can configure on your phone. A work profile is like a second account on your phone.

Android 14 gives you a disable button *for the work profile itself*.

If you install the work profile, and then disable Google Play Services and Google Play Store on the normal profile, you can use the work profile to download and play games from the store, chat on social media, etc, and then *fully disable all of it* with the press of a single button.

Then everything in the base profile is (generally) safe from tampering, and you can keep all your important stuff there.

This is the best solution that I have found so far.
