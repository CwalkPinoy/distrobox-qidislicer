create distrobox ubuntu:latest in boxbuddy

add this to /etc/apt/sources.list
deb http://security.ubuntu.com/ubuntu jammy-security main
deb http://cz.archive.ubuntu.com/ubuntu jammy main

sudo apt update

sudo apt install libmspack-dev libgstreamerd-3-dev libsecret-1-dev libwebkit2gtk-4.0-dev libosmesa6-dev libssl-dev libcurl4-openssl-dev eglexternalplatform-dev libudev-dev libdbus-1-dev extra-cmake-modules libgtk2.0-dev libglew-dev libudev-dev libdbus-1-dev cmake git texinfo

distrobox-export <appimage>
