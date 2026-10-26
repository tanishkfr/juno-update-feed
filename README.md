# Juno update feed

This public repository holds only **sanitized, signed release metadata** for Juno's private desktop beta.

- latest.juno.json is the Ed25519-signed manifest the installed app fetches.
- It contains a version, release notes, and the installer file name, byte size and SHA-256.
- It never contains a private key, a token, user data, conversation content or the installer itself.
- The Juno source repository and the juno-beta installer distribution repository stay private.

The manifest is signed offline by the owner. The matching public key is embedded in each Juno build, so mirroring or tampering with this file cannot make an untrusted release acceptable.

