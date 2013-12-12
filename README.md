pac-ls
======

Python script to list the installed packages on your ArchLinux installation

Permissions
===========

```
chmod +x pac-ls
```

Executing
=========

To execute the program you may use the following option arguments:
 - **-xn**: Exclude native packages
 - **-xf**: Exclude foreign packages
 - **-xv**: Exclude versions

Example:

```
./pac-ls -xn
alsi 0.4.5-1 (foreign)
android-sdk r22.3-1 (foreign)
android-sdk-build-tools r19-1 (foreign)
android-sdk-platform-tools r19-1 (foreign)
android-studio 0.3.6-1 (foreign)
btsco 0.5-2 (foreign)
btsync 1.2.73-2 (foreign)
chromium-pepper-flash-stable 2:11.9.900.152-2 (foreign)
google-chrome 31.0.1650.63-1 (foreign)
google-talkplugin 4.9.1.0-1 (foreign)
jdk 7.45-1 (foreign)
lib32-llvm-amdgpu-lib-snapshot 20130403-2 (foreign)
llvm-amdgpu-lib-snapshot 20130403-3 (foreign)
pulseaudio-git v4.0.301.g12b7a60-1 (foreign)
sublime-text-dev 3.3047-1 (foreign)
virtualbox-ext-oracle 4.3.2-1 (foreign)
```
