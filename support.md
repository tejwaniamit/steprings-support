# StepRings Support

**Questions, problems or ideas?** Email [step.rings.dev@gmail.com](mailto:step.rings.dev@gmail.com).

If something isn't working, please include:
- your iPhone and Apple Watch models
- your iOS and watchOS versions
- what you expected to see, and what you saw

## Contents

1. [Requirements](#requirements)
2. [Getting started](#getting-started)
3. [Goal and display](#goal-and-display)
4. [History](#history)
5. [Widgets and complications](#widgets-and-complications)
6. [The Step Counter on Apple Watch](#the-step-counter-on-apple-watch)
7. [Siri](#siri)
8. [Privacy](#privacy)

## Requirements

- **iPhone:** iOS 18 or later (iPhone XS, XR, SE 2nd generation or newer).
- **Apple Watch (optional):** watchOS 11 or later (Series 6, SE 2nd generation, Ultra or newer), paired with that iPhone.
- **Apple Health:** access to Steps and Activity.

## Getting started

### What does StepRings show?
- Today's steps against your daily goal.
- Your Move, Exercise and Stand progress from Apple Health.
- It appears in four places:
  - the iPhone app
  - the iPhone widgets
  - the Apple Watch app
  - the Watch complications

### How do I connect Apple Health?
1. Open StepRings on your iPhone.
2. Tap **Connect Apple Health**.
3. Allow StepRings to read **Steps** and **Activity**.
4. Open StepRings on your Apple Watch once and allow access there too.

### StepRings shows zero steps
StepRings reads your steps from Apple Health. Check that it may read Steps and Activity:
- **On iPhone:** Settings → Health → Data Access & Devices → StepRings.
- **On Apple Watch:** Settings → Health.

Apple Health doesn't tell apps whether access was denied, so zero can mean either:
- no steps have been recorded yet, or
- StepRings has no access.

### What does the Connection row in Settings mean?
Open **Settings → Apple Health** on your iPhone:
- **Connected:** StepRings has read your steps from Apple Health, so access works.
- **Waiting for data:** StepRings asked for access but hasn't read any steps yet. Walk a little, or check access (see above).
- **Not connected:** StepRings hasn't asked yet. Tap **Connect Apple Health**.

### The Move, Exercise or Stand ring is missing or empty
- These rings come from your Apple Watch's Activity data in Apple Health.
- Check that StepRings may read **Activity** (see above).
- The Move, Exercise and Stand goals are set in Apple's **Fitness** app, not in StepRings.

### Does StepRings need an Apple Watch?
- **No.** The iPhone app and widgets work on their own.
- They show steps from your iPhone and from any other device that saves steps to Apple Health.
- The Move, Exercise and Stand rings need an Apple Watch.

## Goal and display

### How do I change my goal?
1. Open StepRings on your iPhone and tap **Settings**.
2. Under **Daily goal**, adjust the goal (1,000 to 50,000 steps).
   - Or tap **Type a goal…** to enter an exact number.
3. Your Apple Watch updates on its own.

### Can I change the look?
Yes. In **Settings** on your iPhone:
- **Progress design:** Rings, Tracks, Columns, Milestones or Tiles. It's the first row of the section below **Daily goal**.
- **Appearance** (under **Display**): System, Light or Dark.
  - Applies to the iPhone app and widgets.
  - Apple Watch always uses a dark display.

The **Preview** at the top of Settings shows each change as you make it.

### Can I reorder, hide or recolor the rings?
Yes. In **Settings**, the section under **Progress design** is named after your design and the order it uses, for example **Rings · outer to inner** or **Columns · left to right**:
- **Reorder:** tap **Edit**, then drag the rows.
- **Hide:** turn a row's switch off.
  - At least one always stays on.
  - Hidden rings are also hidden in the widgets.
- **Recolor:** use the color menu beside each row.
  - Pick a color, **Rainbow** or **Custom Color…**.

### How does Rainbow work?
- The Steps ring is rainbow by default; Move, Exercise and Stand start in orange, blue and purple, and any of them can be set to Rainbow.
- A rainbow ring is one color that changes as you make progress: red at the start, then orange, yellow, green and blue, and violet at your goal.
- A ring with no progress yet is grey, so an empty morning doesn't look like a warning.

### Do my settings reach my Apple Watch?
- **Yes**, automatically. This includes:
  - the goal
  - the progress design
  - ring order, visibility and colors
- If the Watch hasn't updated:
  1. Keep it near your iPhone.
  2. Open StepRings on the Watch.

### How do I start over?
1. Open **Settings**.
2. Tap **Reset StepRings Settings**.
3. Confirm.

This restores the 10,000-step goal, the Rings design, ring order, visibility, the default colors and display options. Your Health data is not affected.

## History

### Where is my step history?
- **On iPhone:** tap **History** on the home screen.
- **On Apple Watch:** tap the chart button at the top of the Today screen.

Choose a range:
- **Day:** steps by hour
- **Week** and **Month:** steps by day
- **Year:** steps by month

### What does the history show?
- **On iPhone:**
  - Touch a bar to see its steps.
  - The goal line shows where your goal sits.
  - The summary shows your current streak and your best day.
  - **Goal reached** compares each day with your *current* goal, and today counts the steps so far.
  - In **Day**, an active hour is one with at least 250 steps.
- **On Apple Watch:** every value is printed beside its bar, newest first.

### The Watch history is shorter than the iPhone's
- Your Watch keeps only part of your Health history.
- StepRings on your iPhone sends your Watch a year of daily totals.
- To load it, open StepRings on your iPhone once.
- Until it arrives, the Watch shows a note.

## Widgets and complications

### What widgets are there?
**On iPhone:**
- **StepRings:** your rings with today's values.
  - Home Screen: small, medium and large
  - Lock Screen: circular, rectangular and inline
- **Step Counter:** counts down the steps left to your goal (then how far ahead you are), or counts up the steps you've taken.
  - Home Screen: small and medium
  - Lock Screen: circular, rectangular and inline

**On Apple Watch** (watch face and Smart Stack):
- **StepRings:** your rings (rectangular).
- **Step Counter:** counts down or up (circular, rectangular and inline).

### How do I make the Step Counter count up?
It counts down by default. To change it:
- **On iPhone:** touch and hold the widget, tap **Edit Widget**, then set **Count** to **Count up**.
- **On Apple Watch:** when you add the complication, choose **Step Counter: Count up**. To change one already on a face, touch and hold the face, tap **Edit**, and pick it again.

### How do I add a widget or complication?
**On iPhone:**
1. Touch and hold the Home Screen or Lock Screen.
2. Tap **Edit** (Home Screen) or **Customize** (Lock Screen).
3. Add a StepRings widget.

**On Apple Watch:**
1. Touch and hold the watch face.
2. Tap **Edit** and swipe to the complications.
3. Choose a slot, then choose StepRings.

### A widget isn't up to date
- iOS and watchOS decide when widgets refresh.
- StepRings asks for a refresh when:
  - your steps go up by 25 or more
  - your goal changes
  - a new day starts
  - a Move, Exercise or Stand ring changes
- If you force-quit StepRings, iOS doesn't wake it in the background. Open the app again and its widgets update right away.

### The Watch or a complication is behind Apple Health
- Apple Watch saves your steps to Apple Health in batches, so it can lag.
- Opening StepRings on your iPhone sends its total to your Watch.
- The Watch never shows less than your iPhone's total for today.

## The Step Counter on Apple Watch

### How do I open the full-screen counter?
1. Add the **Step Counter** complication to your watch face.
2. Tap it.

It counts the same way as the complication:
- **Countdown:** the steps left to your goal, or how far ahead you are.
- **Count up:** the steps you've taken today.

### The count moves as I walk. Where does that come from?
- While the full-screen counter is open, StepRings counts with your Watch's pedometer, so you don't wait for Apple Health.
- It starts from your Apple Health total and never goes backwards while you watch.
- The pedometer runs only while the counter is on screen.
- It needs **Motion & Fitness** access:
  - StepRings asks the first time you open the counter.
  - Without it, the counter shows Apple Health's count instead.

### Why does it say "Updating…"?
- StepRings is reading your latest Apple Health total, so the counter starts from the right number.
- This usually takes a moment.
- If Health doesn't answer, the counter shows the pedometer's count instead.

### Does my Watch tap when I reach my goal?
- **Yes.** It plays a short haptic when you reach your goal.
- It plays once per day.

## Siri

### Can I ask Siri for my steps?
**Yes**, on iPhone or Apple Watch, with no setup. Include "StepRings" in the phrase:
- "How many steps have I taken in StepRings?"
- "How many steps are left in StepRings?"
- "How many steps ahead in StepRings?"
- "Am I ahead of my goal in StepRings?"

Without the app name, Siri answers from Apple Health instead.

## Privacy

### Does StepRings collect my data?
**No.** StepRings:
- only reads your data from Apple Health
- never writes to Apple Health
- keeps everything on your devices
- has no accounts, no ads and no tracking

See the [Privacy Policy](privacy.md).

### How do I remove StepRings' data?
1. Delete the app from your iPhone and Apple Watch.
2. Its saved totals and settings are removed with it.

Your Apple Health data stays as it is.
