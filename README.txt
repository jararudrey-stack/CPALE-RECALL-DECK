CPALE Recall Deck v4.0

This is a clean redo of the MCQ quiz options update.

Visible confirmation:
- The Quiz screen title now shows "v4.0 controls" so you can confirm the new file loaded.

Active quiz controls:
- Option 1: Exit and Save
  Saves the current quiz progress so you can finish it later.

- Option 2: Exit and Not Save
  Removes the current quiz attempt and clears the quiz session from the screen.

- Option 3: Restart
  Restarts the same quiz from item 1 and clears your current answers.

After quiz completion:
- Option 4: Finish
  Appears only after the quiz is completed. It terminates and clears the completed quiz session from the screen.

Still included:
- Previous / Next
- Resume saved quiz
- Review missed
- New quiz
- Timed quiz: 1 minute per question
- Sound/haptic feedback
- Progress bar

How to update:
1. Download and extract this ZIP.
2. Replace these files in GitHub:
   - index.html
   - manifest.webmanifest
   - service-worker.js
   - README.txt
3. Commit changes.
4. Open your site with:
   https://jararudrey-stack.github.io/CPALE-RECALL-DECK/?v=40

Important cache step:
- If you do not see "v4.0 controls" beside the Quiz title, the old site is still cached.
- Open with ?v=40.
- On iPhone Home Screen app, delete the old icon and add the updated site again.
