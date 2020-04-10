# GitCracken
GitKraken utils for non-commercial use

Working on `GNU/Linux` (without `snap`), `Windows` and `macOS`.

Author: KillWolfVlad at [GitKraken-AUR](https://github.com/KillWolfVlad/GitKraken-AUR)

> WARNING! On `macOS` you should patch `GitKraken` only after first launch and full program closing!

## Requirements

- `Node.js` v12 LTS or later
- `yarn`

## Quick start

- `git clone https://github.com/5cr1pt/GitCracken.git`
- `cd GitCracken/GitCracken/`
- `yarn install`
- `yarn build`
- `node dist/bin/gitcracken.js patcher`

## Disable Automatic Update

Add this content to your `hosts` file:

```text
0.0.0.0 release.gitkraken.com
```

Check [GitCracken/README.md](https://github.com/5cr1pt/GitCracken/blob/master/GitCracken/README.md) for more usage information.

test:
git clone https://github.com/5cr1pt/GitCracken.git
cd GitCracken/GitCracken
rm yarn.lock
yarn install
yarn build
# windows gitbash
node dist/bin/gitcracken.js patcher --asar ~/AppData/Local/gitkraken/app-6.5.0/resources/app.asar
# mac 
node dist/bin/gitcracken.js patcher --asar 你的gitkraken的目录/resources/app.asar
