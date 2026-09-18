# Late Mate releases

Signed builds of [Late Mate](https://github.com/egn88/late-mate), published here
so the app can update itself without a cable.

- `late-mate.apk` is the current build.
- `version.json` is what the app reads to decide whether to download it.

The app checks every couple of hours, over any connection, and Settings has a
button to check straight away. It verifies the SHA-256 and the signing
certificate before offering the update, and Android asks you to confirm every
install. Nothing here installs silently.

Only this repository is public. The source stays private.
