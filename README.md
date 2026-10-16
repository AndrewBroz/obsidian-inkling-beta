# Inkling Markup: beta channel

This repository holds **release builds only** for the beta channel of
[Inkling Markup](https://github.com/AndrewBroz/obsidian-inkling). The source, issues and
documentation live in the main repository.

Every stable release is published here too, so when a beta ends you move onto the stable release
automatically.

## Joining the beta

1. In BRAT, remove `AndrewBroz/obsidian-inkling` from the beta plugin list.
2. **Add beta plugin** → `AndrewBroz/obsidian-inkling-beta`.

List only one of the two repositories in BRAT. Both install the same plugin id, and BRAT only ever
updates to a newer version, so with both listed you'd silently stay on whichever build is newest.

## Leaving the beta

Remove `AndrewBroz/obsidian-inkling-beta` from BRAT and add `AndrewBroz/obsidian-inkling` again.
Adding a repository installs its latest release straight away, so this moves you back to the current
stable build, even though it is older than the beta you had.
