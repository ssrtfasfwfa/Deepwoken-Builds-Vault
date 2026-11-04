# Deepwoken Build Vault — Phone Edition

A mobile-first installable PWA. Serve this folder over HTTPS (or localhost) to enable installation and offline app-shell caching.

## Install
- Android: open the hosted page in Chrome → menu → Install app / Add to Home screen.
- iPhone: open the hosted page in Safari → Share → Add to Home Screen.

## Storage and import
Builds autosave in the browser's local storage on that device. Use **Export backup** and import the JSON file on another device to transfer your library. JSON and CSV imports are supported. Merge keeps existing builds and skips duplicates; Replace swaps the local library.

Keep JSON backups: uninstalling the PWA or clearing browser site data may remove locally stored builds. There is no automatic cloud sync yet.
