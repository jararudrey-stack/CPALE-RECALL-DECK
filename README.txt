CPALE Recall Deck v4.4

This fixes the Finish button visibility after a completed quiz and adds Growth Areas.

Visible confirmation:
- The Quiz screen title shows "v4.4 controls".

Finish fix:
- A new separate completed-quiz panel appears after a quiz is completed.
- The panel has a large Finish button.
- Finish clears the completed quiz session and resets the Quiz screen to no active quiz.
- The old result box may still show the score, but the new panel is separate so the Finish button is much harder to miss or break.

New Growth Areas feature:
- After quiz completion, the completed-quiz panel shows suggested growth areas.
- Growth areas are based on the subjects/decks/topics of wrong answers or timed-out answers.
- If no items were missed, it tells you no major growth area was detected.

How to update:
1. Download and extract this ZIP.
2. Replace these files in GitHub:
   - index.html
   - manifest.webmanifest
   - service-worker.js
   - README.txt
3. Commit changes.
4. Open:
   https://jararudrey-stack.github.io/CPALE-RECALL-DECK/?v=44

If you do not see "v4.4 controls", you are still seeing the cached old version.
