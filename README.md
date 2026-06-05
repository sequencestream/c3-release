# c3

Signed binary distribution for **c3 (Claude Code Center)**.

Source lives in a private repo; every release here is a signed build published from a
trusted machine. Downloads are under [Releases](https://github.com/sequencestream/c3/releases).

## Verify a download

minisign public key (key id `061223695cdd6df5`):

```
untrusted comment: c3 release signing key (minisign)
RWQGEiNpXN1t9VEX2lXZab7nHaR+gfjfPYcCYN6Bxyid5NkuQK/Gme+l
```

Each release ships `minisign.pub`, per-artifact `.sha256`/`.minisig`, and `SHA256SUMS`:

```
minisign -Vm c3-vX.Y.Z-<target>.tar.gz -p minisign.pub
shasum -a 256 -c SHA256SUMS
```
