CPALE Recall Deck v4.8

This is a redone clean MCQ grouping update based on the last working v4.6 base.

Why this redo:
- The earlier v4.7 build could fail during startup because the organizer could run before its constants were initialized.
- v4.8 fixes that by loading the organizer before the app reads saved local data.

What changed:
- Removed Auditing Problems from the subject dropdown and import prompt subject list.
- Existing Auditing Problems items are preserved by moving them under Auditing Theory.
- New MCQs now merge into the existing subject + deck/topic when names match.
- Matching is cleaner: spacing, capitalization, and "and" vs "&" differences are normalized.
- For Auditing Theory, the app automatically groups these common lecture decks:
  - Practice & Regulation
  - Fundamentals of Auditing & Assurance Services
  - Introduction to Auditing
- Duplicate deck names under the same subject are merged on load and on every save.
- MCQ list sorting is cleaner: subject, deck, topic, then question.

Recommended CSV use:
subject,deck,topic,question,A,B,C,D,correct,explanation

Example:
Auditing Theory,Practice & Regulation,PRBOA Qualifications,...

How to update GitHub:
1. Download and extract this ZIP.
2. Replace these files in your GitHub repository:
   - index.html
   - manifest.webmanifest
   - service-worker.js
   - README.txt
3. Commit changes.
4. Open:
   https://jararudrey-stack.github.io/CPALE-RECALL-DECK/?v=48

If the page still shows the old version, refresh several times or clear Safari website data for the GitHub Pages site.
