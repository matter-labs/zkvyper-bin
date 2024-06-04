# ZKsync Vyper compiler binaries

This repository contains current and historical builds of the ZKsync Vyper (`zkvyper`) compiler binaries.

[Compiler changelog](https://github.com/matter-labs/era-compiler-vyper/blob/-/CHANGELOG.md)

## Troubleshooting 

- The binary may need to have its executable bit set:
 
```chmod a+x <path to file>```

- On macOS, the binary may need to have its quarantine attribute cleared: 

```xattr -d com.apple.quarantine <path to file>```
