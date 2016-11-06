# buku-scripts

bash scripts for [buku](https://github.com/jarun/Buku) bookmarks

Tested only on a debian system.

## add

A script for xsel, this add a bookmark to buku and display a notification using notify-send

Requirements:

```bash
apt install xsel libnotify-bin
```

## tag_expired

A script to add a tag on all bookmarks with HTTP status not equal to 200 OK.

Requirements:

```bash
apt install curl
```
