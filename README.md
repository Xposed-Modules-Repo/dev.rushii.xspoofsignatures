# XSpoofSignatures

Xposed module to spoof package signatures.

Please avoid starring this repository, go star the [original repo](https://github.com/rushiiMachine/XSpoofSignatures) instead!

## Features

- Supports Android >= 1.5 (Cupcake)
- Compatible with the standardized spoofing
  mechanic ([microG](https://github.com/microg/GmsCore/tree/a787b52ccc56b2e197bf38e1229bb4206538cd12/patches))
- Allow any package to spoof their signature through manifest properties
	- Allow bypassing GMS checks
- Spoofing gated behind a permission

## Install

1. Install XSpoofSignatures
2. Enable it in LSPosed
3. Verify that signature spoofing works via [Signature Spoofing Checker](https://f-droid.org/en/packages/lanchon.sigspoof.checker)
4. You can now use apps that require signature spoofing (like microG)

## Usage (developers)

Go to [original repository](https://github.com/rushiiMachine/XSpoofSignatures) for more information