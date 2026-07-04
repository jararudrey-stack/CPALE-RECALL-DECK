CPALE Recall Deck v4.3

This fixes the Finish button after a completed quiz.

Visible confirmation:
- The Quiz screen title shows "v4.3 controls".

What changed:
- Finish no longer tries to exit to Dashboard.
- Finish now stays on the Quiz screen and immediately clears the completed quiz.
- After tapping Finish, the Quiz screen resets to a blank/no-active-quiz state.
- The completed quiz queue, answers, timer state, and saved session storage are cleared.
- Finish has both an inline click action and a fallback listener.

Button labels:
- Exit and Save
- Exit and Not Save
- Restart
- Finish

How to update:
1. Download and extract this ZIP.
2. Replace these files in GitHub:
   - index.html
   - manifest.webmanifest
   - service-worker.js
   - README.txt
3. Commit changes.
4. Open:
   https://jararudrey-stack.github.io/CPALE-RECALL-DECK/?v=43

If you do not see "v4.3 controls", you are still seeing the cached old version.
