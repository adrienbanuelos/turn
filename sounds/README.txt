HI-LO sound files
=================

Drop audio files into this folder using these exact names.
Any file you haven't added yet is simply silent - the game never errors.

button.mp3    generic click: chip buttons (1/2, 2x, MAX), the bet-mode tabs
              (Higher/Lower, Suit, Color), and closing the cash-out popup
play.mp3      the Play button - a new round starts
choice.mp3    the player clicks a choice: Higher / Lower / a suit / a color
flip.mp3      the next card's flip animation - plays exactly as the card starts
              turning, after the short "processing" delay that follows a choice
skip.mp3      the Skip Card button
win.mp3       a correct guess - the multiplier climbs
cashout.mp3   Cash Out
lose.mp3      a wrong guess - the streak is lost

Notes
-----
- Prefer short .mp3 clips. If you use .wav or .ogg instead, open
  "hilo (2).html" and change the file names in the SOUNDS list at the
  top of the <script> section to match.
- Master volume is the SOUND_VOLUME value in the same place (0.0 - 1.0).
- Rapid presses overlap cleanly; each play starts a fresh copy of the clip.
