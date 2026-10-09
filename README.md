# PCアシスタント＋ releases

This repository only hosts signed release packages of PCアシスタント＋ for the app's built-in updater.
Each release carries the package ZIP, `update-manifest.json` and its signature `update-manifest.json.sig`.
The app verifies the signature with a public key embedded in the app before installing anything.
