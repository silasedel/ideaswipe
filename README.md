# ideaswipe

Swipe left/right on YouTube video ideas. Make a list, get a 4-digit code, and anyone who types the code gets the list to swipe through.

Live: https://silasedel.github.io/ideaswipe/

Lists are stored in a free Firebase Realtime Database. `database.rules.json` is a copy of its security rules: anyone can read a list by its code, only the creator (who holds a secret in their browser) can edit or delete it.
