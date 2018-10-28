# Awesome FLOSS Mobile

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

We have many operating systems, apps and hardware projects, trying to push for a free/libre/open source mobile device. This page attempts to compile all these projects, state the project goals, and to give a real world review. With this you will know what to throw your support behind.

# Android

## Core Android Apps

These apps intend to replace the "core" system apps that any user would expect. These download/update apps and provide APIs for apps to use.

* [F-Droid](https://f-droid.org/) - Repository and app containing only FLOSS software. Has a decent selection. Also check out the [Privileged Extension](https://gitlab.com/fdroid/privileged-extension/#f-droid-privileged-extension) if you are root, so you can install and remove apps in the background without having to confirm.
* [microG](https://microg.org/) - FLOSS reimplementation of the Google Play Services middleware, a must have if you intend to run most Google Play Apps. (hard to install, you should use a pre-configured custom rom instead).
* [Yalp Store](https://f-droid.org/en/packages/com.github.yeriomin.yalpstore/) - Grabs APKs directly from Google Play and facilitates updates.

## Android Forks

The Android Open Source Project is licenced under Apache 2.0. However most versions ship with the proprietary Google Play Services ingrained into the OS. Which harms the user.

* [LineageOS](https://lineageos.org/) - A fork of Android with it's own set of default apps and extra features. G-Apps are optional and should be avoided if can.
* [LineageOS with microG](https://lineage.microg.org/) - This fork of LineageOS is pre-configured with microG and F-Droid with the privilege extension.
* [eelo (beta)](https://e.foundation/) - New project from a veteran open-source developer/supporter, huge emphasis on privacy and control and attractiveness. It comes with microG, new default apps, account manager, new search engine and online "cloud" services.
* [Replicant](https://www.replicant.us/) - A fully FLOSS Android OS, that runs absolutely no proprietary firmware/drivers/microcode. Uses F-Droid as it's app store and is approved by the FSF. Only runs on (very) old phones.

## Android Apps

| Key   | Value                                       |
|-------|---------------------------------------------|
| **F** | Available on F-Droid.                       |
| **W** | Only available from the publishers website. |

### Essential Apps

Must-have apps, with direct links to either F-Droid or the APK from the official website.

* **F** | [Fennec F-Droid](https://f-droid.org/packages/org.mozilla.fennec_fdroid/) - F-Droid fork of Firefox, removes proprietary bits found in Mozilla's builds.
* **W** | [VLC](https://www.videolan.org/vlc/download-android.html) - The ultimate media player.
* **F** | [OpenCamera](https://f-droid.org/packages/net.sourceforge.opencamera/) - A good camera app, It's more configurable and generally takes better photos then the default camera apps.
* **F** | [Simple Gallery](https://f-droid.org/en/packages/com.simplemobiletools.gallery/) - A simple gallery app, has all gallery features one would expect.
* **F** | [Amaze](https://f-droid.org/en/packages/com.amaze.filemanager/) - A good FLOSS file manager. Looks good, works well, and has extra features.
* **F** | [AnySoftKeyboard](https://f-droid.org/en/packages/com.menny.android.anysoftkeyboard/) - Multilingual keyboard with spell check and plenty of configuration options.
* **F** | [Document Viewer](https://f-droid.org/en/packages/org.sufficientlysecure.viewer/) - Probably the best document viewer on Android. It is fast and supports PDF, DjVu, XPS and EPUB among others.
* **F** | [OsmAnd](https://f-droid.org/en/packages/net.osmand.plus/) - Powerful offline map app, shows public transport and hiking symbols among driving features.
* **F** | [Maps](https://f-droid.org/en/packages/com.github.axet.maps/) - F-Droid fork of Maps.ME. It's fast, easy and offline, but no hiking tools, and rudimentary routing.
* **F** | [Simple Calendar](https://f-droid.org/en/packages/com.simplemobiletools.calendar/) - A more simple solution to LineageOS' default app. Works well for events and has reminders.
* **F** | [Editor](https://f-droid.org/en/packages/org.billthefarmer.editor/) - A simple text editor, could be used to store notes in a simple fashion.
* **F** | [Survival Manual](https://f-droid.org/en/packages/org.ligi.survivalmanual/) - Learn how to survive. Based on the Army Field Manual 21-76 - fully working offline.
* **F** | [K-9 Mail](https://f-droid.org/en/packages/com.fsck.k9/) - Mail client with multiple accounts, POP3, IMAP Push IMAP, OpenPGP if [OpenKeychain](https://f-droid.org/fr/packages/org.sufficientlysecure.keychain/) installed.
* **F** | [AFWall+](https://f-droid.org/en/packages/dev.ukanth.ufirewall/) - Firewall (iptables front-end) which allows you to choose which are allowed to connect to the Internet. 

### Nice Apps

Tertiary apps. Nice to have, but not required for basic operations

* **F** | [Feeder](https://f-droid.org/en/packages/com.nononsenseapps.feeder/) - No frills RSS feed reader.
* **F** | [Flym](https://f-droid.org/en/packages/net.frju.flym/) - A modern RSS feed reader.
* **F** | [AntennaPod](https://f-droid.org/packages/de.danoeh.antennapod/) - Podcasting Manager, lets you download/stream and manage podcasts. Can add podcasts from iTunes, gpodder.net, OPML files, or RSS feed URLs.
* **F** | [NewPipe](https://f-droid.org/en/packages/org.schabi.newpipe/) - Lightweight YouTube/Soundcloud frontend.
* **F** | [Slide](https://f-droid.org/en/packages/me.ccrama.redditslide/) - Feature-packed and material-designed Reddit client.
* **F** | [Markor](https://f-droid.org/en/packages/net.gsantner.markor/) - A powerful text editor and note manager with Markdown support.
* **F** | [Termux](https://f-droid.org/en/packages/com.termux/) - A terminal emulator built for Android, with its own repos. [Hacker's Keyboard](https://f-droid.org/en/packages/org.pocketworkstation.pckeyboard/) is recommended.
* **F** | [Unit Converter Ultimate](https://f-droid.org/en/packages/com.physphil.android.unitconverterultimate/) - A simple and easy-to-use unit converter to handle any conversion you'll ever need.
* **F** | [LibreTorrent](https://f-droid.org/en/packages/org.proninyaroslav.libretorrent/) - Torrent Client.
* **F** | [Ameixa](https://f-droid.org/en/packages/org.xphnx.ameixa/) - A FLOSS icon pack for FLOSS apps.
* **F** | [Material Tea Timer](https://f-droid.org/packages/org.ligi.materialteatimer/) - Time your tea brewing.
* **F** | [Soft Sound](https://f-droid.org/en/packages/org.mcxa.softsound/) - Plays relaxing sounds like rain, storms and camp fires.
* **F** | [Binaural Beats](https://f-droid.org/en/packages/com.github.axet.binauralbeats/) - Helps you to relax and meditate.
* **F** | [Shattered Pixel Dungeon](https://f-droid.org/en/packages/com.shatteredpixel.shatteredpixeldungeon/) - Rouge-like game.
* **F** | [Minetest](https://f-droid.org/en/packages/net.minetest.minetest/) Voxel sandbox game, with multiplayer. Some has made a [mod manager](https://f-droid.org/en/packages/com.rubenwardy.minetestmodmanager/).
* **F** | [SuperTuxKart](https://f-droid.org/en/packages/org.supertuxkart.stk/) - Good 3D kart racing game (similar to Mario Kart)
* **F** | [Cow's Revenge](https://f-droid.org/en/packages/org.pipoypipagames.cowsrevenge/) - Fun platform game made in Godot Engine.
* **F** | [Anuto TD](https://f-droid.org/en/packages/ch.logixisland.anuto/) - A simple tower defence game..
* **W** | [ScummVM](https://www.scummvm.org/) - Allows you to play old point and click games, plays well on Android.
* **W** | [RetroArch](https://www.retroarch.com/?page=platforms) - A front-end for emulators, game engines and more. This allows compatible engines (known as cores) to intergrated into one place, and media
* **F** | [J2ME Loader](https://f-droid.org/en/packages/ru.playsoftware.j2meloader/) - J2ME Emulator. This will play some old Motorola games.

# GNU/Linux

## GNU/Linux-based operating systems

These operating systems aren't based on Android, but are instead purpose-built GNU/Linux operating systems.

* [Ubuntu Touch](https://ubuntu-touch.io/) - Ubuntu ported to mobile, interesting, pleasing and gesture-based UI. Has its own [app ecosystem](https://open-store.io/). Works well on the (older but good) ["promoted devices"](https://ubports.com/devices/promoted-devices). Other devices probably won't work well if at all.
* [postmarketOS](https://postmarketos.org/) - Touch-optimized, pre-configured Alpine Linux with own packages, designed for mobile devices with the goal of keeping old phones functional and sustainable. Even if a device is supported, it may only be partial. You should check each device individually.
* [Sailfish](https://en.wikipedia.org/wiki/Sailfish_OS) - A GNU/Linux OS for mobile, has it's own ecosystem and Android support. However some components (such as the UI) are not FLOSS.

## GNU/Linux software

* [Plasma Mobile](https://www.plasma-mobile.org/) - The KDE Plasma desktop environment ported to mobile GNU/Linux!
* [Anbox](https://anbox.io/) - Compatibility layer that allows Android apps to run on any GNU/Linux system.
* [Shashlik](http://www.shashlik.io/) - Provides a way to run Android apps under a GNU/Linux desktop as easily and simply as possible.

## Ubuntu Touch Apps

* [uNav](https://open-store.io/app/navigator.costales) - OpenStreetMap-powered GPS/maps app with offline map function.
* [Podbird](https://open-store.io/app/com.mikeasoft.podbird) - Podcast manager.

# Hardware

## Free Hardware Projects

These are phones that aim to have "open hardware". This usually means it will either let you freely install what ever OS, or that it allows hacking, or that it runs with fully-free OS's. A fully free SoC is unlikely.

* [ZeroPhone](https://www.crowdsupply.com/arsenijs/zerophone) - A work-in-progress open source, Linux-powered, $50 smartphone. Based on the Raspberry Pi Zero, ESP8266 and Arduino.
* [Librem 5](https://puri.sm/products/librem-5/) - A work-in-progress premuim smartphone that is intended to respect security, privacy and freedom.
* [Necunos Mobile](https://necunos.com/mobile/) - A privacy centric open source phone. To-Be-Announced.
* [Neo900](https://neo900.org/) - An in-dev successor to the N900 phone with modern hardware (including LTE). Can run on a fully FLOSS OS, and allows you to install which ever OS you want.

## Recommended Android Phones

| Key    | Value        |
|--------|--------------|
| **Lo** | LineageOS    |
| **Ub** | Ubuntu Touch |
| **Eo** | eelo         |
| **Pm** | postmarketOS |
| **Re** | Replicant    |

* [OnePlus 5 (2017-06)](https://en.wikipedia.org/wiki/OnePlus_5) - **[Lo](https://wiki.lineageos.org/devices/cheeseburger)** - A newish OnePlus phone that supports LineageOS. 
* [OnePlus 5T (2017-11)](https://en.wikipedia.org/wiki/OnePlus_5T) - **[Lo](https://wiki.lineageos.org/devices/dumpling)** - The latest OnePlus phone that supports LineageOS.
* [Samsung Galaxy S9 (2018-03)](https://en.wikipedia.org/wiki/Samsung_Galaxy_S9) - **[Lo](https://wiki.lineageos.org/devices/starlte)** - The latest and greatest phone money can buy with official LineageOS support.
* [Moto G4/G4 Plus (2016-05)](https://en.wikipedia.org/wiki/Moto_G4) - **[Lo](https://wiki.lineageos.org/devices/athene)** - A somewhat low-end phone.
* [Fairphone 2 (2015-12)](https://en.wikipedia.org/wiki/Fairphone_2) - **[Lo](https://wiki.lineageos.org/devices/FP2)**, **[Ub](https://devices.ubuntu-touch.io/device/FP2)**, **[Pm](https://wiki.postmarketos.org/wiki/Fairphone_2_(fairphone-fp2))** - An ethically sourced, fairtrade smartphone that can be easily repaired.
* [OnePlus One (2014-04)](https://en.wikipedia.org/wiki/OnePlus_One) - **[Lo](https://wiki.lineageos.org/devices/bacon)**, **[Ub](https://devices.ubuntu-touch.io/device/bacon)**, **[Pm](https://wiki.postmarketos.org/wiki/OnePlus_One_(oneplus-bacon))** - A phone that came out of nowhere to challenge bigger flagships.
* [Nexus 5 (2013-10)](https://en.wikipedia.org/wiki/Nexus_5) - **[Lo](https://wiki.lineageos.org/devices/hammerhead)**, **[Ub](https://devices.ubuntu-touch.io/device/hammerhead)**, **[Pm](https://wiki.postmarketos.org/wiki/Google_Nexus_5_(lg-hammerhead))** - Old but gold. This phone works best with Ubuntu Touch's convergence.
* [Galaxy Note 2 (N7100) (2012-09)](https://en.wikipedia.org/wiki/Samsung_Galaxy_Note_II) - **[Re](https://redmine.replicant.us/projects/replicant/wiki/GalaxyNote2N7100)** - Very old, but will run a completely free OS.

# Misc.

* [NanoDroid](https://gitlab.com/Nanolx/NanoDroid/blob/master/README.md) - Flashable package containing microG, F-Droid and other FLOSS apps.

![Public Domain (CC0)](pd.png) CC0 Licenced.
