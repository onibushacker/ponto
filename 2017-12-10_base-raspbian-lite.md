## December 10th 2017
### Fresh install, raspberry pi 3

## 1. Base OS
- RASPBIAN STRETCH LITE
  - [release notes](http://downloads.raspberrypi.org/raspbian/release_notes.txt)
  - [torrent](https://downloads.raspberrypi.org/raspbian_lite_latest.torrent), [zip](https://downloads.raspberrypi.org/raspbian_lite_latest)

## 2. Image burn
- Etcher 1.2.1
  - https://etcher.io/

## 3. Troubleshoot monitor offset problem
- LG Flatron Wide. VGA -> HDMI
- Problem: screen offset to the left
- Solution: disable overscan, or adjust screen overscan left + dimensions
  - edit [config.txt](https://www.raspberrypi.org/documentation/configuration/config-txt/README.md) file on SD card
  - https://www.raspberrypi.org/documentation/configuration/config-txt/video.md
  - https://github.com/onibushacker/ponto/blob/master/rafa.config.txt#L21-L22 e https://github.com/onibushacker/ponto/blob/master/rafa.config.txt#L14

## 4. Change password of user "pi"
```
passwd
```
## 5. Language, timezone, wifi
```
sudo raspi-config
```

