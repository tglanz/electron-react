# Electron React

Nothing special, just basic use of the frameworks

This project was initialy created using [electron-forge](https://electronforge.io/) cli with react template, more specificaly the issued command was  
```electron-forge init electron-react --template=react```

## Build and Run

See [package file](./package.json)

## Issues
- packaging is not as expected

## Next additions
- redux - think over state sharing over main/renderer processes and ipc
- testing framework
  - unit tests - mocha
  - component tests - snapshot, rendering (jest, enzyme)
  - e2e - spectron (official wdio wrapper for electron)
- branding - localization, themeing etc...
- simple native bindings

## Maybe
- ipc over rx