<div align="center">

  <img src="https://github.com/tapframe/NuvioTV/raw/dev/assets/brand/app_logo_wordmark.png" alt="NuvioTV webOS" width="300" />
  <br />
  <br />

  <p>
    Shared <b>webOS metadata</b> repository for Nuvio TV.
    <br />
    Homebrew metadata • Release distribution
  </p>

  <p>
    ⚠️ <b>Status: BETA</b> — experimental and may be unstable.
  </p>

</div>

## About

**NuvioWebOS** is the shared LG webOS metadata repository for Nuvio TV.

It is not the main application source code. Release IPKs are now built directly from `NuvioMedia/NuvioWeb`, and this repository primarily tracks the Homebrew metadata published in `webosbrew/apps.json` plus shared branding assets.

## Install

- For direct `.ipk` install: download the latest `.ipk` built from `NuvioMedia/NuvioWeb` releases, enable Developer Mode and Key Server by following `https://www.webosbrew.org/devmode`, then install it with `webOS Dev Manager`
- For Homebrew Channel repository install: open `Homebrew Channel`, go to `Settings`, choose `Add repository`, enter `https://raw.githubusercontent.com/NuvioMedia/NuvioWebOS/main/webosbrew/apps.json`, return to the apps list, and install Nuvio TV from there

## For Developers

- Main shared app source and release packaging: `NuvioMedia/NuvioWeb`
- This repo now primarily handles `webosbrew/apps.json` and release-facing metadata for Homebrew Channel distribution
