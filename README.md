# Using jx in a snap

The official Jenkins X installation instructions are here : https://jenkins-x.io/getting-started/install/

This snap isn't available in the snapcraft store yet.  I had to use the --classic mode in order for the jx snap to be able to access the host.  I'm new to snap so if there is an easier way to achieve this then I'm happy to listen.

## Build

Visit snapcraft.io and download the tools needed to build a snap.

```
cd build
snapcraft cleanbuild
snap install jx_v1.3.380_amd64.snap --classic --dangerous
snap list
```

## Install

If you are feeling adventurous you can install the pre-built .snap application in this directory. Just clone this repo and run :

```
snap install jx_v1.3.380_amd64.snap --classic --dangerous
```

## Remove

To remove the jx snap run :

```
snap remove jx 
```

Enjoy.
