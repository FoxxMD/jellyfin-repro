# @jellyfin/sdk Nodejs Types Issue

## Overview

This repository demonstrates that jellyfin/jellfin-sdk-typescript (`@jellyfin/sdk` npm package) does contain compatible typings for modern nodejs projects.

See [Are The Types Wrong?](https://arethetypeswrong.github.io/?p=%40jellyfin%2Fsdk%400.13.0) for independent verification that type resolution is not correct.

## Usage

With prerequisties:

* Node 24, but Node 18 >= should also work
* Typescript 5.9.3, but 5.5.4 >= should also work
* @jellyfin/sdk 0.13.0

Install project

```shell
npm install
```

Open [`index.ts`](/index.ts) in your IDE and observe that the `Jellyfin` import shows an error:

```
Module '"@jellyfin/sdk"' has no exported member 'Jellyfin'.ts(2305)
```