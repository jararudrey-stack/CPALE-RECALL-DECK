CPALE Recall Deck v2

What this version includes:
- Local profile / local "login"
- Decks by CPALE subject and topic
- Dashboard with due cards, total cards, streak, accuracy, and mastered cards
- Review mode with spaced repetition
- Filters: due cards, all cards, weak cards, mastered cards
- Add, edit, and delete cards
- Create custom decks
- CSV import/export
- JSON backup/restore
- PDF-to-text helper for text-based PDFs
- GPT prompt for turning notes into importable flashcards
- Mobile-friendly layout
- PWA files included for hosting online and adding to iPhone Home Screen

Important:
- This is still a static/local app. The "login" is only a local profile.
- Your cards are stored in the browser's localStorage.
- Export CSV or JSON backups regularly.
- PDF extraction works best for text-based PDFs, not scanned pages/images.
- The PDF helper uses a public PDF.js CDN, so it needs internet access when extracting PDFs.

How to use on iPhone:
1. Host the folder online using GitHub Pages, Netlify, or Vercel.
2. Open the site in Safari.
3. Tap Share.
4. Tap Add to Home Screen.

How to import from ChatGPT:
1. Copy your notes or extracted PDF text.
2. Ask ChatGPT using the prompt inside the Import screen.
3. Copy the CSV output.
4. Paste it into Import.
5. Tap Import CSV / Q&A.

CSV format:
subject,deck,topic,question,answer

Example:
FAR,Inventory,PAS 2,What is NRV?,Estimated selling price less costs to complete and sell.
RFBT,Obligations,Civil Code,What are the elements of obligation?,Active subject; passive subject; prestation; juridical tie.
