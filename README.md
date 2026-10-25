# Wordsprout 🌱

A picture talker for a child who knows her words but finds them hard to say.
It runs in Safari on an iPad, speaks out loud, works offline, and keeps everything on the device.

## Two sides

**💬 Talk**: build a sentence in three steps, using the colours of the Fitzgerald Key used in AAC.

| Step  | Colour | Examples |
|-------|--------|----------|
| Who   | yellow | I, Mum, Dad, Brother, Grandma |
| Doing | green  | want, need, feel, go, eat, play |
| What  | orange / blue | toilet, apple, park, happy, tired |

Picking a "Doing" word opens the matching group. For example, *feel* opens Feelings and *go* opens Places.
The whole sentence is spoken at the end, with grammar fixed ("Mum wants juice").

**🙋‍♀️ Answer**: one-tap replies when someone asks her a question.
Yes / No / Maybe / I don't know / Say it again are always on top. Below them are question pages: How do you feel? · What do you want? · Who? · Where? · When? · How was it? · Which one? · How much?

## Grown-up settings

**Press and hold ⚙︎ for about 1.5 seconds.** A quick tap does nothing, so she can't change things by accident.

- **Edit words and pictures**: tap any tile to change its word, the words spoken, or its picture. You can take a photo with the iPad camera. Use real photos for family; that matters most.
- **Sentence mode**:
  - *full sentence* (every step required)
  - *can skip* (lets "toilet" stand alone)
  - *all columns at once*
- Voice, speed, pitch, picture size, quick-words bar.
- **Save backup file / Load backup file**: do this after adding photos.

## Put it online with GitHub Pages (about 5 minutes)

1. Create a new repository on GitHub called `wordsprout`.
2. Upload every file in this folder: `index.html`, `sw.js`, `manifest.webmanifest`, the three `.png` icons and this README.
3. In the repository, go to **Settings → Pages**. Set **Source: Deploy from a branch**, **Branch: main / (root)**, then **Save**.
4. After a minute the board is live at `https://<your-username>.github.io/wordsprout/`.

## Set it up on the iPad

1. Open the link in **Safari**.
2. Tap **Share → Add to Home Screen**.
3. Open it from the new home-screen icon. It runs full screen, works without Wi-Fi, and Safari won't clear its saved photos.
4. For a nicer voice, go to **Settings → Accessibility → Spoken Content → Voices → English** and download an enhanced voice (an Australian one, for example). Then pick it in Wordsprout's settings.
5. Consider **Guided Access** (Settings → Accessibility) to keep her inside the app.

## Privacy

There is no account, no server and no tracking. Words, photos and settings are stored only in this iPad's browser storage. Backups are a single `.json` file you control.

## Updating

Change `index.html`, upload it to the repo, and the iPad picks up the new version the next time it opens with internet.
Her saved words and photos aren't affected.
