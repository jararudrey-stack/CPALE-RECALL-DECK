CPALE Recall Deck v10.2 — Performance Fix

Problems fixed:
- The app no longer keeps the opening screen visible for 2.45 seconds.
- The opening transition now lasts about half a second on the first visit.
- Reloads in the same browser session skip the opening transition completely.
- The large opening animation was moved out of index.html into opening-eye.webp.
- This reduces index.html parsing work and lets the browser cache the animation separately.

Due MCQ performance:
- Sequence metadata is indexed once and reused.
- Connected-question groups are stored in fast in-memory maps.
- Due assignments and completion totals use a cached snapshot.
- Repeated Due-screen render requests are deduplicated.
- The Due tab no longer rebuilds every connected group repeatedly.
- The extra duplicate Due-tab click listener was removed.
- The hidden Due screen is no longer rendered during every dashboard update.
- Full connected-question recomputation now occurs only after MCQ imports or edits.

General startup improvements:
- Hidden flashcard lists and the removed flashcard review queue are no longer built during startup.
- The complete MCQ bank and topic pages render only when opened.
- App updates now refresh only the active screen instead of rebuilding every hidden screen.

Preserved:
- One due subtopic per subject
- Connected MCQ sequencing
- Due-completion message
- Quiz Finish flow
- Focus timer
- Analytics and growth priorities
- Firebase learners-online indicator
- Sleeping night ghost
- Fiery-eye opening animation

Files to upload:
- index.html
- opening-eye.webp
- manifest.webmanifest
- service-worker.js
- README.txt

Open after updating:
https://jararudrey-stack.github.io/CPALE-RECALL-DECK/?v=102

Important:
Upload opening-eye.webp together with the other files. The opening animation will not appear if that file is missing.

Safari cache:
After deployment, refresh several times. If v10.1 remains visible, clear website data for the GitHub Pages site and reopen the v=102 URL.
