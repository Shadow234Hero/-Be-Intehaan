# For My Priji — Girlfriend's Day Website

## How to open it
Just double-click `index.html` (or open it in any browser). Tap the envelope
to unlock the site — that's also what starts the background music, since
browsers block music from autoplaying without a click.

## What's inside
1. **Envelope intro** — tap to open, unlocks the site + music
2. **Hero** — "Happy Girlfriend's Day" title
3. **Intro note**
4. **Video** — plays `assets/video/gir-edit.mp4` (your `gir.mp4`) in a phone frame
5. **Gallery** — 11 polaroid-style photos of her
6. **Reasons** — 6 flip cards ("reasons you're my favorite person") — placeholder text, easy to personalize
7. **Letter** — click the small envelope to reveal a full letter — placeholder text, personalize this!
8. **Voice note** — a player that's ready and waiting for your recording
9. **Floating music button** (bottom-right) — mutes/unmutes "Be Intehaan" anytime

## Things you'll want to personalize

### 1. Add your voice note
Record your voice note, name the file **exactly** `voice-note.mp3`, and drop
it into:
```
assets/audio/voice-note.mp3
```
The player will automatically light up — no code changes needed. (If your
recording is in a different format like `.m4a` or `.wav`, just convert it to
mp3 first, or tell me and I'll wire it up for you.)

### 2. Edit the letter
Open `index.html`, search for `letter-paper`, and replace the paragraph text
with your real words. The placeholder is written to be easy to swap out.

### 3. Edit the 6 "reasons" cards
Same file, search for `reason-card`. Each card has a front line and a back
line — swap in your own inside jokes / reasons.

### 4. Swap photos or captions
Photos live in `assets/img/photo1.jpg` through `photo11.jpg`. To replace one,
just overwrite the file with the same name, or edit the `src` in
`index.html` under the `#gallery` section. Captions are the text right next
to each photo tag.

## Hosting it (optional, if you want a shareable link)
This is a static site — three free options:
- **Netlify Drop**: go to app.netlify.com/drop and drag this whole folder in
- **GitHub Pages**: push the folder to a repo and enable Pages
- **Vercel**: `vercel` CLI or drag-and-drop via their dashboard

Or just send her the zipped folder to open locally — it works perfectly
offline too.
