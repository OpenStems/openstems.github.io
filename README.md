# OpenStems Website

This repository hosts the official OpenStems website:

https://openstems.github.io/

OpenStems brings stem control to open-source music players. Choose the right player for your music source, separate stems, then send audio to OBS or your DAW.

## Apps

- **Pear-OpenStems**: OpenStems integrated into Pear for YouTube Music.
- **LXMusic-OpenStems**: OpenStems integrated into LX Music for Chinese music sources.

## Downloads

Installers are published through GitHub Releases:

https://github.com/OpenStems/OpenStems/releases

This repository contains only the static website source. It does not contain the Pear-OpenStems or LXMusic-OpenStems application source code.

## Website Contents

- `index.html`: homepage
- `assets/`: icons, screenshots, and demo video
- `robots.txt`: search crawler rules
- `sitemap.xml`: search indexing sitemap

## Local Preview

Open `index.html` directly in a browser, or run:

```bash
python3 -m http.server 8898
```

Then visit:

```text
http://127.0.0.1:8898/
```
