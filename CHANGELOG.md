# Changelog

Site changes, newest first. Facts, no guilt.

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
