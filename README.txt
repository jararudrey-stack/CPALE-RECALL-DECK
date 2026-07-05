CPALE Recall Deck v6.0

Firebase live presence update:
- Added a minimalist live learners-online indicator to the dashboard.
- Uses Firebase Realtime Database presence records.
- Shows anonymous connected learners only; it does not collect names or account data.
- Uses heartbeat updates and onDisconnect cleanup.
- Keeps the v5.9 smooth page transitions and v5.8 polished bottle countdown.

Required Firebase Realtime Database rules:
{
  "rules": {
    "presence": {
      ".read": true,
      "$sessionId": {
        ".write": true,
        ".validate": "newData.val() == null || (newData.hasChildren(['online', 'lastSeen']) && newData.child('online').val() == true && newData.child('lastSeen').isNumber())"
      }
    }
  }
}

How to update GitHub:
1. Download and extract this ZIP.
2. Replace these files:
   - index.html
   - manifest.webmanifest
   - service-worker.js
   - README.txt
3. Commit changes.
4. Open:
   https://jararudrey-stack.github.io/CPALE-RECALL-DECK/?v=60

If Safari still shows the old version, refresh several times or clear website data for the GitHub Pages site.
