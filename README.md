TeamJB CM Based Manifest
===========

Getting Started
---------------

To get started with TeamJB/CyanogenMod JB build, you'll need to get familiar with Git and Repo.

To initialize your local repository using the TeamJB trees, use a command like this:

    repo init -u git://github.com/TeamJB/android.git -b jellybean

Then to sync up:

    repo sync

After the initial sync sync once more so that the local_manifest.xml will be picked up.

After that you need to get proprietary CM bits:

    ./vendor/cm/get-prebuilts
