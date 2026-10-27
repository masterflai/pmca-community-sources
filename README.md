# PMCA community sources

A source for [PMCA-RE RELOADED](https://github.com/masterflai/pmca-re-reloaded) that keeps
camera apps installable whose authors have archived their projects.

This repository hosts no apps. Every entry in `pmca-source.yaml` points to the **original
author's own GitHub releases**: the APK you install is the one the author published, signed
by the author. Nothing here is modified or rebuilt.

## Apps

| App | Author | What it does | Project |
|---|---|---|---|
| BetterManual | [obs1dium](https://github.com/obs1dium) | Improved manual shooting, made for the Alpha 5100 | [obs1dium/BetterManual](https://github.com/obs1dium/BetterManual) |
| FocusBracket | [obs1dium](https://github.com/obs1dium) | Proof-of-concept focus bracketing | [obs1dium/FocusBracket](https://github.com/obs1dium/FocusBracket) |

Both apps are MIT-licensed. All credit belongs to their author; read their READMEs for which
cameras they were made for and tested on.

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

Suggestions for other archived or unmaintained apps are welcome as issues.
