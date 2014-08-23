ParanoidAndroid
===============

Getting Started
---------------

To get started with ParanoidAndroid, you'll need to get
familiar with [Git and Repo](http://source.android.com/download/using-repo).

To initialize your local repository using the ParanoidAndroid trees, use a command like this:

    repo init -u git://github.com/Paradox-PA/manifest.git -b kitkat

Then to sync up, use 50g ccache and build falcon:

    repo sync && prebuilts/misc/linux-x86/ccache/ccache -M 50G && . rom-build.sh falcon

For information on how to build, check [Here](https://github.com/AOSPA/manifest)
