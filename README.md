# PMCA community sources

A source for [PMCA-RE RELOADED](https://github.com/masterflai/pmca-re-reloaded) that gathers
camera apps for Sony's PlayMemories Camera Apps platform in one list: actively developed apps
whose authors agreed to be listed, and apps whose authors have archived their projects, so
those stay installable.

This repository hosts no apps. Every entry in `pmca-source.yaml` points to the **author's
official release location** (their GitHub releases or their own server): the APK you install
is the one the author published, signed by the author, and downloaded from the author.
Nothing here is modified or rebuilt.

## Apps

| App | Author | What it does | Project |
|---|---|---|---|
| BetterManual | [obs1dium](https://github.com/obs1dium) | Improved manual shooting, made for the Alpha 5100 | [obs1dium/BetterManual](https://github.com/obs1dium/BetterManual) |
| FocusBracket | [obs1dium](https://github.com/obs1dium) | Proof-of-concept focus bracketing | [obs1dium/FocusBracket](https://github.com/obs1dium/FocusBracket) |
| JPEGCAM | James (jbuch1984) | Film looks straight out of the camera: pick a recipe, the camera saves the finished JPEG | [jpeg.cam](https://jpeg.cam) |
| Recipe Lab | André Domingues ([voxivoid](https://github.com/voxivoid)) | Film simulations and camera looks, stored in the camera | [voxivoid/recipe-lab-sony-pmca](https://github.com/voxivoid/recipe-lab-sony-pmca) |

BetterManual and FocusBracket are MIT-licensed, Recipe Lab is GPL-3.0. Recipe Lab's author
publishes his own source (`voxivoid/recipe-lab-sony-pmca`); the entry here is identical to it,
so if you add both, either row installs the same file from his releases. JPEGCAM is free to use in its Light edition;
the optional Pro license is sold by its author at [jpeg.cam](https://jpeg.cam). It is listed
with its author's permission: the APK is always downloaded from his servers, and the program
installs it only if it is signed with his certificate (`cert_sha256` in the entry), the first
install included. All credit belongs to the authors; read their pages for which cameras the
apps were made for and tested on.

## Use it

In PMCA-RE RELOADED: *Settings → App and plugin sources* → add `masterflai/pmca-community-sources`.
On the command line:

```
pmca-console sources add masterflai/pmca-community-sources
pmca-console apps
```

## For authors

If you are the author of an app listed here and would rather it were not, open an issue or
mention @masterflai, and it will be removed right away. If you publish your own
`pmca-source.yaml` ([format](https://github.com/masterflai/pmca-re-reloaded/blob/main/docs/app-sources.md)),
your entry here will be replaced by a pointer to your source.

Suggestions for other apps are welcome as issues.
