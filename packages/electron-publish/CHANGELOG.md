# electron-publish

## 23.0.0-alpha.0

### Major Changes

- [#6556](https://github.com/electron-userland/electron-builder/pull/6556) [`a138a86f`](https://github.com/electron-userland/electron-builder/commit/a138a86fb7b59098f5dac0c0a6b59c034eb9b222) Thanks [@mmaietta](https://github.com/mmaietta)! - Breaking changes
  Removing Bintray support since it was sunset. Ref: https://jfrog.com/blog/into-the-sunset-bintray-jcenter-gocenter-and-chartcenter/
  Fail-fast for windows signature verification failures. Adding `-LiteralPath` to update file path to disregard injected wildcards
  Force strip path separators for backslashes on Windows during update process
  Force authentication for local mac squirrel update server

  Fixes:
  fix(nsis): Adding --INPUTCHARSET to makensis. (#4898 #6232 #6259)

  Adding additional details to error console logging

### Patch Changes

- Updated dependencies [[`a138a86f`](https://github.com/electron-userland/electron-builder/commit/a138a86fb7b59098f5dac0c0a6b59c034eb9b222), [`a138a86f`](https://github.com/electron-userland/electron-builder/commit/a138a86fb7b59098f5dac0c0a6b59c034eb9b222)]:
  - builder-util@23.0.0-alpha.0
  - builder-util-runtime@9.0.0-alpha.0

## 22.14.13

### Patch Changes

- Updated dependencies [[`f7b38698`](https://github.com/electron-userland/electron-builder/commit/f7b386986ec30f7e4cd3e3f68e078a773940a51c)]:
  - builder-util@22.14.13

## 22.14.12

### Patch Changes

- [#6516](https://github.com/electron-userland/electron-builder/pull/6516) [`344bb232`](https://github.com/electron-userland/electron-builder/commit/344bb232d71e608b881a04fc98dca0858e42ddfc) Thanks [@robertpatrick](https://github.com/robertpatrick)! - fix: Explicitly set the protocol to https on the request objects to allow publishing to work from behind a proxy server when the https_proxy environment variable is set.

## 22.14.7

### Patch Changes

- Updated dependencies [[`04a84352`](https://github.com/electron-userland/electron-builder/commit/04a84352b2b3fbb3c54533a8428bfd103df0af21)]:
  - builder-util@22.14.7

## 22.14.6

### Patch Changes

- Updated dependencies [[`66ca625f`](https://github.com/electron-userland/electron-builder/commit/66ca625f892329fd7bedf52fddc6659ec83b7cd3)]:
  - builder-util-runtime@8.9.2
  - builder-util@22.14.6

## 22.14.5

### Patch Changes

- Updated dependencies [[`54ee4e72`](https://github.com/electron-userland/electron-builder/commit/54ee4e72c5db859b9a00104179786567a0e977ff)]:
  - builder-util-runtime@8.9.1
  - builder-util@22.14.5

## 22.14.0

### Minor Changes

- [#6228](https://github.com/electron-userland/electron-builder/pull/6228) [`a9453216`](https://github.com/electron-userland/electron-builder/commit/a94532164709a545c0f6551fdc336dbc5377bda8) Thanks [@mmaietta](https://github.com/mmaietta)! - feat: adding Bitbucket publisher and autoupdater

### Patch Changes

- Updated dependencies [[`a9453216`](https://github.com/electron-userland/electron-builder/commit/a94532164709a545c0f6551fdc336dbc5377bda8)]:
  - builder-util-runtime@8.9.0
  - builder-util@22.14.0

## 22.13.1

### Patch Changes

- Updated dependencies [[`7f933d00`](https://github.com/electron-userland/electron-builder/commit/7f933d0004a0a5f808a2a1c71dca7362cab2728e)]:
  - builder-util-runtime@8.8.1
  - builder-util@22.13.1

## 22.13.0

### Minor Changes

- [#6167](https://github.com/electron-userland/electron-builder/pull/6167) [`f45110cb`](https://github.com/electron-userland/electron-builder/commit/f45110cbf66572d5748d21fc24dc26cabd06f35f) Thanks [@mmaietta](https://github.com/mmaietta)! - feat: Adding Keygen as an official publisher/updater for electron-builder (#6167)

### Patch Changes

- Updated dependencies [[`f45110cb`](https://github.com/electron-userland/electron-builder/commit/f45110cbf66572d5748d21fc24dc26cabd06f35f)]:
  - builder-util@22.13.0
  - builder-util-runtime@8.8.0

## 22.12.1

### Patch Changes

- Updated dependencies [6c945bd5]
  - builder-util@22.12.1

## 22.11.11

### Patch Changes

- a4eae34f: Synchronizing CLI and package.json versions. Updating auto-publish values + changeset generation to be more frictionless
- Updated dependencies [a4eae34f]
  - builder-util@22.11.11
  - builder-util-runtime@8.7.10

## 22.11.10

### Patch Changes

- 878671d0: Updating patch number as many deps were updated as parted of RenovateBot integration
- Updated dependencies [878671d0]
  - builder-util-runtime@8.7.9
  - builder-util@22.11.10

## 22.11.9

### Patch Changes

- 1272afc5: Initial introduction of changset config
- Updated dependencies [1272afc5]
  - builder-util@22.11.9
  - builder-util-runtime@8.7.8
