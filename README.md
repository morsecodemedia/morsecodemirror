# Smart Mirror
[![GitHub license](https://img.shields.io/github/license/morsecodemedia/smart-mirror.svg)](https://github.com/morsecodemedia/smart-mirror/blob/master/LICENSE)
![Github All Releases](https://img.shields.io/github/downloads/morsecodemedia/smart-mirror/total.svg)
![GitHub release](https://img.shields.io/github/release/morsecodemedia/smart-mirror.svg)
[![GitHub issues](https://img.shields.io/github/issues/morsecodemedia/smart-mirror.svg)](https://github.com/morsecodemedia/smart-mirror/issues)
![GitHub pull requests](https://img.shields.io/github/issues-pr/morsecodemedia/smart-mirror.svg)
![GitHub contributors](https://img.shields.io/github/contributors/morsecodemedia/smart-mirror.svg)


This repository is the framework and modules for my own personal smart mirror. Once I get it in a good place, I will set it up to be more flexible and scalable for distribution.

## Build Setup

``` bash
# install dependencies
npm install
# serve with hot reload at localhost:9080
npm run dev
# build electron application for production
npm run build
# lint all JS/Vue component files in `src/`
npm run lint
```

## Features List/Requests
If you would like to vote on a feature or suggest a new feature, click on the list below and add it to FeatHub.

[![Feature Requests](http://feathub.com/morsecodemedia/smart-mirror?format=svg)](http://feathub.com/morsecodemedia/smart-mirror)

## PARTS
- **LED TV**
I ideally don't want to spend a lot of money on something that I'm going to be stripping down. Also size is an issue, I can't go bigger than a 24" and have enough room for the frame and not have it hanging over the sides of the wall.
  - [VIZIO D-Series D24F-F1 - 24" LED Smart TV](https://www.amazon.com/VIZIO-SmartCast-Class-Certified-Refurbished/dp/B078Z1DYD9): $140 refurb
  - [LG 22LJ4540 22in Class Full HD IPS LED TV](https://www.ebay.com/itm/LG-22LJ4540-22in-Class-Full-HD-IPS-LED-TV/172789253991): $119 refurb
- **2-way mirror**
I'm probably going to go with the VanityVision glass from [Two Way Mirrors](https://www.twowaymirrors.com/smart-mirror/). Mostly becuase it just takes the thinking out of this part. *These options are with 1/4" non-tempered glass, and sanded edges.*
  - With the Vizio D24F-F1 24", the glass will cost: $101.60
  - With the LG 22LJ4540 22", the glass will cost: $86.81
- **Touch Overlay**
While TWM offers suggestions for various touch overlays, all the options they recommend don't provide solutions for smaller than 32". I found myself on [Alibaba](https://www.alibaba.com/) getting decent results with a various range of sizes.
- **Camera and Mic**
I'll probably get the [Playstation Eye](https://www.amazon.com/Sony-PlayStation-Camera-Bulk-Packaging-Pc/dp/B0072I2240) and deconstruct it to have it built into the frame of the mirror.
- **Raspberry Pi**
I have a Raspberry Pi 3 Model B already, waiting to get set up.
- **Frame**
I suppose that this will be the hardest part, as I don't have any wood working tools, and I doubt I am going to find a frame that will just work. Luckily, I have some carpenter connections that I might be able to get someone to make a custom frame for this project. I have seen projects where makers have gone to IKEA and gotten a cheap mirror and stripped out the actual mirror and just used the frame, but as mentioned earlier, I am limited on dimensions, so I will probably have a harder time than some finding something prefabbed that fits the bill.
