# patch'd [TYPO3](https://typo3.org) extension [`core`](https://github.com/TYPO3/typo3/tree/main/typo3/sysext/core)

This extension provides the TYPO3 API, i.e. the core functionalities, which can be used and extended in any other TYPO3 extension.

## Compatibility

https://github.com/typo3patch/cms-core/blob/249efd29d62cbf8784399636e5887139fb77c82a/composer.json#L18

## Installation

```bash
composer config repo.t3p-core git https://github.com/typo3patch/cms-core
composer req typo3patch/cms-core
```

## Patches

+ [x] ignore `array` @ `substituteMarkerArray [[issue](https://forge.typo3.org/issues/104590)]
