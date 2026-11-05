# Log

Newest at the top.

## 2026-11-05 (later)
- Looked up what each interview round tests and added it to [[Research]]. Amazon new grad loop = 2 coding, 1 low-level design, 1 behavioral (Bar Raiser), with Leadership Principle questions in every round.
- Moved the live AI voice interviewer into version 1 (it was "later").
- Added a new page in the Figma file, "Version 2 (round types + live voice)", with 5 screens: start, coding, low-level design, behavioral, loop results. Every round has a live voice interviewer with captions. The old screens are still on the first page.
- Changed how feedback works: no feedback between rounds (like a real interview). Instead, one "Loop results" page at the end shows the final result, the top 3 things to practice, and a section for every round (coding scores, design scores, and a score per Leadership Principle + a STAR check for behavioral). Removed the old per-round feedback screens and the old summary.
- Files changed: `vault/Research.md`, `vault/Log.md`
- Left to do: pick the tech stack (#15). The voice interviewer will need speech-to-text and text-to-speech.

## 2026-11-05
- Made a mock UI (wireframes) for version 1 on a design canvas: https://claude.ai/artifact/3RtxpvpcEryVNByW1Zmc6Z
  - 4 screens: Start a loop, Coding round, Round feedback, Loop summary. The buttons link the screens together.
  - Text in [brackets] is a placeholder.
- Rebuilt the same 4 screens in Figma: https://www.figma.com/design/I817KhNKFbQfRARy6s4obV
- Files changed: `vault/Log.md`, `vault/Overview.md`
- Left to do: look over the screens and change what you want, then pick the tech stack (#15).

## 2026-10-31
- Wrote [[Research]] for issue #14: apps compared, the gap, and the must-have features for version 1. It's a draft based on the backlog, so check it against your own research.
- Files changed: new `vault/Research.md`, `vault/Log.md`, `vault/Overview.md`
- Left to do: move #14 to Done on the board, then do rough wireframes and pick the tech stack (#15).

## 2026-10-26
- Made the board minimal: only 3 cards in Backlog (#14 research + features, #15 scope + tech stack, #16 first version of the interview loop). Everything else was taken off the board and listed under "Later" in [[Interview Loop Backlog]].
- Files changed: `vault/Interview Loop Backlog.md`, `vault/Log.md`
- Left to do: delete unused issues #1 to #13 and #17 to #25 on GitHub, then start #14.

## 2026-10-22
- Renumbered the list in [[Interview Loop Backlog]] as 1 to 12 so it's easier to read.
- Put all 25 issues in order in [[Interview Loop Backlog]]: the current backlog (#14 to #25) and the old ones to delete (#1 to #13). Also wrote down why the numbers start at #14.
- Files changed: `vault/Interview Loop Backlog.md`, `vault/Log.md`
- Connected this project folder to GitHub (github.com/snowkang08-star/map26-27). Notes and code now upload there. See [[Git Basics]] for how to save work.
- `vault/.obsidian/` is left out on purpose (listed in `.gitignore`).
- Files changed: new `.gitignore`, new `vault/Git Basics.md`, `vault/Overview.md`, `vault/Log.md`
- Redid the board backlog in last year's (map25) style: full-sentence titles, all in **Backlog**. New issues are #14 to #25 in the repo `snowkang08-star/map26-27`.
- The old issues #1 to #13 are still there. I'll delete them myself.
- GitHub had a problem loading project boards today, so the board may look empty until it's fixed. The issues are on it.
- Files changed: `vault/Log.md`, `vault/Interview Loop Backlog.md`
- Filled in the GitHub Project board. Made all 13 backlog items real issues (#1 to #13) in the repo `snowkang08-star/map-26-27`, each with a description.
  - **Ready:** #1 Research existing apps, #2 List user features
  - **Backlog:** #3 to #13 (scope, tech stack, all features, beta-test). That's 11 cards, which is over the column's limit of 5, so GitHub just shows a warning.
- Files changed: `vault/Overview.md`, `vault/Log.md`
- Left to do: connect the `code/` folder to the GitHub repo, then start #1.
- Added a new feature idea: an **AI voice interviewer** that talks to the user through the whole loop (issue #12 in [[Interview Loop Backlog]]). Also added it to the goals in [[Overview]].
- Files changed: `vault/Interview Loop Backlog.md`, `vault/Overview.md`, `vault/Log.md`
- Decided on the project: **Interview Loop**, an app that simulates tech interviews (Amazon and other FAANG companies) for CS students.
- Made an empty GitHub Project board for it: github.com/users/snowkang08-star/projects/4
- Filled in [[Overview]] with what the project is, goals, and a to-do list.
- Wrote a draft list of issues for the board: [[Interview Loop Backlog]]
- Files changed: `vault/Overview.md`, `vault/Log.md`, new `vault/Interview Loop Backlog.md`
- Left to do: set up git + GitHub repo, add the issues to the board, start research.

## 2026-10-21
- Set up the project: `code/` for code, `vault/` for notes. Claude reads and updates these notes automatically.
- Set up Obsidian (opened `vault/`) and VS Code with Claude Code.
