FUSION ROM !!
=============

Support Fusion rom
------------------
Follow the Fusion rom builds. Please visit and support my efforts

[Fusion Website] (http://forum.xda-developers.com/showthread.php?t=1855963)

[Fusion Downloads] (http://www.xdafileserver.nl/index.php?dir=Samsung/Galaxy%20S%20III/Custom%20ROMS/DragonXS%20Fusion)

[Fusion Facebook] (https://www.facebook.com/DragonXsFusion)


Getting Started
---------------

To get started with building Fusion rom, you'll need to get
familiar with [Git and Repo](http://source.android.com/download/using-repo).

Then to initialize your local repository using the Fusion rom trees, use this command:

    repo init -u git://github.com/FusionSP/fusion_manifest.git -b lp5.0

Then to sync up:

    repo sync

Then to build:

    . build/envsetup.sh

    lunch

    time make fusion
