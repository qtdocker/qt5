# Qt-docker-qt5

Repository with multiple docker recipes for C++/Qt projects linked against old standard library and prepared for cross-compilation.

Look at [Base repo](https://github.com/qtdocker/base) for more info.

Qt from distro upstream:
- Debian Buster with Qt 5.11.3
- Debian Bullseye with Qt 5.15.2

### Debian Buster
#### Base arch: x86_64/amd 
#### Target arch:
- native: `docker pull atom63/qt-docker:linux-buster-x86_64-qt5` [![Docker Image CI](https://github.com/qtdocker/qt5/actions/workflows/docker-image-buster-x86_64-qt5.yml/badge.svg)](https://github.com/qtdocker/qt5/actions/workflows/docker-image-buster-x86_64-qt5.yml)
- armv7a/armhf: `docker pull atom63/qt-docker:linux-buster-cross-x86_64-armv7a-qt`  [![Docker Image CI](https://github.com/qtdocker/qt5/actions/workflows/docker-image-cross-buster-x86_64-armv7a-qt5-clang.yml/badge.svg)](https://github.com/qtdocker/qt5/actions/workflows/docker-image-cross-buster-x86_64-armv7a-qt5-clang.yml)

### Debian Bullseye
#### Base arch: x86_64/amd 
#### Target arch:
- native : `docker pull atom63/qt-docker:linux-bullseye-x86_64-qt5` [![Docker Image CI](https://github.com/qtdocker/qt5/actions/workflows/docker-image-bullseye-x86_64-qt5.yml/badge.svg)](https://github.com/qtdocker/qt5/actions/workflows/docker-image-bullseye-x86_64-qt5.yml)
- armv7a/armhf: `docker pull atom63/qt-docker:linux-bullseye-cross-x86_64-armv7a-qt` [![Docker Image CI](https://github.com/qtdocker/qt5/actions/workflows/docker-image-cross-bullseye-x86_64-armv7a-qt5-clang.yml/badge.svg)](https://github.com/qtdocker/qt5/actions/workflows/docker-image-cross-bullseye-x86_64-armv7a-qt5-clang.yml)