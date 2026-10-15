# Privacy policy

*Last updated: 16 October 2026*

ID3ntify is a free, open-source desktop app that runs on your own computer. It has **no accounts, no ads, no analytics and no tracking**. Its author, Elias Hajjar, does not receive any of your data. The source code is public, so anyone can check this.

## What stays on your computer
- Your music files. They're read and changed only when you ask (for example, **Write tags**).
- Settings, history and optional backups. They're stored in your user profile (`%APPDATA%\ID3ntify`).
- Microphone or desktop-audio recordings. These are short temporary clips, deleted when the app closes (or, if it didn't close normally, the next time it starts).
- In folders you load in **Bulk identification**, two small files (`id3ntify_session.json` and `id3ntify_cache.json`) remember your progress and answers. **Save checklist** adds `results.csv` and `checklist.csv`. You can delete them at any time.

## What is sent, and to whom
To identify a song, ID3ntify has to ask online services. It only does this when you start an identification.

| Sent to | What | Why |
|---|---|---|
| **AcoustID** (acoustid.org) | An audio fingerprint made on your computer (a numeric summary, not the audio), the song length and the app's key | To look up the recording on MusicBrainz |
| **Instant ID** (Shazam's recognition service, through the unofficial community client "shazamio") | A fingerprint made on your computer from about 12 seconds of audio, plus the time of the request and two random request IDs. Not the audio itself, the filename or your location | To recognise the song |
| **Deezer** and **Apple iTunes** search (Preview check, only when the other services aren't sure) | The artist and title being checked (from the services, your tags or the filename), then a download of the store's public 30-second preview | To compare the preview's sound with your file. Your own audio is never uploaded for this |
| ACRCloud / AudD (only if you turn them on) | A short audio clip (about 15 seconds) and your own key | Optional extra opinions |
| Cover art hosts (e.g. Cover Art Archive, Apple's image servers) | A normal image request | To show and embed album covers |
| GitHub (only if update checks are on) | The app's version, as a normal web request | To tell you about new versions |
| Your Plex server (only if you set it up) | A "refresh library" request with your Plex token | To rescan your library after tagging |

These services see your IP address like any website would, and their own privacy policies apply. ID3ntify isn't affiliated with any of them. Instant ID in particular isn't an official or authorised Shazam product. Streaming-service buttons (YouTube, Spotify, and so on) simply open a search in your web browser.

## Feedback and diagnostics
Nothing is sent automatically. If you choose to email feedback or open a GitHub issue, you decide what to include. **Copy diagnostics** puts a text summary (versions, settings with keys hidden, recent log lines with your Windows user name removed) on your clipboard so you can read it before sharing.

## Deleting your data
- Clear history in **Settings → History** or on the **History** page.
- Uninstalling removes the app and asks whether to delete `%APPDATA%\ID3ntify` (settings, history and backups) too.

## Children
ID3ntify doesn't knowingly collect any personal information from anyone, including children.

## Changes
Changes to this policy will be listed in the app's **What's new** page.


## Contact
Questions about privacy: hello@id3ntify.app
