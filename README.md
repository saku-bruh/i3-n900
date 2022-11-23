# Custom i3wm Config for the Nokia N900 with PmOS

The prebuilt .img should have everything you need started, download latest edge build from [here](https://images.postmarketos.org/bpo/edge/nokia-n900/i3wm/).

The original wiki may also be found [here](https://wiki.postmarketos.org/wiki/Nokia_N900_(nokia-n900)).

## FYI the default sudo password is
```
147147
```

Make sure the testing mirror is in ```/etc/apk/repositories``` by checking with your prefered text editor. (ie. nano,vim,vi)

Your ```repositories``` should look like this.
```
http://mirror.postmarketos.org/postmarketos/master
http://dl-cdn.alpinelinux.org/alpine/edge/main
http://dl-cdn.alpinelinux.org/alpine/edge/community
http://dl-cdn.alpinelinux.org/alpine/edge/testing
```

After you've made sure testing repo has been added run this command:

```
sudo apk update && sudo apk add i3wm-gaps i3blocks git && git clone https://github.com/saku-bruh/i3-n900.git
```

Some good packages to install:
```
acpi
catt
gotop
htop
imagemagick
nano
ncdu
neofetch
netsurf
nmap
oh-my-zsh
pfetch
py3-pip
python3-dev
ranger
thunar
tshark
wal
wavemon
wget
youtube-dl
zsh
``` 