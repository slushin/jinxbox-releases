# JinxBox releases

Firmware files for [JinxBox](https://github.com/slushin/jinxbox) LED display boxes. Each box checks
`latest.json` here once a day and offers a newer version on its Box tab. It only installs one when someone
presses **Install**.

- `latest.json`: the newest version, its file, size, MD5 fingerprint and what's new
- `JinxBox-vX.YY.bin`: the firmware files. To install one by hand, use **Install from a file** on the Box tab.

New versions are added with `tools/publish_release.py` in the main repo. Only built firmware goes here: no source code, passwords or settings.
