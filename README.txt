CPALE Recall Deck v3

New in v3:
- CPALE-style multiple choice quiz mode
- New Quiz tab
- New MCQs tab for adding/editing/deleting MCQ items
- MCQ CSV import/export
- Quiz score tracking
- Explanation after every answer
- Retry missed questions
- Full JSON backup includes decks, flashcards, MCQs, quiz progress, and profile
- Automatically migrates most v2 local data and adds sample MCQs

How to update your GitHub website:
1. Download and extract this ZIP.
2. In your GitHub repository, upload/replace:
   - index.html
   - manifest.webmanifest
   - service-worker.js
   - README.txt
3. Commit changes.
4. Open your GitHub Pages site.
5. If the old version still appears, refresh Safari or remove the site from Home Screen and add it again.

MCQ CSV import format:
subject,deck,topic,question,A,B,C,D,correct,explanation

Example:
RFBT,RFBT General,Obligations,"D obliged himself to give C either his car, motorcycle, or P300,000 at D's choice. Before choice, the car is lost by fortuitous event. What is the effect?","The obligation is extinguished.","D may still choose between the motorcycle and P300,000.","C may demand the value of the car plus damages.","The obligation becomes purely monetary.","B","Alternative obligation is not extinguished if other prestations remain before choice."

How to generate MCQs with ChatGPT:
Use the prompt inside the Import screen. Choose MCQ CSV prompt, copy it, paste your CPALE notes after it, then import the generated CSV into the website.

Important:
- Data saves locally in the browser.
- Export full JSON regularly for backup.
- For best safety before updating, export JSON from the current website first.
