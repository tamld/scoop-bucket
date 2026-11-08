# scoop-bucket

[Scoop](https://scoop.sh) bucket for [g8s](https://github.com/tamld/g8s) — Zero-Trust Process & Capability Harness for AI Agents.

## Install

```powershell
scoop bucket add tamld https://github.com/tamld/scoop-bucket
scoop install tamld/g8s
```

The manifest ships the prebuilt Windows binaries (amd64 + arm64) from the signed g8s GitHub release; hashes are pulled from the release's own `checksums.txt`. The bucket's update workflow bumps the manifest within an hour of each g8s release.

## Verify

```powershell
g8s version
g8s doctor
```

Source project: https://github.com/tamld/g8s — see its README for the full installation matrix (installers, Linux packages, verification, lifecycle commands).
