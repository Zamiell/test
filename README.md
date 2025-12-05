# test

This showcases a bug in [`jsonc-eslint-parser`](https://github.com/ota-meshi/jsonc-eslint-parser).

Steps to reproduce:

```sh
git clone git@github.com:Zamiell/test.git
cd test
npm ci
npx tsc eslint.config.mjs --allowJs --noEmit --skipLibCheck
```
