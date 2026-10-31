# cws-releases

Update images for one device, Cathy's Weather Station (an ESP32-C5 display).
This repo holds no source code.

Every image here is encrypted and signed before it is published. The device
decrypts each image as it downloads, checks its signature against keys built
into its firmware, and installs it only if its version is newer than any it has
run. A copy taken from this site cannot be read, and a changed or old one will
not install.

Files are served by GitHub Pages at https://rayhennessey.github.io/cws-releases/.
