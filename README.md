# The Dot Product

A collection of small, single-purpose Android apps that I vibe-code with Claude to fix everyday annoyances. Each app does one job, is open source, and can be downloaded as a free APK.

This repository holds the website for the collection: a single static page with no framework and no build step.

## The apps

| App | What it does | Download | Source |
| --- | --- | --- | --- |
| **Verba** | Notes you can just say. Type or talk; it keeps both the original recording and a speech-to-text transcript. | [Latest APK](https://github.com/Satyajeet-code/verba/releases/latest) | [verba](https://github.com/Satyajeet-code/verba) |
| **ReadAloud** | Paste some text, tap play, and it reads it out loud. | [Latest APK](https://github.com/Satyajeet-code/readaloud/releases/latest) | [readaloud](https://github.com/Satyajeet-code/readaloud) |

More apps will be added as I build them.

## Installing an app

The apps aren't on the Play Store yet. To install one on an Android phone:

1. Open the app's **Latest APK** link above.
2. Under **Assets**, tap the `.apk` file to download it.
3. Open the downloaded file. If Android asks, allow **Install unknown apps** for your browser.
4. Tap **Install**.

## Running the site locally

Everything is in `index.html`: the styles, the script and the icons. Open it in a browser to view it. Fonts load from Google Fonts, so you need an internet connection for them to display correctly.

## Adding a new app to the site

In `index.html`, find the `<!-- READALOUD -->` card in the tools section. Copy the whole `<article class="card reveal" data-spot>` block, paste it below, and update:

- the icon `<svg>` inside `.app-icon`
- the name and tagline in `<h3>`
- the description, the `.flow` line and the feature chips
- the **Download APK** link (`https://github.com/Satyajeet-code/<repo>/releases/latest`) and the **View source** link

## Get in touch

Have a small, annoying problem your phone should just handle? Open an issue, or email [satyajeetnarayan9@gmail.com](mailto:satyajeetnarayan9@gmail.com) and we can build it together.

---

Built with Claude by [Satyajeet Narayan](https://satyajeet-narayan.vercel.app/).
