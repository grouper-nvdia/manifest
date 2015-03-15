#Grouper-nVidia

## Getting Started

To get started with Grouper-Nvidia, you'll need to get
familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository using the GRUB4Android trees, use a command like this:

    repo init -u git://github.com/grouper-nvidia/manifest.git -b master

Then to sync up:

    repo sync

## Building
Build everything with make. GNU make can handle parallel tasks with a -jN argument, and it's common to use a number of tasks N that's between 1 and 2 times the number of hardware threads on the computer being used for the build. E.g. on a dual-E5520 machine (2 CPUs, 4 cores per CPU, 2 threads per core), the fastest builds are made with commands between make -j16 and make -j3, see [the build repository](https://github.com/grouper-nvidia/build) for more information


## Downloads
Here will appears Download links (generated from the build system: *the latter, the newer*)
