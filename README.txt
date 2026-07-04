CPALE Recall Deck v4.2

This redoes the Finish fix.

Visible confirmation:
- The Quiz screen title shows "v4.2 controls".

Button labels:
- Exit and Save
- Exit and Not Save
- Restart
- Finish

Fix:
- Finish now uses direct clearing logic:
  1. Stops the timer
  2. Clears quizQueue, quizIndex, quizAnswers, and timer state
  3. Removes saved quiz session storage
  4. Exits to Dashboard
- It also has a delegated fallback listener in case the normal click handler does not attach.

How to update:
1. Download and extract this ZIP.
2. Replace these files in GitHub:
   - index.html
   - manifest.webmanifest
   - service-worker.js
   - README.txt
3. Commit changes.
4. Open:
   https://jararudrey-stack.github.io/CPALE-RECALL-DECK/?v=42

If you do not see "v4.2 controls" beside the Quiz title, you are still seeing the cached old version.
