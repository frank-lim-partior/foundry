# Foundry Fork
The primary goal of this fork is to have control over releases of the foundry codebases. At the point of writing, the upstream project does not have an established release strategy nor commit to keeping certain versions of the releases available. I have the need of a stable version to be consumed for months - so it makes sense to fork the repository and control the release artifacts.

Notes:
- The `master` branch of this fork should always represent a particular point in history of the upstream `master` branch. This is so that we can reuse the same tags that they release.

## Syncing `master` from upstream
This can be done by clicking "Sync fork" on the main page of this github repository.

## Downloading Tags
```
git fetch --tags git@github.com:foundry-rs/foundry.git
git push --tags
```
