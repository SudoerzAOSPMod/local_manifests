# Welcome to Sudoerz's Mod[PRIVATE]

Based on [Project Mia](https://github.com/Project-Mia) (also a private project)


# WARN:THIS IS A PRIVATE PROJECT
DO NOT SHARE ANY COMMIT TO PUBLIC WITHOUT AUTHORIZATION

 Getting Started
================
To get started with the Sudoerz's Mod sources, you'll need to get
familiar with [Git and Repo](https://source.android.com/setup/build/downloading).

To initialize your local repository, use command:

```bash
repo init --no-clone-bundle -u https://github.com/SudoerzAOSPMod/local_manifests -b 13
```

Then sync up:

```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune
```

Building the System
================
 Initialize the ROM environment with the envsetup.sh script.

```bash
source build/envsetup.sh
```
Lunch your device after cloning all device sources if needed.
```bash
lunch xxx
```
Start compilation
```bash
mka bacon
```