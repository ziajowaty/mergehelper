# MergeHelper

Android helper for merge-style games: MultiClick (saved tap point, repeated taps) and MultiMerge (intelligent image search over user defined area; detects duplicates, merges them).
It was made for Merge Survival game UI specifically, but if your merge game has a grid board, the app will work!

This repository contains **no application source code**. It exists only to publish installable builds via [GitHub Releases](https://github.com/ziajowaty/mergehelper/releases).

**This app can cause banking, wallet, and payment apps to refuse login or flag your phone as “suspicious.”** That is a known side effect of how MergeHelper works—not a sign your account was hacked. Read [Banking apps and how to fix it](#banking-apps-and-how-to-fix-it) before you install if you use the same phone for banking.

This app has **no Network permission**, your **data is safe**.

## Banking apps and how to fix it

### What happens

MergeHelper needs **Accessibility** (for taps, swipes, and screenshots) and permission to **draw over other apps** (for the floating controls). Fraudsters abuse the same combination on real banking apps (fake screens + automation). Many banks run **device-risk checks**: if accessibility automation is enabled—especially from a **sideloaded** app (not from official Store)—they may stop working or block login.

- The bank app does **not** scan this APK code of behavior. It sees that **accessibility automation is on** for a sideloaded app.
- A **factory reset is usually not required.**

### How to fix it

**Before you open your bank (or similar) app:**

1. Open **Settings → Accessibility**.
2. Turn **off** **MergeHelper gestures**.
3. Quit your bank app.
4. Open the bank app again.

**When you want to play again:**

1. Turn **MergeHelper gestures** back **on** in Accessibility.
2. Open MergeHelper and **Start overlay** as usual.

MergeHelper does not send gameplay data off your device (no network permission in the app).

## Install (Android)

1. Open the **Releases** page (link above).
2. Download the latest `.apk`.
3. On your phone, open the downloaded file and allow install from that app (Files, Chrome, etc.) when prompted.

**Updates:** Open Releases again and install the newer APK over the old one (same signing key).

## What the tool offers:

### MultiClick - set a point on the screen, tap multiple times.
<img width="320" height="418" alt="multiclick gif" src="https://github.com/user-attachments/assets/bfb2b49d-94ea-4fa4-86c9-95cbbca402c3" />


### MultiMerge - smart merge assistant. Detects duplicate items and merges them. If it detects 4 level 1 items, it will merge them to one level 3 item.
!! Important !! User must input correct row x columns.

<img width="320" height="418" alt="multimerge gif" src="https://github.com/user-attachments/assets/9269a43a-3db4-4184-b3ed-980d6e35db5d" />


### Adjust - change the MultiClick position and MultiMerge params on the fly, without leaving your merge game.
<img width="320" height="418" alt="adjust" src="https://github.com/user-attachments/assets/0b0a2746-12b7-413e-8972-8d58f69f6ce5" />


### Profiles - change MultiClick position and MultiMerge area with one button click. Up to 99 profiles supported.
<img width="320" height="418" alt="profiles" src="https://github.com/user-attachments/assets/ff1100ab-eab7-4737-9d04-3e2896acd12f" />

### Discard overlay - done with merging? Just remove the overlay.
<img width="320" height="561" alt="discard" src="https://github.com/user-attachments/assets/cb034eaf-424e-4580-aec9-05af53a550a4" />
