CPALE Recall Deck v5.1

This is a redone fix based on the last working v4.9.

What changed:
- Auditing · Auditing General is removed from default decks and from saved local data on startup.
- Old Auditing General items are automatically moved into actual Auditing topic decks.
  Examples:
  - Audit Risk / Assertions / Materiality -> FS Audit Overview
  - RA 9298 / PRBOA / PICPA / CPD -> Practice & Regulation
  - Assurance / Review / AUP / Compilation -> Fundamentals of Auditing & Assurance Services
  - ISQM / Quality Review -> Quality Management
  - Engagement Letter / Opening Balances / PSA 220 -> Pre-Engagement
  - Operational / Compliance / Government Audit -> Introduction to Auditing
- Auditing no longer creates a General deck.
- When taking a quiz, tapping Next scrolls the actual question back to a comfortable center position.
- Previous and queue-jump also auto-center the question.
- Decks remain in the main subject order, and topic decks stay in upload/creation order.

How to update GitHub:
1. Download and extract this ZIP.
2. Replace these files:
   - index.html
   - manifest.webmanifest
   - service-worker.js
   - README.txt
3. Commit changes.
4. Open:
   https://jararudrey-stack.github.io/CPALE-RECALL-DECK/?v=51

If it still shows the old version, refresh several times or clear Safari website data for the GitHub Pages site.
