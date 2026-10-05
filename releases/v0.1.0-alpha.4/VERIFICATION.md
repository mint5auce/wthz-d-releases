# Alpha 4 build 5 verification

The [Alpha 4 prerelease](https://github.com/mint5auce/wthz-d-releases/releases/tag/v0.1.0-alpha.4) is published with all five immutable assets.
GitHub upload digests match every frozen artifact.
All five anonymous downloads match their SHA-256 digests and lengths, including the complete 922,466,519-byte corresponding-source archive.
The downloaded installer passes its archive Ed25519 signature, Gatekeeper and stapled-ticket validation.
Its read-only mounted app matches the final manifest inventory and passes strict nested signatures, its stapled ticket and Gatekeeper.
The mounted volume is detached after verification.

GitHub Pages successfully builds site commit `d8f3dc46c08baf6bfeb420c41463962df6a2205f`.
Only the appcast and new Alpha 4 notes change.
Previous notes, CNAME, Jekyll configuration and unrelated site content remain unchanged.
The live feed and new notes return HTTP 200 through the existing `jon-hadley.com` redirect and match the prepared bytes exactly.
Both Ed25519 signatures verify with the existing signing identity.
The appcast SHA-256 is `0d940f9701b90656279a392f960331f33ff9d2338d6f98a7c1366776949f629f`.
The hosted-note SHA-256 is `db74126446b05ff2d29300190acedba7e9c0569cf0cef75600aa0f0e3b0b517f`.
The feed contains alpha-channel build 5 followed by unchanged build 4 and build 3 entry content, with the exact verified installer URL/length, macOS 27.0 minimum and no deltas.
Clients on builds 4, 3 and 2 are eligible for build 5.
Prior installers and complete corresponding-source assets remain available.

The complete critical gate passes all 586 core and 209 native tests in both SwiftPM and arm64 Xcode, with documented skips and zero failures.
The final packaged decoder passes all sixteen paced synthetic intervals with identical functional repetitions, zero failures/drops and complete cleanup.
The owner accepts the unperformed exact-build checks in [the publication disposition](PUBLICATION.md#owner-disposition).
Clean-install, physical USB, independent-install, manual accessibility and actual client update installation remain unverified.
The running owner app is untouched.
No product criterion closes, phase advances or transmit authority follows.

Companion JSON records retain anonymous downloads, downloaded-installer checks, Pages deployment and hosted-byte/signature verification.
The [release manifest](https://github.com/mint5auce/wthz-d-releases/releases/download/v0.1.0-alpha.4/release-manifest.json) binds the final artifacts.
