# Boxxy Flatpak Remote
Flatpak remote for Boxxy since Flathub submission was [closed](https://github.com/flathub/flathub/pull/8235).

## Install
```
curl -O https://miifrommera.github.io/boxxy-flatpak-remote/boxxy.gpg && \
  flatpak remote-add --user --if-not-exists --gpg-import=boxxy.gpg \
  boxxy https://miifrommera.github.io/boxxy-flatpak-remote/repo && \
  flatpak install --user boxxy dev.boxxy.BoxxyTerminal
```
