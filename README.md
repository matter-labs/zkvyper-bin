# zkvyper-bin

This repository contains current and historical builds of the zkEVM Vyper Compiler. 

[Compiler changelog](https://github.com/matter-labs/era-compiler-vyper/blob/-/CHANGELOG.md)

## Troubleshooting 
- The binary may need to have its executable bit set:
 
```chmod a+x <path to file>```

- On macOS, the binary may need to have its quarantine attribute cleared: 

```xattr -d com.apple.quarantine <path to file>```
