# HoroCMS — Installation guide

*Beta 0.2.4*

How to install HoroCMS on a Mac or a Windows PC and the companion on a phone, set it up, update it, move it to another computer and remove it.

## Requirements

- macOS 13 Ventura or later (Apple silicon or Intel), or Windows 10 or 11 (64-bit).
- Phone companion (optional): Android 8 or later (64-bit), on the same Wi-Fi network as the computer. The iPhone companion (iOS 15 or later) is not yet offered to the public.
- About 100 MB of disk space for the app, plus room for your photos and documents.
- No internet connection is needed. HoroCMS goes online only for the update check (www.leger.ca and GitHub, can be turned off), official exchange rates (Bank of Canada, if you turn them on) and the online assistant (Anthropic, if you turn it on).

## Getting the installer

HoroCMS is free. Download it from the public download page:

https://github.com/ITriskMgr/HoroCMS-updates/releases/latest

Under Assets, choose the file for your system: HoroCMS-Mac.dmg for a Mac (Apple silicon or Intel), HoroCMS-Windows-Setup.exe for Windows (or the .msi), and HoroCMS-Android.apk for an Android phone. No account is needed. The same page has these guides as PDF files.

## Installing on a Mac

1. Download HoroCMS-Mac.dmg from the download page (see Getting the installer) and open it.
2. Drag HoroCMS into Applications, then open it from Applications.
3. The beta is not yet signed by Apple, so macOS stops it the first time. On macOS 15 Sequoia or later: choose Done, open System Settings › Privacy & Security, scroll down to HoroCMS was blocked, choose Open Anyway, confirm with your password, then Open. On macOS 13 or 14: right-click HoroCMS in Applications, choose Open, then Open again.

If macOS says HoroCMS is damaged, open Terminal and run xattr -dr com.apple.quarantine /Applications/HoroCMS.app, then open it again. macOS asks only once.

To update, install the new version the same way; your vault and settings are kept. HoroCMS runs on macOS 13 Ventura or later (Apple silicon and Intel).

## Installing on Windows

1. Download HoroCMS-Windows-Setup.exe from the download page (see Getting the installer) and run it. The .msi does the same for managed computers.
2. If Windows SmartScreen says it protected your PC, choose More info, then Run anyway. The beta is not yet signed, so Windows warns once.
3. Follow the installer; HoroCMS appears in the Start menu.

HoroCMS needs Windows 10 or 11 with Microsoft Edge WebView2 (already present on current Windows; the installer adds it if needed). The vault is stored in your local application data, which is not synchronised by OneDrive.

## Creating your vault

HoroCMS keeps your collection in an encrypted vault on this computer. Nothing is sent anywhere.

1. Choose the language and the format for numbers and dates.
2. Choose a passphrase of at least 12 characters. Four or five unusual words are easy to remember and hard to guess.
3. Print or copy your recovery key, then retype its third group to confirm you have it.

Keep the recovery key away from the computer: with your watch papers, in a safe, or with your notary. It is the only way into the vault if you forget the passphrase.

## Installing the phone companion on Android

1. On the phone, open the download page in the browser (see Getting the installer) and download HoroCMS-Android.apk. Or download it on the computer and copy it to the phone (cable, Google Drive or email to yourself).
2. Open the downloaded .apk from the notification or the Files app.
3. Android asks once to allow installing apps from that source: allow it, then choose Install. You can turn the permission off again afterwards.
4. Open HoroCMS on the phone, choose a passphrase for the phone, then pair it (see Your collection on your phone).

It needs Android 8 or later on a 64-bit phone. If the new version refuses to install over the old one (a beta signed with another key), uninstall the old one first and pair again; nothing is lost, the collection comes back from your computer.

## Installing the phone companion on iPhone

The iPhone companion is not yet offered to the public: it will come through Apple’s TestFlight. Use Support in HoroCMS to ask to be told when it is ready.

Apple lets an app onto an iPhone only when it is signed by an Apple developer account. Until then, testers install it in one of two ways:

- TestFlight (recommended): with the Apple Developer Program (US$99 a year). The author builds the app with your Team ID and sends it to TestFlight; you install the free TestFlight app from the App Store, accept the invitation, then install HoroCMS. Updates arrive the same way.
- Xcode, without a paid account: on a Mac with Xcode and a free Apple ID, the app is installed by cable. It stops opening after 7 days and must be installed again.

1. Once installed, open HoroCMS on the iPhone and allow the camera (to read the pairing QR code) and the local network (to reach your computer) when asked.
2. Choose a passphrase for the phone, then pair it (see Your collection on your phone).

It needs iOS 15 or later. The technical steps for the author are in docs/MOBILE.md.

## Your collection on your phone

The HoroCMS companion for iPhone and Android shows your collection with its photos, lets you put a watch on and take it off, and keeps your wishlist. What you change on the phone comes back to your computer.

On the computer, open Settings › Phone companion and choose Turn on the phone companion, then Pair a phone (your passphrase is asked). On the phone, choose a passphrase for the phone, then Scan the code, or type the address and the code shown on the computer. Both must be on the same Wi-Fi network.

The phone keeps its own encrypted copy of the collection and locks itself when you leave the app. It talks only to your computer, on your home network, and only while HoroCMS is unlocked there; nothing goes through the internet. If your computers sync through a cloud folder, the phone also receives what the other computers send.

The first time, macOS or Windows may ask whether HoroCMS may accept incoming connections: allow it on private networks only. Turn the companion off in the same place when you do not need it. If you forget the phone’s passphrase, erase the phone’s data from its unlock screen and pair it again.

## Updating HoroCMS

When HoroCMS starts, it asks www.leger.ca and GitHub whether a newer version exists (only the app’s version number is sent). If one does, a banner offers it; Settings › Updates › Check now does the same at any time. Turn the start-up check off there to keep HoroCMS completely offline.

1. Make a backup (Settings › Backups). HoroCMS reminds you if the last one is more than a day old.
2. Click Install and restart. HoroCMS locks, downloads the update, checks that it is signed by its author (anything else is refused), installs it and restarts.
3. Unlock as usual. Your collection is carried over automatically: HoroCMS keeps a copy of it, brings it up to date, checks every record, and puts the copy back if anything is wrong.

Your vault, your preferences and your automatic backups stay where they are; an update never deletes them. Photos and documents are not touched.

You can also install a new version by hand, like the first time (see Installing on a Mac, or Installing on Windows): the same safe upgrade happens when you next unlock.

If HoroCMS says it could not bring the vault up to date, nothing was changed: reinstall the previous version to keep working and contact the author. A vault used by a newer version cannot be opened by an older one; update the app instead.

## Restoring a backup or moving to a new computer

On a new computer, choose Restore from a backup… on the first screen; on this one, use the unlock screen or Settings.

1. Choose the backup file (.horobak).
2. Type its passphrase.
3. Choose the passphrase for the restored vault.

Everything is checked before the current vault is touched; the current vault is kept aside. You receive a new recovery key to print.

## Backups

HoroCMS makes an encrypted backup automatically after you unlock, at most once a day, in HoroCMS’s own data folder (or a folder you choose; Settings › Backups › Show in Finder or Explorer opens it). It keeps the 10 newest. Each automatic backup opens with the passphrase you unlocked with that day.

To make one yourself, go to Settings › Backups, choose a passphrase for it and Save a backup…, then pick a place such as a USB key. Keep at least one copy away from the computer.

## When something goes wrong

HoroCMS checks everything it reads, so damage is detected rather than shown as wrong data. Two kinds of problem can happen after a disk failure or a crash.

The collection will not open, although the passphrase is right. HoroCMS then offers two ways back:

- Go back to an automatic copy: HoroCMS keeps one before each update. Changes made since are lost; photos and documents are not affected. The damaged file is kept aside.
- Restore a backup: choose your most recent one (see Restoring a backup or moving to a new computer).

Some photos or documents are missing or damaged. Settings › Vault health › Check the vault finds them. Choose a backup made when they were fine and type its passphrase: HoroCMS copies back only those files, after checking each one. Files not in any backup can then be removed from the record; the watch itself is not affected.

Keep backups on a USB key or another disk, not only on this computer: they are what makes every problem recoverable.

## Where your data lives

- Mac: ~/Library/Application Support/ca.leger.horocms/vault (encrypted).
- Windows: %LOCALAPPDATA%\ca.leger.horocms\vault (encrypted; not synchronised by OneDrive).
- Automatic backups: the Backups folder beside the vault (versions before 0.2.1 used Documents/HoroCMS Backups), unless you chose another folder.
- Preferences (language, theme, display currency): a small file in the system's settings folder; it contains nothing about your collection.

## Removing HoroCMS

Make a backup first (Settings › Backups). On a Mac, drag HoroCMS from Applications to the Trash; on Windows, use Settings › Apps › HoroCMS › Uninstall. The encrypted vault is left in place so that reinstalling finds your collection; delete the folder listed above if you want it gone.

---

© 2026 Marc-André Léger. All rights reserved. Built with Claude (Anthropic).
