# minidlna-portable

Minidlna is great, but it was not working for me on Linux Mint 21. So I compiled from source and released the binary. Might work for Ubuntu 22.04.

## Dependencies for Linux Mint 21: 

```
sudo apt install libid3tag0
```

## Installation

```
sudo -i
crontab -e
```

add this line:

```
@reboot [path-this-folder]/minidlnad -f [path-this-folder]/minidlna.conf
```

Edit minidlna.conf:

```
media_dir=[path-to-your-media-files]
```

## Source

I've got the source code from https://sourceforge.net/projects/minidlna/