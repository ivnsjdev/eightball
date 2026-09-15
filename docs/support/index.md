# 8 Ball Support

**Last updated:** 15 September 2026

8 Ball is a fortune-telling ball for Apple Watch: ask a yes-or-no question, shake
your wrist, and read one of the twenty classic replies. It runs on the watch alone,
with no iPhone app needed. It is a one-time purchase with nothing else to buy, and
there is no account, no server, no advertising, no analytics, and no tracking — the
app contains no networking code at all, so it works exactly the same with the watch
offline.

## Contact

The fastest way to reach us is email:

**ivnsjdev@gmail.com**

We aim to reply within 2–3 business days. To help us help you faster, please
include:

- your Apple Watch model and watchOS version (**Watch app on iPhone → General →
  About**, or **Settings → General → About** on the watch)
- the 8 Ball version, shown on the App Store listing
- what you were doing — shaking, turning the Digital Crown, tapping, or in Settings
- what you expected to happen, and what happened instead

## Frequently asked questions

### How do I ask the ball?

Three ways, whichever suits the moment:

- **Shake your wrist** — a deliberate flick.
- **Turn the Digital Crown** — about a third of a revolution, either direction.
- **Tap the ball.**

The ball winds up, tumbles, and the answer window swings round into view. You will
feel three taps while it thinks and one when it answers, so it works without looking.

### Which devices does it need?

Apple Watch running **watchOS 11 or later**. 8 Ball is a standalone watch app: there
is no iPhone app to install, and it does not need your phone nearby or an internet
connection.

### How do I get to Settings?

**Press and hold the ball** for about half a second. Settings has three rows —
**Skin**, **Emblem**, and **Language** — and each shows what is currently chosen.

The long press is used rather than the Digital Crown because the crown is one of the
ways to ask the ball, and a list on the main screen would take it away from that.

### What does 8 Ball cost?

One payment on the App Store, at the price shown on its listing for your country.
After that there is nothing else to buy: no in-app purchases, no subscription, no
paid tier, and no advertising. Every skin, every emblem and all 32 languages are
included from the start — nothing is held back or unlocked later. The app contains no
purchase code at all, so nothing inside it can charge you again.

Apple handles all App Store billing, so we never see your payment details. To query
the charge or request a refund, use
[reportaproblem.apple.com](https://reportaproblem.apple.com).

### Is 8 Ball private?

Yes. It has no server, no analytics, no ads, and no third-party SDKs, and it contains
no networking code of any kind. It never receives your question, because there is
nowhere to type one. The only things saved are the skin, emblem, and language you
picked, and they stay on your watch. See the [Privacy Policy](../privacy/) for full
detail.

### Is it suitable for children?

Yes. 8 Ball is rated 4+ and family-friendly: no chat, no sharing, no social features,
no advertising, and nothing to buy. The twenty replies are the classic toy's replies.
It is a toy for settling what to have for lunch, not a source of advice.

## The ball and its answers

### Are the answers really random?

Yes. Each reply is drawn uniformly from the twenty using the system random number
generator, and the draw happens **before** the ball starts moving. The tumble then
displays a result that has already been decided — it does not steer toward one.

### Why did I get the same answer twice in a row?

Because that is what a fair draw does. Every ask is an independent 1-in-20, and the
previous answer is deliberately **not** filtered out of the next one. A real 8 ball
repeats, and removing the last reply from the pool would make the draw measurably
non-uniform. Over twenty asks, a repeat somewhere is the likely outcome, not a bug.

### Does the app know what I asked?

No, and it cannot. There is no text field, no dictation, and no microphone use. You
ask out loud or in your head; the app only sees a shake, a crown turn, or a tap.

### Do the coloured replies have different odds?

No. The three tones — **Affirmative**, **Non-committal**, and **Negative** — only tint
the answer window so you can read the verdict before you read the words. There are ten
affirmative, five non-committal, and five negative replies, and each of the twenty is
equally likely, so the tones are not equally likely to each other.

### Where is my answer history?

There isn't one, by design. The reply is held in memory while it is on screen and is
never written to storage, so it is gone when the app closes. Nothing accumulates.

## Shaking

### Shaking does not do anything

The shake detector is tuned to a **deliberate wrist flick** — it wants a peak of
roughly 2 g sustained across about half a second, which raising your arm, walking, a
clap, or a knock against a table will not produce. Flick your wrist as if shaking down
a thermometer.

If it still does nothing:

- Check whether the ball is already rolling. Shakes are ignored for about a second
  after a roll starts, so the shake that began the roll cannot start a second one.
- Lower your wrist and raise it again. With the wrist down the watch is dimmed and the
  ball deliberately will not roll.
- Use the Digital Crown or a tap instead. Both work everywhere, including on a charging
  stand, where shaking is not possible.

### It rolls when I did not mean it to

The trigger needs a sustained shake rather than a single spike, so accidental rolls
are rare. If your daily movement is setting it off, use the crown or a tap and tell us
what you were doing — the thresholds are tunable and real reports are how they get
tuned.

### VoiceOver is on and shaking does nothing

VoiceOver takes the shake gesture for its own navigation. Tapping the ball still asks,
and so does the crown; the ball is also exposed as a button, so a VoiceOver double-tap
works. The answer is announced as it arrives, with its tone.

## Skins and emblems

### How do I change the look of the ball?

Press and hold the ball to open Settings, then **Skin** for the ball itself or
**Emblem** for the mark on its shoulder. Each picker shows the choice on a real ball
before you commit.

There are twelve skins — **Classic, Ivory, Slate, Ruby, Emerald, Sapphire, Amethyst,
Rose, Gold, Ember, Aurora, Neon** — and twelve emblems — **Eight, Question, Star, Moon,
Sparkles, Bolt, Flame, Heart, Spade, Pool Ball, Crystal Ball, Dice**. That is 144
combinations, and all of them are unlocked from the start.

### Are any skins or emblems locked, or paid?

No. Every one is available immediately. There is nothing to unlock, earn, or buy.

### I reinstalled and my skin is back to Classic

Your choices live in the app's local data on the watch, with no account or iCloud
sync behind them, so deleting the app clears them. Pick them again in Settings — it
costs nothing and everything is still unlocked.

## Settings and accessibility

### How do I change the language?

Press and hold the ball → **Settings** → **Language**. 8 Ball carries **32 languages**
and its picker is independent of your watch's language, so you can read the ball in one
language on a watch set to another. Right-to-left languages lay the app out
right-to-left.

### The animation is too much

Turn on **Reduce Motion** (Watch app on iPhone → Accessibility, or Settings →
Accessibility on the watch). 8 Ball honours it with a much shorter, calmer roll rather
than the full tumble. The answer is unchanged — it was drawn before the animation
started either way.

### Does 8 Ball work with VoiceOver?

Yes. The ball is a labelled button, and each answer is announced along with its tone as
it arrives, so a question can be asked and answered without seeing the screen. Swiping
back to the ball repeats the current answer.

### Does it support Always-On, and what about battery?

Yes. When your wrist drops, the animation stops immediately rather than running unseen,
and the accelerometer is switched off whenever the app is not in the foreground — a live
motion sensor is the real battery cost on a watch, not the drawing.

The answer window is also marked privacy sensitive, so watchOS redacts it in the dim
state. Someone glancing at your lowered wrist does not read your answer.

### Is there a complication or a watch face widget?

Not in this version. 8 Ball is the app alone.

### Is there an iPhone version?

8 Ball is watch-only. The same 8-ball, with the rest of a randomizer around it, is part
of **Pickify** on iPhone and iPad.

## Bugs and feature requests

Please email **ivnsjdev@gmail.com**. Bug reports with the details listed under
[Contact](#contact) above are the most useful, and feature requests are genuinely read.

## Terms of Use

8 Ball is licensed under Apple's standard licence agreement for apps, the
[Apple Standard End User License Agreement](https://www.apple.com/legal/internet-services/itunes/dev/stdeula/).
App Store downloads are additionally governed by the
[Apple Media Services Terms and Conditions](https://www.apple.com/legal/internet-services/itunes/).

## Privacy Policy

[Read the Privacy Policy](../privacy/)
