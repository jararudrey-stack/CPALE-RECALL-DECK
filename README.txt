CPALE Recall Deck v3.5

New in v3.5:
- Correct answer feedback: ping sound
- Wrong answer feedback: haptic vibration where supported plus a low buzz sound
- Optional timed MCQ quiz mode
- Timed quiz gives exactly 1 minute per question
- If time expires, the app automatically marks the item as timed out and reveals the correct answer
- In timed mode, the Next button becomes available after you answer or after time expires
- Timer state is saved when you exit and resume an unfinished quiz
- Timer pauses when you exit and resumes with remaining time when you resume
- Quiz progress bar from v3.4 remains

Important iPhone note:
- Haptic vibration depends on browser/device support. If iOS Safari does not allow vibration, the app still plays the wrong-answer buzz sound.
- Sound starts after a user action such as Start quiz or selecting an answer.

How to update GitHub:
1. Download and extract this ZIP.
2. Replace/upload these files in your GitHub repository:
   - index.html
   - manifest.webmanifest
   - service-worker.js
   - README.txt
3. Commit changes.
4. Open your site with ?v=35 at the end:
   https://yourusername.github.io/CPALE-RECALL-DECK/?v=35
5. If using the Home Screen app, delete the old icon and add the updated site again.

How to use timed MCQ:
1. Go to Quiz.
2. Change Untimed quiz to Timed quiz: 1 minute per question.
3. Tap Start quiz.
4. Answer before the timer expires.
5. If the timer expires, the correct answer appears automatically.
6. Tap Next to proceed.
