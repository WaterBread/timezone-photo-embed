# timezone-photo-embed

Takes a given GPS embedded photo, and adds a timezone (OffsetTime)

## Dependencies

This program uses `exiftool`, and must be installed and discoverable on the shell with the same name.

## Installing

```sh
pipx install timezone-embed
```

## Usage

### Examples

1. Embed timezone for one image;

```sh
timezone-embed ./myimage.png
```


1. Embed timezone for an entire folder;

```sh
timezone-embed ./myfolder/*
```
