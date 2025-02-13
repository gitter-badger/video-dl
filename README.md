# video-dl

[![PyPI version](https://img.shields.io/pypi/v/video_dl.svg)](https://pypi.org/project/video-dl/)
---

`video-dl` is a naive online video downloader based on [aiohttp](https://docs.aiohttp.org/en/stable/).

## Prerequisites
- [ffmpeg](https://ffmpeg.org/) used to merge picture and sound to a complete video.
- [python](https://www.python.org) 3.7 or above (required by [aiohttp](https://docs.aiohttp.org/en/stable/)).

## Installation
```bash
pip3 install video-dl
```

## Upgrading
```bash
pip3 install --upgrade video-dl
```

## Usage
### download the highest-definition video
> :warning: If there are special symbols in your url, please enclose it with quotation marks. 
```bash
video-dl 'https://www.bilibili.com/video/BV15L411p7M8'
```
> :warning: the `highest` depends my own view, maybe not the one you want.

![Normal Usage](https://github.com/fengdongfa1995/video-dl/raw/main/screenshots/normal_usage.gif)
### download video which definition will be selected manually
```bash
video-dl -i 'https://www.bilibili.com/video/BV15L411p7M8'
```
![Normal Usage](https://github.com/fengdongfa1995/video-dl/raw/main/screenshots/interactive.gif)

### download video to your specific directory
```bash
video-dl -d ~/tmp 'https://www.bilibili.com/video/BV15L411p7M8'
```
![set download directory](https://github.com/fengdongfa1995/video-dl/raw/main/screenshots/directory.gif)

## Help document
```bash
video-dl -h
```

# Supported websites
- [哔哩哔哩 (゜-゜)つロ 干杯~](https://www.bilibili.com/)

# How was this shit created?
- [在B站学习用Python做一个B站爬虫](https://www.bilibili.com/video/BV1nv411T798/)
