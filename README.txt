CPALE Recall Deck v3.2

New in v3.2:
- Smarter CSV importer for pasted MCQ CSV
- Handles smart/curly quotes copied from chat apps
- Strips markdown code fences from pasted CSV
- Strips ChatGPT/file citation markers from pasted text
- Auto-detects MCQ CSV if the header contains correct/explanation
- Added Backup button: Remove broken imported MCQs

Why this version matters:
If your imported MCQs showed cut-off questions, quoted subjects like “RFBT”, or wrong answers, the older importer likely misread commas because the copied CSV used smart quotes instead of normal CSV quotes.

How to fix your current website:
1. Upload/replace these files in GitHub:
   - index.html
   - manifest.webmanifest
   - service-worker.js
   - README.txt
2. Commit changes.
3. Open your GitHub Pages website.
4. Go to Backup.
5. Export full JSON first for safety.
6. Tap Remove broken imported MCQs.
7. Tap Remove duplicate MCQs if needed.
8. Re-import the MCQ CSV.

Best import format:
subject,deck,topic,question,A,B,C,D,correct,explanation

Important:
- This app saves data locally in your browser.
- Always export full JSON before cleanup or major imports.
