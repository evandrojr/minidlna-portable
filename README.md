# minidlna-portable

## Dependencies for Linux Mint 21: 

sudo apt install libid3tag0

## Instalation

Add somenthing like that to your crontab:

```
@reboot [path-this-folder]/minidlnad -f [path-this-folder]/minidlna.conf
```

Edit minidlna.conf:

```
media_dir=[path-to-your-media-files]
```