# Welcome to Sudoerz's Mod[PRIVATE]

# WARN:THIS PROJECT NOW WIP

 Getting Started
---------------
To get started with the ArrowOS sources, you'll need to get
familiar with [Git and Repo](https://source.android.com/setup/build/downloading).

To initialize your local repository, use command:

```bash
repo init -u https://github.com/SudoerzAOSPMod/local_manifests -b 12.1
```

Then sync up:

```bash
repo sync
```

Building the System
-------------------
 Initialize the ROM environment with the envsetup.sh script.

```bash
source build/envsetup.sh
```
Lunch your device after cloning all device sources if needed.
```bash
lunch
```
Start compilation
```bash
mka bacon
```
