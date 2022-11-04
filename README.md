Project Mia
===========

Project Mia is a Mia Institute collaborative project.

Getting started
---------------

To get started with Project Mia, you'll need to get familiar with [Source Control Tools](https://source.android.com/setup/develop).

To initialize your local repository, use this command:
```bash
repo init --no-clone-bundle -u ssh://git@github.com/Project-Mia/android_manifest.git -b takina
```

Then to sync up:
```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune
```
