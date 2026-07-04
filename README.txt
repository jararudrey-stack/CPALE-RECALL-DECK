CPALE Recall Deck v4.1

This fixes the Finish button after quiz completion and removes the "Option #" wording.

Visible confirmation:
- The Quiz screen title now shows "v4.1 controls".

Active quiz buttons:
- Exit and Save
  Saves the current quiz progress so you can finish it later.

- Exit and Not Save
  Removes the current quiz attempt and clears the quiz session.

- Restart
  Restarts the same quiz from item 1 and clears your current answers.

After quiz completion:
- Finish
  Clears the completed quiz session, removes it from the quiz screen, and exits to the Dashboard.

Fix included:
- Finish now uses a stronger clearing function.
- Finish also has a fail-safe click handler so it still works even if the normal listener does not attach.

How to update:
1. Download and extract this ZIP.
2. Replace these files in GitHub:
   - index.html
   - manifest.webmanifest
   - service-worker.js
   - README.txt
3. Commit changes.
4. Open your site with:
   https://jararudrey-stack.github.io/CPALE-RECALL-DECK/?v=41

If you do not see "v4.1 controls" beside the Quiz title, the old cached version is still loading.
