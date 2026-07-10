CPALE Recall Deck v10.1 — Connected MCQ Sequences

Connected-question fix:
- Connected MCQs are now treated as one question block.
- The app shuffles independent blocks instead of shuffling every question individually.
- Questions inside a connected block always retain their original logical order.
- A follow-up question appears immediately after its main scenario question.
- Connected blocks are kept intact even when this slightly exceeds the selected quiz length.
- Reviewing missed items also restores the main question and the complete connected sequence.

How connections are detected:
- Original CSV/import order
- Same subject, deck, and subtopic
- Phrases such as “using the same data,” “based on the preceding information,” and similar references
- Main questions that explicitly state that several questions use the same information
- Repeated scenario entities, values, or substantially shared facts
- Short dependent follow-up questions after a detailed main scenario

Quiz improvements:
- Connected questions display a Connected Set position indicator.
- Free-practice quizzes randomize complete question blocks, not individual connected questions.
- Imported MCQs receive stable sequence-order metadata for future quizzes.

Due MCQ improvements:
- Due selection chooses complete connected blocks.
- A connected set is never divided between different due sessions.
- Existing daily due schedules are rebuilt once for the new sequence system.
- Due sets continue to use one adaptive subtopic per subject.

Due-completion message:
- The Due screen displays “All due MCQs have been answered” after completion.
- The last answered due item triggers the same confirmation message.
- The quiz-results screen clearly confirms when the entire daily due rotation is complete.
- The completion message remains visible until the next due schedule is generated at midnight Philippine time.

Files to upload:
- index.html
- manifest.webmanifest
- service-worker.js
- README.txt

Open after updating:
https://jararudrey-stack.github.io/CPALE-RECALL-DECK/?v=101

Safari cache:
Refresh several times after deployment. If the previous version remains visible, clear website data for the GitHub Pages site and reopen the v=101 URL.
