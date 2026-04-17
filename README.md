# AOSPA #

## Setting up your machine ##

You must be running a 64-bit Linux distribution and must have installed some packages to build AOSPA. Google recommends using [Ubuntu](http://www.ubuntu.com/download/desktop) for
this and provides instructions for setting up the system (with Ubuntu-specific commands) on
[the Android Open Source Project website](https://source.android.com/source/initializing.html#setting-up-a-linux-build-environment).

Once you have set up your machine according to the instructions by Google, return here and carry
on with the rest of the instructions.

## Grabbing the source ##

Init the repo:

```bash
repo init -u https://github.com/aospa-olzhas/manifest -b beryl
```
Sync the repos:

```bash
repo sync
```

## Building ##

For example, munch or alioth

```bash
./rom-build.sh DEVICE_CODENAME
```
