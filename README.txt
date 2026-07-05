CPALE Recall Deck v4.9

This update fixes the subject/topic arrangement.

What changed:
- "Auditing Theory" is now displayed simply as "Auditing".
- Old imported rows using "Auditing Theory" still work and are automatically shown under "Auditing".
- Old "Auditing Problems" items are preserved by moving them under "Auditing".
- Main subject order is retained:
  FAR, AFAR, MAS, Auditing, Taxation, RFBT.
- Within each subject, the General deck appears first.
  Examples:
  FAR General
  Auditing General
  Taxation General
- Specific topic decks are no longer arranged alphabetically.
- Specific topic decks now follow upload/creation order.
- New MCQs uploaded later for an existing subject/topic are added to that same existing deck, without changing its position.
- MCQs inside each deck are also shown in upload order.

Recommended CSV use:
subject,deck,topic,question,A,B,C,D,correct,explanation

Examples:
Auditing,Practice & Regulation,PRBOA Qualifications,...
Auditing Theory,Practice and Regulation,PRBOA Qualifications,...

Both examples will go under:
Auditing · Practice & Regulation

How to update GitHub:
1. Download and extract this ZIP.
2. Replace these files in your GitHub repository:
   - index.html
   - manifest.webmanifest
   - service-worker.js
   - README.txt
3. Commit changes.
4. Open:
   https://jararudrey-stack.github.io/CPALE-RECALL-DECK/?v=49

If the page still shows the old version, refresh several times or clear Safari website data for the GitHub Pages site.
