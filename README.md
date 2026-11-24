# xuing/scoop-bucket

[![Tests](https://github.com/xuing/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/xuing/scoop-bucket/actions/workflows/ci.yml)

[Scoop](https://scoop.sh) bucket for [ssh-paste](https://github.com/xuing/ssh-please-paste-picture):
paste screenshots into programs that run over SSH.

```powershell
scoop bucket add xuing https://github.com/xuing/scoop-bucket
scoop install xuing/ssh-paste
```

`bucket/ssh-paste.json` is written by the release workflow of
xuing/ssh-please-paste-picture for each release. Do not edit it here; the next
release replaces it. The tests come from
[ScoopInstaller/BucketTemplate](https://github.com/ScoopInstaller/BucketTemplate).
