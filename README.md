# ZWEISPUR

A two-track audio recorder for iPhone, iPad, and desktop. Built as a single `index.html` file — no install, no dependencies.

---

## Getting Started

Open `index.html` in Safari (iOS) or any modern browser. Grant microphone permission when prompted.

To use as a home screen app on iPhone/iPad: tap **Share → Add to Home Screen**.

---

## Recording

1. **Arm a track** — tap **ARM** on Track A or Track B (only one at a time)
2. **Press RECORD** — recording starts immediately, or after a count-in if enabled
3. **Press STOP** — recording ends and the track is ready for playback
4. **Press PLAY** to hear it back

Track A captures with echo cancellation disabled for the cleanest possible audio. Track B keeps echo cancellation on so Track A plays back through the speaker during overdubs.

---

## Overdubbing

Record Track A first. Then arm Track B and press RECORD — Track A plays through the speaker while you record Track B over the top.

---

## Mixer

Tap **MIX** in the top bar to open the mixer.

- **Fader** — volume. 75% position = 0 dB. Above 75% adds up to +6 dB of headroom.
- **Gain dial** — trim gain ±12 dB. Drag up/right to boost, down/left to cut. Double-tap to reset.
- **Pan dial** — stereo position. Drag up/right for right, down/left for left. Double-tap to centre.

---

## Track Controls

| Button | Action |
|--------|--------|
| ARM | Arm track for recording |
| SOLO | Play/stop this track independently |
| MUTE | Silence track during playback |
| CLR | Delete track audio |
| NORM | Normalize track to 85% peak |

---

## Metronome & Timing

Tap **METRO** or **COUNT-IN** to reveal BPM controls.

- **METRO** — audible click track during recording and playback
- **COUNT-IN** — 4-beat count before recording starts
- **TAP** — tap repeatedly to set BPM by feel
- **LOOP LENGTH** — set how long a loop cycle is (or use Track A's length)

---

## Speed

- **½ SPEED** — time-stretch both tracks to half speed (phase vocoder, minimal artefacts)
- **¾ SPEED** — three-quarter speed
- Tap the active button again to return to normal speed

---

## Export

Press **↑ SHARE** in the transport bar to export a stereo mix as a 320 kbps MP3. On iOS this opens the share sheet; on desktop it downloads the file.

---

## Latency Compensation

For overdub recordings, the app trims a small amount from the start of the new recording to compensate for device latency. The default offset is **77 ms**.

- **AUTO** — plays a click through the speaker and measures the round-trip delay automatically
- **−5ms / +5ms** — manual adjustment

---

## Tips

- For best Track A quality, record in a quiet environment
- The louder your instrument relative to room noise, the better the result
- Normalize a quiet take with the **NORM** button before overdubbing
