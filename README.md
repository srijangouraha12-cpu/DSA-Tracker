# Winter Arc 2026

A dark, responsive, local-first DSA and Codeforces quest tracker. It uses plain HTML, CSS and JavaScript; there is no build step or account.

## Open it

Open `index.html` in a modern browser. If the browser blocks Codeforces API requests from a `file:` page, open a terminal in this folder, run `py -m http.server 8000`, then visit `http://localhost:8000`. Codeforces sync uses public endpoints and requires only a handle.

## Progress and data

Progress is stored in this browser's local storage. Use **Arc Codex → Export Save File** to make a backup, or import a save on another browser. Reset is available from the gear button.

The included tracker ships with a bundled A2Z problem dataset and marks a must-do subset inside each topic. Must-do problems control dungeon unlocks; the remaining problems stay visible as extra trackable practice. The current Take U Forward sheet can change, so DSA World still supports adding/editing encounters and importing JSON arrays with `name`, `topic`, and optional `difficulty`, `status`, `quality`, and `notes` fields.

## Rules in the app

- XP is based on question difficulty and Independent / Hint / Editorial solve quality. Time never scores.
- Normal, Busy and Very Busy quest modes use question counts.
- November 1–20, 2026 is Exam Arc: zero required DSA, optional bonus XP, and no streak punishment. Winter Arc resumes November 21.
- Topics unlock in route order after 60% mastery of non-deferred problems.
- Weekly missions are question-based and include a weekly boss challenge.
