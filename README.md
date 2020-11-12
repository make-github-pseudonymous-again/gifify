:rainbow: gifify
[![License](https://img.shields.io/github/license/aureooms/gifify.svg?style=flat)](https://raw.githubusercontent.com/aureooms/gifify/main/LICENSE)
[![Build status](https://img.shields.io/travis/aureooms/gifify/main.svg)](https://travis-ci.org/aureooms/gifify/branches)
==

Convert videos to GIFs.

## :school_satchel: Dependencies

  - `bc`
  - `convert`
  - `ffmpeg`
  - `gifsicle`
  - `gifski`
  - `grep`
  - `sed`

## :minidisc: Install [![AUR package](https://img.shields.io/aur/version/gifify)](https://aur.archlinux.org/packages/gifify)

```sh
make DESTDIR=/ PREFIX=/usr install
```

## :woman_astronaut: Usage

```sh
> gifify -i <VIDEO> -o <GIF>
```

## :open_book: Help

Instructions for selecting the video segment, adjusting the framerate, creating
a looping GIF file, among others, can be listed with the help flag.

```sh
> gifify -h
```
