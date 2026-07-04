CPALE Recall Deck v3.6

This version fixes the timer/sound features and adds quiz retry later.

New in v3.6:
- Reinstated and rebuilt timed MCQ quiz mode
- Optional timed mode: exactly 1 minute per question
- Timer starts when a timed quiz begins and each new question loads
- If time expires, the item is marked as timed out and the correct answer is automatically revealed
- In timed mode, Next becomes available only after answering or after timeout
- Added Enable sound button to reliably unlock browser audio on iPhone/Safari
- Correct answer: ping sound
- Wrong answer or timeout: low buzz sound plus vibration where supported
- Exit and save remains available
- New Exit & retry this quiz later option
- Retry missed button now first tries to load the saved retry quiz; otherwise it retries missed items
- Clear saved quiz button added

How to update:
1. Download and extract this ZIP.
2. Replace these files in your GitHub repository:
   - index.html
   - manifest.webmanifest
   - service-worker.js
   - README.txt
3. Commit changes.
4. Open the site with ?v=36:
   https://yourusername.github.io/CPALE-RECALL-DECK/?v=36
5. If using the Home Screen app, delete the old icon and add the updated site again.

How to use:
1. Go to Quiz.
2. Tap Enable sound once.
3. Select Timed quiz: 1 minute per question if you want timed mode.
4. Tap Start quiz.
5. Answer before the timer expires.
6. If the timer expires, the correct answer appears automatically.
7. Tap Next to proceed.
8. Use Exit and save to continue later, or Exit & retry this quiz later to restart that same quiz from question 1 later.

iPhone note:
- Safari/iOS may limit vibration for websites. If haptic vibration does not trigger, the wrong-answer buzz sound should still play after pressing Enable sound.
