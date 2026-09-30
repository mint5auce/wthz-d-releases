# Published Alpha 2 build 3 verification

Verified on 30 September 2026 after owner-approved publication.
All five release assets were downloaded anonymously and matched the frozen local hashes, including the complete 922,443,279-byte corresponding-source archive.
The downloaded DMG passed stapled-ticket and Gatekeeper checks as Notarized Developer ID.
Its read-only mounted app matched the complete final manifest inventory and passed strict nested signature and stapled-ticket checks; the volume was detached afterward.

Pages built commit `4b721cf48aa473bd00a2bf90ac24391e795c4ee7` successfully.
The existing feed URL and custom-domain redirect returned HTTP 200 for the feed and new notes, matching their separately retained deployment hashes exactly.
The appcast SHA-256 is `1967cd55ff02c8c938670f636210e2168796f2a6ae9c682ab29e324230d590bf`.
The hosted-note SHA-256 is `54611126dcaad9d5e7c8bef17062d7df8276c3e8ae7ec4d7d81bb20d34fdc596`.
Feed, notes and downloaded DMG Ed25519 signatures verify using the unchanged signing identity.
The appcast retains build 2 and adds alpha-channel build 3 with the exact public archive URL/length, minimum macOS 27.0 and no deltas.
Build 2 is eligible for build 3 by the published feed contract.

An actual native client installation/update was not performed, preserving the owner's running receive session and installed app.
The known critical logbook row-height failure and remaining manual install/physical/accessibility limitations remain disclosed and accepted for this exact limited alpha; they are not passing observations.
The frozen downloadable notes refer to the preceding SwiftPM pass/Xcode-only failure; the GitHub release body and newly signed hosted notes correctly record the final failure in both validation runners.
Original binary/source/manifest/checksum assets remain unchanged, and all Alpha 1 assets, source, notes and feed entry remain available.
The development repository remains private, and no project phase or exit criterion advances.

Companion JSON files retain all download/deployment identities, signature checks and the explicit owner risk disposition.
