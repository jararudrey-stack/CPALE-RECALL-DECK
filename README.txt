CPALE Recall Deck v3.3

This version fixes the MCQ import problem more aggressively.

New in v3.3:
- Strict MCQ CSV importer
- Broken rows are skipped instead of imported
- Import summary shows imported count and skipped broken rows
- Stronger "Remove broken imported MCQs" cleanup
- CSV file loader: choose a .csv file and load it into the import box
- Handles curly quotes, code fences, and copied citation markers better
- Version marker appears in the subtitle as v3.3 so you can confirm the update loaded

How to update:
1. Download and extract this ZIP.
2. In GitHub, replace:
   - index.html
   - manifest.webmanifest
   - service-worker.js
   - README.txt
3. Commit changes.
4. Open the website with ?v=33 at the end, for example:
   https://yourusername.github.io/CPALE-RECALL-DECK/?v=33
5. If you installed it on Home Screen, remove the old Home Screen icon and add it again after the update.

How to fix broken MCQs:
1. Open the website.
2. Go to Backup.
3. Tap Export full JSON first.
4. Tap Remove broken imported MCQs.
5. Tap Remove duplicate MCQs.
6. Re-import the CSV.

Best re-import method:
- Use a real .csv file instead of copy-pasting from chat.
- Go to Import.
- Choose MCQ CSV.
- Choose the CSV file.
- Tap Load CSV file into box.
- Tap Import.

Important:
- If the old version still appears, Safari or the PWA is caching it. Open the site with ?v=33 or remove and reinstall from Home Screen.
