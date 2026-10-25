# Second Brain

A personal hub for tasks, notes, projects, a reading list and work thoughts.

The live app is a private Claude artifact.

- `index.html` is the page's source: one self-contained file with all markup, styles and script.
- The data (tasks, notes, reminders) is **not** in this repo. It lives in the artifact's database on Claude, so opening `index.html` on its own shows an empty "Open this page in Claude" screen.
- Smart features (auto-sort, Plan my day, Ask) use Claude through the artifact runtime and only work inside Claude.

## Deep links

Add one of these to the end of the artifact link:

| Link ending | Opens |
|---|---|
| `#today` | Today view |
| `#task`, `#note`, `#project`, `#link`, `#work` | That section |
| `#ask` | Ask tab |
| `#capture` | Quick capture only (good for a phone home-screen icon) |

## Updating

Pushing changes here doesn't update the live page. Ask Claude to republish the artifact from this repo's `index.html`.
