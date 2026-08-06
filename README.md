# TokenUse release verification artifacts

This repository mirrors public release verification artifacts outside the
`TokenUse/tokenuse` release asset list.

Current layout:

- `v<version>/SHA256SUMS` mirrors the checksum manifest uploaded to the matching
  GitHub release.
- `v<version>/SHA256SUMS.minisig` will be present after the release signing key
  is provisioned and the signing lane is rehearsed.
- `minisign.pub` will be published here after key custody and fingerprint
  approval.

Do not treat a release as cryptographically signed until both `minisign.pub` and
the matching `SHA256SUMS.minisig` file are present.
