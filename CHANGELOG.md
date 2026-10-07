# Changelog

Site changes, newest first. Facts, no guilt.

## 2026-10-07 (Adrift 1.0.2)

- **setup-help.html:**
  - **`#classic` — the walkthrough,** rewritten to Adrift 1.0.2's fourteen
    cards (`#step-1…14`, seven per part; 1.0.1 had five), following the
    app's copy. The snag section is kept, reworded in the app's register
    ("parts"), plus the both-boxes snag.
  - The fork and the `#ios27` section no longer say "From Adrift 1.0.2":
    it's out.
- **support.html:** the iOS 27 lines no longer say "From Adrift 1.0.2".
  "Do I need two parts for every app?" reads: no on iOS 27, yes on iOS 26
  or earlier.
- **index.html:** the intro and Setup lines no longer say "From Adrift
  1.0.2".

## 2026-10-04 (stage 1, ahead of Adrift 1.0.2)

- **setup-help.html:** a fork at the top sends iOS 27 readers to `#ios27`
  and iOS 26-or-earlier readers to `#classic`.
  - **`#ios27` — Adrift 1.0.2's two ready-made parts,** up ahead of its
    release so its links land. The section opens "From Adrift 1.0.2".
    The three pack cards (`#pack-step-1…3`) with the app's ringed stills,
    the check, "good to know" (other iPhones sync switched off; parts
    built before iOS 27 are named "App", "App 2"; an app installed later;
    the lock). The editor cards for building the parts yourself
    (`#editor27-step-01…14`, zero-padded, with stills), and an iOS 27 snag
    section written from the app's own diagnosis copy. The steps and
    snags follow the app's copy, with "your app" for the app's name.
  - **`#classic` — the iOS 26-or-earlier walkthrough is unchanged until
    Adrift 1.0.2's release:** Adrift 1.0.1's five steps (`#step-1…5`) and
    its snag section, word for word, now under the fork's second heading.
  - **On every iPhone:** the lock line, and links to both cleanups.
- **support.html:**
  - `#ios27-teardown`: removing Adrift's parts on iOS 27. From Adrift
    1.0.2, removing one app in Adrift keeps the ready-made parts. Leaving
    altogether deletes Adrift Opens and Adrift Closes in All Shortcuts
    (touch and hold → Delete → Delete Shortcut, "This shortcut will be
    deleted from all of your iCloud devices."), then any parts you built
    yourself, then the app.
  - `#teardown` retitled for iOS 26 or earlier, with a pointer up. Its
    steps are unchanged.
  - New question `#lock`: the timer stops at a lock; after an unlock,
    leave the app and open it again. It's the same on every iOS version,
    so it sits outside the iOS 27 section.
  - "Do I need two parts for every app?" replaces the old one-pair
    question: no on iOS 27 from Adrift 1.0.2; yes on iOS 26 or earlier,
    or before 1.0.2.
  - The island question no longer says "lock, glance, it's counting": a
    lock stops a tracked app's timer.
- **index.html:** the root's fragment forward also sends `#ios27-teardown`
  to `support.html#ios27-teardown` (the app links the site root). The
  intro, Setup and Support lines say "parts", as the app does, and
  describe both setups, the iOS 27 one from Adrift 1.0.2.

## 2026-10-04

- **privacy.html:** regenerated for Adrift 1.0.2, ahead of its release, to
  match the app's Privacy screen: all 56 of Adrift's own events, word for
  word (the page listed 28), with the three 1.0.2 retired marked for 1.0.1
  installs; what TelemetryDeck's library adds (its own signals, and
  standard details on every event, the date and time included); and the
  parts sentence (they live in Apple's Shortcuts app, iCloud sync is
  Apple's, and on iOS 27 Adrift counts only the apps you've added).

## 2026-08-21

- Added the setup page, [setup-help.html](setup-help.html), linked prominently
  from the index (its own Setup section + footer) and the support page (intro
  line + footer) — the app's 1.0.1 walkthrough in written form, verified
  against the shipped step cards: deep link lands on the creation sheet →
  search "app" → App → pick the app, "Is Opened" only → Run Immediately on,
  "Notify When Run" off → Create New Shortcut → scroll to Adrift → Start App
  Timer, App set again ("Shortcuts likes to be told twice") → Done → the
  closing half with "Is Closed" / Stop App Timer. One quiet line notes older
  iOS labels the button "New Blank Automation". Copy stays in the app's halves
  register; no setup time estimates anywhere, matching the app's estimate-free
  copy.
  - Step cards carry ids `step-1`–`step-5`, matching the app's Stuck?-sheet
    deep links (`setup-help.html#step-N`) one-to-one with its five backup
    steps.
  - "Let's find the snag." section mirrors the app's diagnosis register,
    symptom-first: nothing arrived / open landed, close didn't / close landed,
    open didn't / wrong-app signal, plus Run After Confirmation, "Notify When
    Run" on, and view-to-heal ("viewing it is enough to re-link the action").
  - The full walkthrough video is NOT hosted anywhere yet (the app bundles its
    clips; no public URL exists) — the video slot is a clearly marked
    TODO(video hosting) comment in the page source, and the visible
    second-screen offer is this page itself until the video has a URL. The
    app's "Watch the full walkthrough" button already lands here regardless,
    at the stuck step's card.
- support.html: the cleanup guide's heading id renamed `cleanup` → `teardown`
  so the app's remove-card deep link lands on it; nothing ever linked the old
  id. Verified against the app: 1.0.1 actually builds that link as the SITE
  ROOT + `#teardown` (not support.html), so index.html gains a two-line
  fragment forward — arriving at the index with `#teardown` replaces to
  `support.html#teardown`; with scripts off it degrades to the index top,
  which links the same guide.
- FAQ added under support's Questions: "Which iPhones show the island timer?"
  — the island list (iPhone 14 Pro/Pro Max and every iPhone since, except the
  16e) vs. "your timer lives on the Lock Screen: lock, glance, it's counting,"
  in the app's fact-not-apology framing; reminders stated the same everywhere
  (banners at the chosen thresholds, mid-scroll, island or not).
- Consistency sweep: canon contact line "you'll hear back from one of us" on
  the new page; current pack names only (Adrift, Calm, Scripture, Quotes,
  Perspective, Note to Self — none needed naming on these pages); no old
  preset names; no setup time estimates. The teardown guide's "About 20
  seconds" line stays — it's the teardown estimate, and the headline's canon.

## 2026-08-05

- Added a dedicated support page, [support.html](support.html), linked from the
  index and every footer. The App Store Support URL keeps pointing at the site
  root. All app-behavior claims below were device-verified 2026-08-03.
  - Headline placement: "Leaving Adrift? The 20-second cleanup." Teardown steps
    in the setup walkthrough's dialect (step count, instruction, wrong-turn
    guard line, mock Shortcuts UI): Automation tab → swipe left on each of the
    two automations per tracked app → Delete; a full swipe deletes in one
    motion.
  - Warning box: deleting the app before its automations leaves an "Automation
    failed" banner over the tracked app on every open and close. Inside the
    broken automation, Shortcuts shows "Unknown — this action could not be
    found" with an "Update Shortcuts" link that is a dead end — deleting the
    automation is the fix.
  - Reinstall note: reinstalling revives the automations with no re-setup; if
    one direction still errors, viewing that automation in Shortcuts and
    backing out re-links the action.
  - FAQ: one automation cannot cover several apps — the trigger can watch many,
    but the action records only one, so it's one open + one close pair per
    tracked app.
- Index retitled from "Adrift — Support" to "Adrift" now that support has its
  own page; its Support section links the cleanup guide.
- Consistency sweep: support contact language is now the canon "you'll hear
  back from one of us" (was "a human (Max, who made it) will answer"). No old
  preset names (Gentle/Standard/Firm) and no "Steady" pack references anywhere
  on the site — "gentle reminders" on the index is the adjective, not the
  preset, and stays.

## 2026-07-22

- Initial site: index (with support contact) and privacy pages.
