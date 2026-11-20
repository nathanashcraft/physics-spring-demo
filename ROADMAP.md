# Spring Physics Demonstration Roadmap

Each milestone should leave the project in a state that can be opened in a browser and tested before work moves on.

## Milestone 1 — Smallest working spring demo

- [x] Create a single-page vertical spring demonstration that opens directly in a browser.
- [x] Let the user adjust spring constant, resting length, and an applied force. Allow force in either direction so the spring can stretch or compress.
- [x] Add an **Apply and release** button that starts a simple spring motion and lets it gradually settle.
- [x] Show the spring’s current length and its stretch or compression from resting length as it moves.
- [x] Keep the spring and readouts visible while the user changes settings and tries the demo.

**Browser check:** [ ] Open the page, change each input, apply both a stretching and compressing force, and confirm that the spring moves, settles, and the readouts track its changing length.

## Milestone 2 — Hanging mass option

- [x] Add a choice between an applied force and a hanging mass.
- [x] In mass mode, let the user adjust the mass and show its weight as the load on the spring.
- [x] Preserve the spring constant and resting-length controls, motion, and live readouts in both load modes.

**Browser check:** [ ] Switch between force and mass modes, change each load, and confirm each produces a visible response with matching readouts.

## Milestone 3 — Reusable motion controls

- [x] Add pause and reset controls.
- [x] Make reset return the spring and readouts to a clear resting state.
- [x] Ensure changing settings and switching load modes produces predictable results after reset or when motion is started again.

**Browser check:** [ ] Start the spring, pause and resume it, reset it, then change settings and run another demonstration.

## Milestone 4 — First-version clarity and polish

- [x] Label all controls and readouts with units and concise explanations.
- [x] Make the page usable on both desktop and narrow mobile screens.
- [x] Refine the visual hierarchy so the spring, controls, and changing measurements are easy to follow.

**Browser check:** [ ] Open the finished page at desktop and mobile widths; confirm controls remain usable and the spring and measurements remain readable.

## First-version scope

Milestones 1 and 2 deliver the three agreed must-haves: adjustable spring/load inputs, a spring that moves and gradually settles when started, and live measurements. Milestones 3 and 4 add optional controls and polish.
