---
layout: post
title:  "Android without Google"
date:   2013-12-27 14:33
categories: android google f-droid
---

I've been an Android user since 2009, when I bought a used G1. Since
then I have owned a Nexus One, a Nexus 7 and now own a Nexus 4. After
upgrading to the Nexus 4, I was very disturbed by the amount of data
that was being sent back to Google. But I really liked the hardware,
and I have long been a fan of Android itself. So I tried to rid my
phone of any and all contact with Google - this posts details the
process.


# Base system

It might be possible to achieve this same effect without flashing a
different base system - by just not adding a Google account when you
first start the phone. But why settle for plain old AOSP when there
are any number of ROMs which implement excellent modifications?
Personally I'm a big fan of Cyanogenmod, so I installed that first
up. The process in the CM wiki gives you a link for the Google apps,
and we will of course skip that last step.

# App repo

Now it doesn't make any sense to leave the bosom of one giant American
company and jump straight into anothers, so the Amazon app store is
out. There are a number of other app stores, but I went with one that
I could trust - [F-Droid][fdroid]. It is to Android what
the Debian repos are to Linux. All the apps are vetted for license and
source code availability (although not as rigorously as Debian just
yet, Firefox is still here after all :). The best part about the app
is that it does not have the permission to install apps by itself.
Instead it downloads the APK from the repo and simply uses the
standard Android installation prompt for confirmation.

The app selection on F-Droid is naturally quite limited. For instance,
none of the standard messaging apps -WhatsApp, Google Hangouts, BBM,
Viber, etc - are available. This may or may not be an advantage
depending on your social inclinations. However, all the basic needs
are covered - browser, email client, PDF viewer, map client, RSS
client, notepad, shopping list, time tracker and a bunch of other
delightfully whacky apps like Juggling Lab and Frex.

The apps that I couldn't find on F-Droid were proprietary clients of
proprietary web services, and recent news has proved (if proof was
necessary) that it is a bad idea to send all your data to a server
that you have no control over, so good riddance to those services.

# Drawbacks

Of course it's a tradeoff. You give up your privacy for the
convenience of Google's services and when you decide to take back your
privacy you can expect to lose some convenience. The hardest part for
me has been living without Google Maps - and on this score I have
cheated a bit by installing the Google Maps apk on to my device
without signing in with a Google account. There are a couple of
interesting OSM clients like OSMAnd and RMaps, but I haven't had the
time to figure out their interfaces just yet. This is definitely on my
list.

The other major drawback is social. Be prepared to explain why you
can't install that app on your Nexus phone a hundred times. And if
you're lucky, most of them will give you a bemused look and leave you
alone. If not, you will have to get into an argument about Google's
privacy policies with someone both belligerent and ill-informed.

# Positives

Trust. I more or less blindly install apps from F-Droid. The source is
there to be seen by everyone, and it has been vetted before being
admitted to the repo, so I implicitly trust everything on there. It is
the exact opposite of the mindset I had on the Play store - distrust
everything, and look for reviews to prove otherwise.

Ads. I don't see ads in apps anymore.

Battery life. Who knew, when you don't have 10 different services all
phoning home and sending data once every 5 minutes, your battery life
improves dramatically.

# Linux for mobile

Canonical is working on "Ubuntu for phones", but I cannot understand
why. Linux is already present on mobiles - it is called AOSP. All that
is required is a comprehensive, vetted OSS repository for Android
applications. That is what F-Droid is attempting, and they have all my
support and thanks. Thanks also to developers of the applications
hosted on F-Droid. Onward and upward!

[fdroid]: https://f-droid.org/
