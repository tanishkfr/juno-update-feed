# Juno update feed

This public repository holds only **sanitized, signed release metadata** for the
Juno Windows public beta.

- `latest.juno.json` is the Ed25519-signed manifest the installed app fetches.
- It contains a version, release notes, and the installer file name, byte size
  and SHA-256.
- It never contains a private key, a token, user data, conversation content or
  the installer itself.
- The matching public key is embedded in each Juno build, so mirroring or
  tampering with this file cannot make an untrusted release acceptable.
- Installation remains manual. Juno announces a signed release and opens the
  release page; it never downloads or runs the unsigned installer.

Current metadata: **Juno v0.4.2 Beta — Performance & Polish** (internal build `0.4.2-rc.3`).