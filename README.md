# Inconsistent Firebase onAuthStateChanged Listener

This repository demonstrates a bug and its solution related to the Firebase `onAuthStateChanged` listener's inconsistent behavior.  The listener sometimes fails to update the app's UI when the user's authentication state changes due to network issues or other unexpected events.

The `inconsistentAuth.js` file shows how the listener may not always react to changes.  `consistentAuth.js` presents a more robust implementation.