# MANIFEST — TTD v3.6.5 Public Skeleton

Canonical file list, frozen at T-2.  
All artifacts are immutable post-freeze; any change requires re-hash + re-sign.

---

## Files (SHA256)

00fb46b7062a4121beb26b7822e1c80960e3e6c03fd6db879611179d9ae4b4f7  AGENT_POLICY.md
ac59d53427c7c9c1b63be02ebc12f6dc0b11afc36b889218fd1808ff92316cc6  EXEC_SUMMARY.md
e64f78198dbff015ad5f294cbc50cdc34454f01f0d8c482a05f9478c628c9346  FAMILY_REGISTRY_PUBLIC.md
48ed44c503b9a78e6d842512675b14eae3f9d5f7bf3ba1b2dd5f58f4437baeff  index.html
0dd2092a34b2bebd311a1c4f37e0f44fc6398f521d5bac5dbe5b6410627ebaff  LICENSE
4133c79c1041db5cc4324865696fc9447f76569071ac7531ea9d952545c0555a  LICENSE_NOTICE.md
46189438ec842e50cd4953ea7c2e71554f200457ae55f8baffc6d216d71570e7  MILESTONES_TIMELINE.md
a9f699c75d25e651efe8c50199f5f9b4fd45b91291e3be7ddffabc1a02c113ca  pubkey.asc
9e2af265e6069398123f9d79d2ca39835637eae224e7e250ddeceb88f9e3e22d  PUBLIC_TOKEN_HEADER.json
5744d75f1ccd068f93def306b50a8cfc4ef2c5df0d9e8bc2f221dc86b9427900  PUBLIC_TOKEN_HEADER.yaml
7385e705b1bb2c71946f7ef1ed9c4c056cd3dbfe75dda348e051f35990364126  README.md
f9010e33ce49ec4e3511184b90b362f6be8ce224928681ec67149ae46b77d43b  RISKS_NOTES.md
71439b2d7d91343aca85a94479f5ca0ed857df92cc986edba3f936be5f0ec4c4  STATE.md
00ce1e356a1957993430607c0cb294876b7d0cb588a243e13b4d24a558f79e04  TECHNICAL_OVERVIEW.md

---

## Signature

- Detached signature: `MANIFEST.sig`
- Algorithm: Ed25519
- Public key: `pubkey.asc`

### Verification
```powershell
# Import key (once)
gpg --import .\pubkey.asc
gpg --fingerprint "Stephen Hope"

# Verify this manifest
gpg --verify MANIFEST.sig MANIFEST.md

# Hash individual files as needed
Get-FileHash .\index.html -Algorithm SHA256

Helix AI Innovations Inc., 17246102 CANADA INC.

