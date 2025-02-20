# Firebase Realtime Database: Nested Object Update Anomaly

This repository demonstrates a subtle issue in Firebase Realtime Database where updates to nested objects may not reflect correctly if not handled properly.  The client-side code successfully writes data, but the database doesn't update as expected due to how Firebase handles partial updates to nested objects.

The `bug.js` file showcases the problematic code.  `bugSolution.js` provides a corrected version.  The key is understanding how to properly replace or update nested objects to ensure data integrity in Firebase Realtime Database.