FROM atom63/qt-docker:linux-bullseye-x86_64

USER root

RUN apt update && apt full-upgrade -y && apt install -y \
    qt5-default \
    qttools5-dev \
    qtdeclarative5-dev \
    qtbase5-dev \
    libqt5widgets5 \
    libqt5x11extras5-dev \
    libqt5svg5-dev \
    libqt5serialport5-dev \
    qtbase5-private-dev \
    && apt-get -qq clean \
    && rm -rf /var/lib/apt/lists/*

RUN apt update  && apt install -y --no-install-recommends \
    libudev-dev \
    libhidapi-dev \
    libgpiod-dev \
    && apt-get -qq clean \
    && rm -rf /var/lib/apt/lists/*

USER user

    

