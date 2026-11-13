# ULTRAXAS Scoop Bucket

Scoop bucket for ULTRAXAS software, including the [Xro](https://github.com/ULTRAXAS/xro) CLI.

## Install Xro

```powershell
scoop bucket add ultraxas https://github.com/ULTRAXAS/scoop-bucket
scoop install xro
```

This installs Node.js if it is not already present, then adds the `xro` command (the official Node.js wrapper around the Windows platform binary, x64 and ARM64).

```powershell
xro --version
```

## Updating

```powershell
scoop update xro
```

## Source

- CLI source: https://github.com/ULTRAXAS/xro
- npm package: https://www.npmjs.com/package/@ultraxas/xro
- License: Apache-2.0
