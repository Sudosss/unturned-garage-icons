# Unturned garage icons

Preview pictures of Unturned vehicles, for use in game server menus.

This repository holds preview pictures only. It contains no mod files: no models, textures, asset bundles,
`.dat` files or any other content taken from a Steam Workshop item.

## Contents

| Path | What it is |
|---|---|
| `icons/<2 chars>/<guid>.png` | One picture per vehicle: 256 x 256 PNG, transparent background. `<guid>` is the vehicle asset GUID as 32 lower-case hex characters, `<2 chars>` is its first two characters. |
| `manifest.txt` | Every GUID that has a picture, one per line, sorted, LF line endings. |

## URLs on GitHub Pages

Picture:

    https://sudosss.github.io/unturned-garage-icons/icons/<2 chars>/<guid>.png

Manifest:

    https://sudosss.github.io/unturned-garage-icons/manifest.txt

Only request a picture whose GUID is listed in the manifest. A GUID that is not listed has no picture and its
URL answers 404.

## Notice

- Every vehicle shown here was made by its Steam Workshop author, who keeps all rights to it.
- This repository is not affiliated with the Workshop authors, Smartly Dressed Games or Valve.
- The pictures are published so that game servers can identify vehicles in their menus.
- If you are an author and want your pictures removed, please
  [open an issue](https://github.com/Sudosss/unturned-garage-icons/issues).
