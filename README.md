## uraniam9

I make things that try to be quieter than the phone they run on.

**[SonoLune](https://play.google.com/store/apps/details?id=com.soundsoftlab.sonolune)** is a sleep and focus app. Warm light, slow sound, and a set of rules about
when it is allowed to interrupt you, which is most of what makes it work.

**[Lune Bridge](https://github.com/uraniam9/lune-bridge)** is the root half. Android can already tint a screen to candlelight and
dim it below what the brightness slider allows, entirely in the compositor. It
just refuses to go that far, because the limits are constants in
`framework-res`. The module moves them, and refits the colour ramp so the new
range is actually correct rather than merely permitted.

It also stops apps waking you: per-app permissions, quiet hours, and a
watcher for the "we miss you" kind of notification. No Xposed anywhere.

**[Lost Xposed](https://github.com/uraniam9/lost-xposed)** doesn't fit the theme above — it's a general LSPosed toolbox, not a
calm one. A status bar clock you actually compose, per-app display density,
notification rules that block a message before it reaches your tray. Alpha,
and every feature says on its own card whether it has actually been tested on
a phone yet.

---

The thing I keep coming back to is that a phone screen is built for daylight
and stays that way at 3am, and almost every fix for it works by laying grey
over the top. Adding darkness is not the same as emitting less light, and your
eyes can tell.

If any of it helped, [a coffee](https://buymeacoffee.com/uraniam9) is a kind way to say so. Telling me the PWM knee of
your panel is worth more, though. It cannot be measured in software, only by a
person looking at a screen, and it is the same for everyone who owns your
phone.
