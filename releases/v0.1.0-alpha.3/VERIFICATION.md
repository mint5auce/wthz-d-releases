# Alpha 3 build 4 verification

The Alpha 3 prerelease is published with all five immutable assets.
Anonymous downloads match every frozen SHA-256 digest and byte length, including the complete 922,463,969-byte corresponding-source archive.
The downloaded DMG passes Gatekeeper and stapled-ticket validation.
Its read-only mounted app matches the complete release-manifest inventory and passes strict nested signatures and app stapled-ticket validation; the volume is detached afterward.
The downloaded archive Ed25519 signature verifies against the signed appcast.

GitHub Pages successfully builds site commit `b651b24fdbf738a142d0925c2012f3ad2ae692e3`.
The live feed and new notes return HTTP 200 through the existing `jon-hadley.com` redirect and match the prepared signed bytes exactly.
Their Ed25519 signatures verify with the unchanged signing identity.
The appcast SHA-256 is `13ee0bd66a5063e8c33d21588274031289d5b3218425ad7dcd7f68de2fbf8b5b`.
The hosted-note SHA-256 is `1685b6e356502b1030ecef5763bc5924b8549a2c7065af6bffe8d30bc9930103`.
The feed contains alpha-channel build 4 followed by unchanged builds 3 and 2, uses the exact verified installer URL/length and macOS 27.0 minimum, and has no deltas.
Existing build-3 clients are eligible for build 4.

The complete critical gate passes 586 core and 208 native tests in both SwiftPM and arm64 Xcode, with zero failures and documented skips.
The final signed packaged decoder passes all sixteen paced synthetic intervals, with identical functional repetitions, zero failures or drops and complete cleanup.
The owner accepts the remaining exact-build clean-install, physical USB and independent-install gaps in [the publication disposition](PUBLICATION.md#owner-disposition).
Actual client update installation and new physical/independent-user evidence remain unperformed.
The installed application, prior releases, old source/notes, site configuration and unrelated content remain unchanged.
No product criterion closes, phase advances or transmit authority follows.

Companion JSON records retain anonymous downloads, downloaded-installer verification, successful Pages deployment and hosted bytes/signatures.
The [release manifest](https://github.com/mint5auce/wthz-d-releases/releases/download/v0.1.0-alpha.3/release-manifest.json) binds the final artifact identities.
