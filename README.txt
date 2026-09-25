WITH — Korea + Japan complete deployment

This is a complete Vercel deployment package.

Behavior
- Existing Korea mode remains available.
- Travel-country button at bottom right: Auto / Korea / Japan.
- Auto mode checks the saved location and switches to Japan only when the country is Japan.
- Japan mode changes destination copy, translation target/speech to Japanese, and emergency information.
- Japan emergency: Police 110, Fire/Ambulance 119, JNTO Japan Visitor Hotline 050-3816-2787.
- Existing Find my way and Nearby use the saved GPS location and Google Maps.
- Existing /H001 through /H005 rewrites are preserved in vercel.json.

Deploy
1. Extract this ZIP.
2. Upload the contents as a new Vercel project (index.html must be at project root).
3. Open the deployed URL.
4. For testing from Korea, tap the bottom-right country button and choose Japan.
