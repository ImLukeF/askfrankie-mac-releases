# AskFrankie for Mac

AskFrankie for Mac is the Mac app for AskFrankie, an AI-powered CRM and operations platform for businesses and teams. This repository publishes the downloadable app and the Sparkle update feed (`appcast.xml`). The application source and build/test tooling are maintained separately and are not included here.

## Facts

- **Latest release:** 0.2.59 (build 83); see [`CHANGELOG.md`](CHANGELOG.md) and [`appcast.xml`](appcast.xml).
- **Requirements:** macOS 14 or later. The release ZIP is universal for Apple silicon and Intel Macs.
- **Account:** an AskFrankie account and an internet connection are required. Sign in with the [AskFrankie web app](https://app.askfrankie.com.au).
- **Cost:** the Mac download is free; AskFrankie subscription pricing is separate. See [pricing](https://askfrankie.com.au/pricing/).
- **Download:** the latest ZIP is on this repository's [Releases](https://github.com/ImLukeF/askfrankie-mac-releases/releases/latest) page.

## Install

1. Download the latest ZIP from [Releases](https://github.com/ImLukeF/askfrankie-mac-releases/releases/latest).
2. Unzip it and drag `AskFrankie.app` to Applications.
3. Open AskFrankie and sign in with your AskFrankie account.

## What the Mac app adds

The current app supports Frankie in a Mac window, a built-in Browser, approved Mac automation, Messages campaigns, one-way contact-group import, meeting notes and voice/push-to-talk. The release history also documents native notifications (0.2.32) and optional iMessage import and LinkedIn sign-in (0.2.47–0.2.49).

macOS permissions are feature-specific. The app's permission descriptions state that:

- Accessibility is used for the Option–Space push-to-talk shortcut and controls in a Mac task window you approved.
- Screen Recording is used only for an approved Mac task or while screen context is switched on; Mac audio is captured only during meeting notes you start.
- Microphone and Speech Recognition are used for voice conversations and meeting notes you start; the app states that meeting audio is not retained.
- Contacts access copies contact groups you choose into your workspace; it does not write back to your contacts.
- Apple Events access sends Messages campaigns you approved in the web app through Messages on your Mac.

Available features depend on your AskFrankie workspace, connected services and plan. Review AI-generated output before acting on it.

## Updates

The app is configured to check the Sparkle feed automatically at [`appcast.xml`](https://raw.githubusercontent.com/ImLukeF/askfrankie-mac-releases/main/appcast.xml). The feed lists each release's version, minimum macOS version and EdDSA signature for the update ZIP. Manual downloads remain available from [Releases](https://github.com/ImLukeF/askfrankie-mac-releases/releases/latest).

## Repository contents

- [`appcast.xml`](appcast.xml): the Sparkle update feed.
- [`CHANGELOG.md`](CHANGELOG.md): release history with download links.
- `release-notes-*.md`: detailed notes for selected releases.

This repository contains no application source, package manifest, build scripts, tests, deployment automation or runbooks, so it has no build, test or deployment commands.

## More information

- [AskFrankie](https://askfrankie.com.au/)
- [Pricing](https://askfrankie.com.au/pricing/)
- [Privacy Policy](https://askfrankie.com.au/privacy/)
- [Terms of Service](https://askfrankie.com.au/terms/)
- [Service status](https://askfrankie.com.au/status/)
- Support: [hello@askfrankie.com.au](mailto:hello@askfrankie.com.au)
