# Maya Extra Dependencies for Debian / Ubuntu

Libraries required by Maya that can't be pulled from aptitude.

### Install

```bash
git clone https://github.com/mdilena/maya-debian.git
cd maya-debian
sudo apt install ./libffi6_3.2.1-9_amd64.deb ./libpng15_1.5.15-1_amd64.deb ./libxp6_1.0.2-2_amd64.deb
```

### Uninstall

```bash
sudo apt remove libffi6 libpng15 libxp6
```


