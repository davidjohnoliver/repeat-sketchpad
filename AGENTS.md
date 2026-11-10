# Notes for agents working on Repeat Sketchpad

The whole app is `index.html`: markup, styles and script in one file, with no build step. GitHub Pages serves it from `main`, so a push to `main` is a release.

## Keyboard shortcuts are optional

- Every feature must work fully by pointer and touch. Much of the use is on phones and tablets, where there is no keyboard.
- A new feature does not need a keyboard shortcut. Leave shortcuts out unless the user asks for one, or one is cheap and follows an obvious convention.
- Do not lead a design proposal with shortcuts or modifier keys, and do not spend toolbar or hint space on them. Describe the on-screen control first.
- A modifier key (Shift, Alt) may speed up an action, but there must always be a visible control that does the same thing.
- If you do add a shortcut, list it in the README table.
