# GarpuGulung BeatMaker

**Everyone can make music.** A friendly drum machine that runs in a phone browser. No install, no uploads: every sound is synthesized in the app.

## How to use

1. Press **▶ PLAY** to hear a beat.
2. Tap a **pad** to hear a sound and pick it.
3. Tap the **squares** to add or remove hits. Tap twice for a louder (accent) hit. Each row is one beat of the bar, so you can count along: 1, 2, 3, 4.

## Features

- **16 pads (4×4)** with three ready layouts: MPC standard, Finger drumming, Drum kit. You can also rearrange them with **MENU → Move pads around** (tap two pads to swap them).
- **Two kits, all synthesized:**
  - Band kit: kick, 808, snare, rim, clap, hi-hat, open hat, 3 toms, crash, ride, shaker, tambourine, cowbell, conga.
  - Kendang kit: dut, tak, tung, dhang, ketipung, tek, kentong, plus kick, snare, hats, clap, tambourine and crash.
- **Four patterns (A, B, C, D) plus FILL.** Pattern switches wait for the end of the bar. FILL plays one bar, then returns.
- **CHAIN**: up to 8 slots that play in order and repeat (for example A A B A C C D FILL).
- **Time signatures**: 4/4, 3/4, 2/4, 6/8, 12/8, 5/4, 7/8. BPM always follows the beat you count (in 6/8 and 12/8 that's the dotted quarter).
- **17 genre starters**: Pop, Rock, Funk, Disco, Hip-hop, Trap, House, Reggae, Bossa Nova, Dangdut, Koplo, Blues shuffle (12/8), Waltz (3/4), Ballad (6/8), Jazz (5/4), Odd groove (7/8), Empty. Patterns B, C, D and FILL are generated from A as a starting point.
- **Library**: save your beats by name and open them later. Export/Import a beat as a text code for backup or to move it to another phone.
- **PADS / PATTERN tabs**: on phones, PADS fills the screen with big pads for live playing, PATTERN shows every sound's steps at once (tap M to mute a sound). On wide screens, pads stay beside the steps.
- **Move pads around**: drag a pad onto another to swap them (or tap two pads).
- **Other**: swing, tap tempo, per-sound mute, Undo for loads and clears.

## Put it online with GitHub Pages

1. Create a new GitHub repo, e.g. `beatmaker`.
2. Upload all files in this folder (**Add file → Upload files**).
3. Open **Settings → Pages**, set *Source* to **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
4. Wait 1–2 minutes. The app will be at `https://<username>.github.io/beatmaker/`.

On your phone: open that address and choose **Add to Home Screen**.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole app |
| `manifest.webmanifest` | Data for "Add to Home Screen" |
| `icon-192.png`, `icon-512.png` | App icons |
| `.nojekyll` | Makes GitHub Pages serve the files as they are |
