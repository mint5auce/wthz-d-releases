# Published Alpha 1 verification

Verified on 28 September 2026 after publication.
All five release assets were downloaded without GitHub authentication and matched the independently retained local hashes.
The downloaded DMG passed stapled-ticket validation and Gatekeeper assessment as Notarized Developer ID.
Its mounted app matched the complete original final signed inventory and passed strict deep signature and stapled-ticket verification.

The deployed feed and Markdown notes returned HTTP 200, followed the existing GitHub Pages redirect to `jon-hadley.com`, and matched the newly signed deployment hashes exactly.
Feed, notes and downloaded archive Ed25519 signatures passed with the original key.
The feed contains exactly one alpha-channel build 2 entry, minimum macOS 27.0, correct public URL/length and no delta updates.

A native manual Check for Updates in the installed `/Applications/WTHz-D.app` build 2 displayed: "You're up to date! WTHz-D 0.1.0 is currently the newest version available."
The dialog was inspected visually and dismissed.
Reception remained disconnected; no radio or credential operations were performed.
The development repository remains private.

Companion JSON files contain the exact deployment/download hashes and signature results.
The installer, corresponding source and release manifest were not changed for publication.
