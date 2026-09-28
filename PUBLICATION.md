# Alpha 1 build 2 publication disposition

Frozen application source: `8d0024b1695b68f4e468993f6f6bdf73e7e07707`.
Release manifest SHA-256: `b6236c9cf14b90b635d17077e141d619b9e543174eb1511deabe043897fce525`.
The release tag in this repository identifies distribution metadata; the Corresponding-Source asset supplies the exact application source.

## Completed checks

The final critical SwiftPM/Xcode gate passed 537 core and 134 app tests per run, with zero failures and three explicit optional/separate-invocation skips.
The final signed packaged decoder passed all 16 paced synthetic slots.
Developer ID signing, Apple notarisation, stapling and bundle/load audits passed.
An isolated signed two-build update passed busy deferral, keyboard Stop, explicit Continue, data preservation and receive-off relaunch.
The owner reported passing the local manual checklist on build 2.
The owner confirmed an encrypted and accessible backup of the Sparkle signing key.

## Licence and source review

At the owner's direction, Codex checked the exact release's dependency register, installed notices, retained upstream licences and complete source packet on 28 September 2026.
The project and adapted wfview component use GPL-3.0-only; WSJT-X uses GPL-3.0-or-later, FFTW GPL-2.0-or-later, Qt Core the selected GPL-3.0-only option, Boost BSL-1.0, Sparkle MIT with its complete embedded-component notices, and the build-only Swift Argument Parser Apache-2.0 with its upstream exception.
GeoNames attribution and the full CC BY 4.0 text are installed; source data and the transformation recipe are retained.
The exact verified source packet includes application source, six pinned dependency archives, build instructions and the executable relocation/signing treatment.
It is published beside the binary for recipients to obtain and modify the corresponding source.
No new upstream source modifications or dependencies are introduced by publication.
No missing licence, notice or corresponding-source requirement was identified in this artifact review.

## Owner decisions

Jonathan Hadley accepted the remaining testing risk for the very early alpha and its very limited audience on 28 September 2026.
New exact-artifact clean-install, physical USB and independent-install observations remain unmeasured; they are accepted release-testing risks for this alpha, not passed tests or new hardware evidence.
The owner then instructed proceeding with licence review and publication, and explicitly selected keeping the development repository private with a separate public distribution location.
This approval covers this frozen early-alpha release and its signed feed.
It does not advance the product phase, authorise transmission or establish broader release qualification.

The frozen publication-preflight tool requires every historical test disposition to be marked passed and cannot represent these owner-approved exceptions.
It is not used to fabricate passed observations.
Exact release/source checksums, signatures, code identity, feed validation and licence/source review were performed independently; owner-accepted risk is recorded explicitly below.
