```
$ flatpak-builder --force-clean --user --install-deps-from=flathub --install build-flatpak-`uname -m` net.megapahit.Viewer.json
$ flatpak run net.megapahit.Viewer
$ flatpak build-bundle ~/.local/share/flatpak/repo megapahit.flatpak net.megapahit.Viewer
```
