# Kya — Your AI Support Dog 🐾

A playful prototype for companionship, feelings check-ins, calming activities, and learning practice. The home screen uses the supplied cutout photo of the real Kya in an animated pastel room.

## Try it

Open `index.html` in a modern browser, or serve the directory with `python3 -m http.server 8000` and visit `http://localhost:8000`. Microphone recognition typically requires localhost or HTTPS, browser support, and permission. Typed chat works without a microphone. Speaking uses the device's available browser voices.

## What works now

- Choose among eight companions (Kya, two animals, and five illustrated kid characters) on the home screen or in Customize. Select a kid style such as Punk Rocker, Sporty, Dreamer, Artist, Superhero, or Cozy; change the outfit and accessory separately. The choices appear on the portrait and companion cards during this visit. Adjust name, personality, voice, speed, and page background. The My Feelings check-in is separate from style choices.
- Kya gently moves while idle, tilts and bobs while listening, and bobs faster with animated sound bars while speaking. The room has drifting clouds, twinkles, and floating hearts. Give Kya a pat for a happy hop and spoken greeting. A reduced-motion setting turns off these animations.
- Use the feeling shortcuts on Home to jump to a selected feeling check-in.
- Type or speak to a companion. Responses are **preset and keyword based**, not a conversational AI model. Stop speaking at any time.
- Record feelings and intensity for the current visit; try breathing, grounding, and quiet time, then record how it felt afterward.
- Practice six learning games and three extra activities; view strengths from successful practice.
- Write a journal entry that stays in the page until refresh. Generate and print a caregiver visit summary of check-ins and activities. Chat and journal text are excluded.

## Privacy and limits

There are no accounts or backend. The prototype keeps check-ins and practice records only in page memory; refresh clears them. The caregiver button is **not authentication**. Do not use this prototype to store sensitive child information or treat its summary as a diagnosis. Speech recognition may be implemented by the browser's own service; check its privacy behavior before use. The app does not send its own network requests.

## Next build steps

1. Add real caregiver authentication, consent, child privacy controls, and secure storage before collecting real children's data.
2. Add a server-side conversational AI endpoint, moderation and safety handling, and approved memory. Never place API secrets in this public repository.
3. Replace preset voice output with natural speech when a backend is ready.
4. For realistic blinking and lip sync, build an animation rig from Kya's actual photo with separate eyelid, muzzle, and mouth layers. The current version animates the intact photo and sound bars; it does not reshape Kya's face or sync mouth movement to speech.
5. Add a securely reviewed weekly report and explicit caregiver-controlled professional sharing.

`index.html.html` from the earlier upload was a duplicated, obsolete prototype and has been removed. GitHub Pages should serve `index.html` at the repository root.
