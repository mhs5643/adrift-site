# Changelog

Site changes, newest first. Facts, no guilt.

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
