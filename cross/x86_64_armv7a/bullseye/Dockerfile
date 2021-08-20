FROM atom63/qt-docker:linux-bullseye-cross-x86_64-armv7a

USER root

RUN apt update && apt full-upgrade -y && apt install -y --no-install-recommends\
    qttools5-dev:armhf  \
    qtdeclarative5-dev:armhf  \
    qtbase5-dev:armhf  \
    libqt5widgets5:armhf  \
    libqt5x11extras5-dev:armhf  \
    libqt5svg5-dev:armhf  \
    libqt5serialport5-dev:armhf  \
    qtbase5-private-dev:armhf  \
	qtscript5-dev:armhf \
    && apt-get -qq clean \
    && rm -rf /var/lib/apt/lists/*

RUN apt update  && apt install -y --no-install-recommends \
    libudev-dev:armhf \
    libhidapi-dev:armhf \
    libgpiod-dev:armhf \
    && apt-get -qq clean \
    && rm -rf /var/lib/apt/lists/*
    
USER user
