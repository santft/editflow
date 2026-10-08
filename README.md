# EDITFLOW

**Recreate any TikTok edit with the person you choose.**

Paste a TikTok link. EDITFLOW finds its cuts, sound, effects and on-screen text to the exact
frame, then rebuilds the edit with clips of the person you pick, from YouTube or your own files.
Everything runs on your Windows PC.

![The EDITFLOW window: the reference viewer in the middle, the timeline below it, and the project panel on the right](docs/editflow.png)

## Download

**[⬇ Download the latest version](https://github.com/santft/editflow/releases/latest)**: on that
page, under **Assets**, click `EDITFLOW-…-windows.zip` (about 540 MB).

1. **Unzip it** anywhere you like, for example in Documents: right-click the zip → *Extract All*.
2. **Double-click `EDITFLOW.exe`** in the unzipped folder. Nothing else to install.
3. **The first start** downloads the free tools EDITFLOW uses (FFmpeg, Deno, Chromium and a face
   model, about 660 MB) from their makers, with a progress window. After that it opens right away,
   and a short tour shows you around.

> **"Windows protected your PC"?** Windows shows this for new apps it hasn't seen often. Click
> **More info → Run anyway**. EDITFLOW doesn't need administrator rights.

## How it works

1. **Load a TikTok**: paste its link and press **Load** (or drop the video file on the viewer).
   It plays at once; the cuts, effects and texts appear a few seconds later.
2. **Add the person**: type who you want to edit in **Who to edit** (e.g. `Megan Fox clips`) and
   press **Search**, or add YouTube links, your own video files or a saved topic. Pick the person
   once per video; EDITFLOW remembers them.
3. **Adjust, if you want**: every slot of the TikTok sits on a timeline. Choose a clip, a still or
   keep the TikTok's own clip; split, trim, swap; switch effects on or off.
4. **Generate**: a video with the same cuts at the same moments, the effects and text on top and
   the original sound, saved in the **Output** folder.

## What it copies

- **Cuts on the exact frame**: hard cuts, jump cuts and dissolves. Fast motion and camera flashes
  don't count as cuts.
- **Effects, measured in the TikTok**: flashes, dips to black or white, strobes, dissolves,
  black & white, **zooms in and out** (the same amount, speed and aim), windows and pictures
  popping in, rewinds and loops. Other effects are listed by name: switch them on to copy them.
- **Text where it was**: on-screen text is read and drawn again at the same place and time, in a
  matching font. You can change what it says.
- **Stills**: photos in the TikTok, even ones the editor zooms into, become photos of your person
  (yours, or found on the web and checked by face).
- **Colour looks and the frame**: preview the library's colour looks on the TikTok before you
  add one; keep 9:16 or choose the TikTok's own frame, 1:1 or 4:5.

## Plans

| | Free | Pro |
|---|---|---|
| New videos | 1 a day | Unlimited |
| Features and effects | All | All |
| Price | $0, no account | $5 a month, cancel any time |

Pro comes as a license key by email: click the plan badge at the top right of EDITFLOW, paste the
key and click **Activate**.

## System requirements

- Windows 10 or 11, 64-bit
- 8 GB RAM (16 GB recommended)
- About 5 GB free disk space for the app, its tools and downloaded videos
- Any graphics card: everything runs on the processor
- Internet for the first start and for downloading links

## Privacy

Your videos, links and projects stay on your PC: nothing is uploaded, there's no account and no
tracking. The app connects to the internet only to download the links you give it, to get its free
tools on the first start, to check a Pro key, and for the two searches you start yourself: **Who to
edit** (YouTube search) and the photo search for still pictures (Bing image search, with the
person's name).

## Updating and uninstalling

- **Update**: download the new zip and unzip it over your EDITFLOW folder. Your videos and settings
  stay.
- **Uninstall**: delete the EDITFLOW folder (and `%APPDATA%\EDITFLOW`, which keeps your plan, if you
  want everything gone).

## Good to know

- Use only footage you own or have permission to use, and respect the people in it: don't use
  EDITFLOW to deceive, impersonate, harass or make sexual content of anyone.
- EDITFLOW is proprietary software. It ships with, or downloads on its first start, free software
  under their own licences; the list is in `app\licenses\THIRD_PARTY_NOTICES.txt` inside the
  download.
- Questions or a problem? Open an issue here (the **Issues** tab): say what you did and what
  happened, and paste the last lines of `app\editflow_log.txt` from your EDITFLOW folder. Check
  them first for anything you'd rather not post publicly.
