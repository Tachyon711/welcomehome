# Welcome Home

> [!IMPORTANT]
> The development for Welcome Home will be left as is for now. I have to focus on my studies, as well as contributing as much as I could on other projects.

Please use [Nord NewTab](https://github.com/raluvy95/nordnewtab) instead, another new tab replacement by [raluvy95](https://github.com/raluvy95). Please also check one of her projects, [Felida Browser](https://github.com/raluvy95/FelidaBrowser).

## Nord NewTab Features

- Clock
- Weather
- Quotes
- Bookmarks
- Minimal and lightweight
- Looks perfectly with [this](https://chrome.google.com/webstore/detail/material-nord/cnfjnjfppmpabbbdeijhimfijipmmanj)
- Works best with Chromium-based browsers

To use Nord NewTab, read the [instructions](https://github.com/Tachyon711/welcomehome#instruction) below and download [here](https://github.com/raluvy95/nordnewtab/archive/refs/tags/2.0.0.zip).

---

## Roadmap
- Adding customization for the bookmarks list. (still studying)
- Adding dark/light mode button. (still studying)
- Submission to AMO (addons.mozilla.org).
- Publish to AMO, Opera Web Store, and Microsoft Edge Add-ons Store.

## Download

> [!NOTE]
> In order to use the extension/add-on properly, please refer to the [instructions](https://github.com/Tachyon711/welcomehome#instruction) below.

- [Chromium packed extension](https://raw.githubusercontent.com/Tachyon711/welcomehome/main/whcv.1.0.0.crx)
- [Chromium unpacked extension](https://raw.githubusercontent.com/Tachyon711/welcomehome/main/welcome_home_chromium_v.1.0.0.zip)
- [Firefox packed extension](https://raw.githubusercontent.com/Tachyon711/welcomehome/main/whfv.1.0.0.xpi)
- [Firefox unpacked extension](https://raw.githubusercontent.com/Tachyon711/welcomehome/main/welcome_home_firefox_v.1.0.0.zip)

**Say hello to Welcome Home!**

This project is built to provide a custom, light, and minimal new tab page extension for browsers, particularly Chromium-based ones.

I built this project to substitute for other existing alternatives. As to why:
- I don't want my new tab page to start connections to load resources. 
- I don't want my new tab page to be heavily decorated.
- Microsoft Edge and Duckduckgo start page is slow, for me.
- A new tab page should be functional, aesthetically pleasing, and light.

## Journey of learning
This project had learning in mind. It had helped me understand some aspects of making extensions/add-ons, how Web Stores work, how Github repo is actually managed properly (I still can't do that), and how semantic versioning is done. I hope that this could somehow help you as well, but it is provided as is.

## Features
- Date
- Simple clock
- Simple bookmarks list
- Dark mode by default. See light mode below.

## Others
- Human-readable code.
- Only 25 KB. That's all.
- Around 15-25 MB memory usage.
- Does not make any connections anywhere.
- With minimalism in mind, design, and code.
- Only deals with the new tab page. Just that.
- Does not collect any data. It just really can't.
- Uses only the local storage to load resources. No CDN, no Google Fonts.

## Screenshots
![Dark theme](https://raw.githubusercontent.com/Tachyon711/welcomehome/main/1.PNG)
![Light theme](https://raw.githubusercontent.com/Tachyon711/welcomehome/main/2.PNG)

## Instruction

### Unpacked

> [!NOTE]
> Installing the unpacked copies would let you be able to interact more to the code of the extension, as well as customize it yourself.

#### Chromium
1. Extract the files in an empty folder.
2. Find your browser's extension settings.
3. Activate the developer mode in the upper right corner.
4. Click load unpacked in the upper left.
5. Select the folder where you extracted the files.

#### Firefox
1. Go to about:debugging.
2. Enable temporary add-on installation.
3. Open the location of the .zip file.

### Packed

#### Chromium
1. Find your browser's extension settings.
2. Activate the developer mode.
3. Drag and drop the .crx file.

#### Firefox

> [!NOTE]
> I am currently planning to submit the .xpi file in AMO (addons.mozilla.org). Upon approval of our submission, this process would be no longer necessary.

1. Go to about:debugging.
2. Enable temporary add-on installation.
3. Open the location of .xpi file.

### How to activate light mode:
1. Locate "lightmode.css"
2. Rename index.css to "dark.css"
3. Rename lightmode.css to "index.css"
4. Reload new tab.

To make changes, open "index.html" or "index.css" using Notepad.
Please feel free to message me.

# Credits

Konpeki事実[^1][^2][^3]
- Code
- [My email](confinedrose@duck.com)

Karen Ying
- Guide
- [Her website](https://blog.karenying.com)

DataBase Center for Life Science (DBCLS)
- Tab icon (svg)
- Licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/legalcode)
- [Source](https://commons.wikimedia.org/wiki/File:202204_Leaf.svg)

Hiroe Mori

Hiromasa Ono

[^1]: @Konpeki事実. All rights reversed.
[^2]: This repository is not copyrighted. That is, with the exception of "leaf.svg" from DBCLS, which is under CC BY 4.0. 
[^3]: Please provide attributions upon distribution. Other than that, please do what you will.
