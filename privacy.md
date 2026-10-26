# Pause Menu — Privacy Policy

_Last updated: October 26, 2026_

Pause Menu ("the app") is a video game backlog tracker for Android. This policy explains what information the app handles and where it goes.

## Summary

- No account, no sign-up, no ads, no analytics, no tracking.
- Your library, notes, lists, ratings and playtime stay **on your device**.
- The only things that go online are your **game searches** (sent to IGDB), **cover images** (loaded from IGDB), a **contentless sign-in request** to the app's own token service (so IGDB accepts the searches), and **Pro purchases** (handled by Google Play). If you choose to send a **bug report**, it goes by email from your own email app.

## Information stored on your device

The app stores the following **only on your device**, in its private storage:

- Games you add to your library, the platform you play each copy on, and their status, rating, playtime, completion tag and abandon reason
- Your notes, saved guide links, custom lists and Digital Vault store tags
- Cached game information and cover images, so the app works offline
- Whether you own Pause Menu Pro

The developer has no access to this data. Updating the app keeps it. Uninstalling the app deletes it, unless you saved a backup file (see below).

### Backup files

Pause Menu doesn't back up to Google or any other cloud service; Android's automatic Google backup is turned off for this app. In Settings you can choose **Save backup** to save your library (including each game's platform), lists, notes and appearance settings to a `.pausemenu` file in a folder you pick on your device. The app asks for your permission before it saves or opens any file, and only uses files you pick yourself. The file is scrambled so other apps can't read it, and only Pause Menu can restore it. It never includes your Pro purchase, which Google Play restores. The file stays where you saved it, even after you uninstall the app, until you delete it. If you move or share the file yourself (for example to cloud storage), that service's privacy policy applies.

## Information sent to third parties

| Service | What is sent | Why |
|---|---|---|
| **IGDB** (owned by Twitch, an Amazon company) | The text you type into Search, the IDs of games you view, and standard network information such as your IP address | To find games and their details, cover art and time-to-beat estimates |
| **Pause Menu token service** (run by the developer on Cloudflare Workers) | An empty request with no personal content. Like any internet request it carries your IP address, which is used only to limit abuse and is not stored by the developer | To get the temporary access key IGDB requires, without putting the developer's IGDB secret inside the app |
| **Google Play** | Purchase requests and your Google Play account, handled by Google | To process and restore the one-time Pro purchase |

Pause Menu doesn't send your library, notes, lists or any other personal content to anyone.

These services handle data under their own privacy policies:

- Twitch / IGDB: https://www.twitch.tv/p/legal/privacy-notice/
- Cloudflare (hosts the token service): https://www.cloudflare.com/privacypolicy/
- Google Play: https://policies.google.com/privacy

## Bug reports

The Report a bug form (on the About screen) doesn't send anything by itself. When you tap Send, it opens your own email app with a message addressed to the developer, and nothing is sent until you send that email. The message contains what you typed in the form plus your phone's manufacturer and model, Android version, screen size, language, the app's version and whether you use the light or dark theme. You can read and edit all of it before sending. The developer uses bug report emails only to fix problems and replies from the same address.

## Links to other apps and websites

The Walkthrough, Boss fights, Wiki and saved guide links open YouTube, Google Search or other websites in their own apps. The "View on IGDB.com" and "Visit IGDB.com" buttons open the IGDB website in your browser. What happens there is governed by those services' privacy policies.

## Payments

Pause Menu Pro is a one-time in-app purchase processed entirely by Google Play. The app never sees your payment details. Refunds follow Google Play's refund policy.

## Children

Pause Menu is not directed at children under 13 and does not knowingly collect personal information from them.

## Changes

If this policy changes, the updated version will be posted at this address with a new "Last updated" date.

## Contact

Somni Solus — somnisolus@proton.me
