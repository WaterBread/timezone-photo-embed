# timezone-photo-embed

Easily embed the correct timezone into your photos using embedded GPS coordinates.

This tool scans for `GPSLatitude` and `GPSLongitude` tags in a photo's metadata, determines the corresponding timezone, and saves it back to the image.

## Requirements

- `exiftool`: Ensure it's installed and accessible from the command line.

## Installing

Install the tool via pipx;

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
