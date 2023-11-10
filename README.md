<p align="center">
    <a href="https://github.com/LeafOS-Project">
    <img src="https://i.imgur.com/G0gNZxg.png"/>
</p>
<h2 align="center">LeafOS experimental</h2>
<h3 align="center">This is purely a testing org and includes personal changes</h3>
<h3 align="center">It might not boot or build, be warned</h3>

Getting started
---------------
To get started with LeafOS experimental, you'll need to get familiar with [Source Control Tools](https://source.android.com/setup/develop).

To initialize your local repository, use this command:
```
repo init -u https://github.com/LeafOS-experimental/android.git -b leaf-2.0
```
Then to sync up:
```
repo sync
```

Building
--------
Initialize the ROM environment with the envsetup.sh script.
```bash
. build/envsetup.sh
```

Fetch official device trees.
```bash
fetch_device {device}
```

To lunch your device after cloning all device sources.
```bash
lunch {device}-{buildtype}
```

Then start building.
```bash
m leaf
```
---
[![Gerrit](https://img.shields.io/badge/LeafOS%20Gerrit-0F9D58?style=flat-square&logo=git&logoWidth=15&logoColor=white)](https://review.leafos.org)
[![Jenkins](https://img.shields.io/badge/LeafOS%20Jenkins-4285F4?style=flat-square&logo=jenkins&logoWidth=15&logoColor=white)](https://ci.leafos.org)
[![Downloads](https://img.shields.io/badge/LeafOS%20Downloads-ff8c00?style=flat-square&logo=cloudways&logoWidth=15&logoColor=white)](https://dl.leafos.org)
[![Forum](https://img.shields.io/badge/LeafOS%20Forum-DB4437?style=flat-square&logo=leaflet&logoWidth=15&logoColor=white)](https://forum.leafos.org)
