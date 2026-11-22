# Habla · Speak — Spanish ⇄ English voice translator

Speak Spanish or English and see and hear the translation. It works in the browser on phones, tablets and computers, with nothing to install and no account needed.

- **Translate:** pick a direction, tap the microphone and speak. The translation appears and is read aloud.
- **Conversation:** two people take turns. Orange is for the Spanish speaker, blue for the English speaker. Each turn is translated and read aloud for the other person. The transcript can be copied.
- **Settings:** read aloud on/off, Latin American or Spain Spanish, voice speed, and an optional email for a higher daily translation limit.

## Publish it on GitHub Pages (about 5 minutes)

1. Sign in at [github.com](https://github.com) (or create a free account).
2. Click **+** (top right) → **New repository**. Name it, for example `habla`. Set it to **Public**, then click **Create repository**.
3. On the new repository's page, click **uploading an existing file**. Drag in **all** the files from this folder: `index.html`, `manifest.webmanifest`, `icon.svg`, `icon-180.png`, `icon-192.png`, `icon-512.png` and `README.md`. Then click **Commit changes**.
4. Go to **Settings** → **Pages**. Under **Build and deployment**, set **Source** to *Deploy from a branch*, choose the branch **main** and the folder **/ (root)**, then click **Save**.
5. Wait a minute or two and refresh the page. GitHub shows the address of your site, for example `https://YOUR-USERNAME.github.io/habla/`.

GitHub Pages serves the site over **https**, which the microphone requires.

**To update the site later,** upload the changed file again in the same way. It goes live about a minute later.

## Using it on a phone or tablet

- Open the address in **Safari** (iPhone/iPad) or **Chrome** (Android).
- To get an app icon: in Safari, tap **Share → Add to Home Screen**; in Chrome, tap **⋮ → Add to Home screen** (or *Install app*).
- The first time someone taps the microphone, the phone asks for permission. Tap **Allow**.
- **iPhone/iPad:** voice input uses Apple's speech recognition. If the mic doesn't work, check **Settings → General → Keyboard → Enable Dictation** (and Siri & Dictation privacy settings).
- On phones, the mic listens for one phrase at a time and finishes on its own when you stop talking.

**Keyboard mode:** if a browser has no speech recognition (Firefox, for example) or the microphone is blocked, the page switches to keyboard mode automatically. Tap the text box, tap 🎤 on the phone's keyboard and speak. The page translates when you pause, and in Conversation mode it sends the message and switches speakers. Set the keyboard language with 🌐 so it understands the language being spoken.

## Translation service and limits

Translations come from **[MyMemory](https://mymemory.translated.net)**, a free service that needs no key.

- About **5,000 characters per day** for each visitor's internet connection. That's roughly 15–20 minutes of conversation.
- Entering an email in the settings raises this to **50,000 characters per day**. The email is only sent to MyMemory and is stored in that browser.
- The page shows how much of today's limit the device has used.
- MyMemory translates more literally than an AI translator, and slang or very informal speech may come out stiff.

Speech recognition and voices are provided by the visitor's own browser and device. In Chrome, speech recognition is processed by Google's servers, so it needs an internet connection.

## Files

| File | What it is |
|---|---|
| `index.html` | The whole app (layout, styles and code) |
| `manifest.webmanifest` | Name and icon for "Add to Home Screen" |
| `icon.svg`, `icon-*.png` | App icons |
