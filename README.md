# Figma No-Rainbow-Loader

## 💀 This project is abandoned

> Note: It would be too hypocritical to leave this repository open and active, and it's actually quite ironic to archive it after what I wrote below. Anyway, I'm not going to apologize for anything and I respect myself for creating this piece of art, though I obviously wouldn't do something like that in future for personal reasons. I want to make it clear for anyone coming here in the future: I have a good job and career, this decision is not forced by my desire to get promoted or my move to Europe, I was just a little wrong about myself :) I will remove the extension from stores, but I will leave it here in honor of my work and time.

---

Chrome extension that removes rainbow-colored loading loading bar from Figma.com that appears during Pride month. Only use for theming and learning how to make extensions, no homophobia intended :)))

[Download from Chrome Web Store](https://chrome.google.com/webstore/detail/figma-anti-lgbt/lnecjeoakphagjeoceoapondpmabphgl/) • [Download from Mozilla Addons](https://addons.mozilla.org/ru/firefox/addon/figma-anti-lgbt/) • [Download soruce from GitHub](https://github.com/VityaSchel/figma-no-rainbow-loader/archive/refs/heads/master.zip)

![image](https://user-images.githubusercontent.com/59040542/175054360-9ecad24e-27b6-4703-b3a0-ef9a2eae9f5c.png)

Reuploaded to GitHub and fixed all complaints. Check out previous version of this repo on [Web Archive](https://web.archive.org/web/*/https://github.com/VityaSchel/figma-anti-lgbt).

## Why?

I made this extension in 41 minutes to remove rainbow loading bar because there is no extensions like this in the internet. Bleach my eyes!! *I just don't like multiple colors in loading bars and prefer sigle color, please accept it as is*

I intentionally made it in vanilla js (or css?) without React, Webpack and SCSS to minimize size of packed extension. Currently it's just 28 KB overall and **only 546 bytes without icons**.

## How?

This extension is basically replacing `background` property of loading bars to `#0d99ff`. In order to prevent it from stop working with site updates, classes are selected by prefix, not whole substring.

Confirmed to work on Recent files page, editor and prototype presentation.

## How to use?

- [Download it in Chrome Web Store](https://chrome.google.com/webstore/detail/figma-anti-lgbt/lnecjeoakphagjeoceoapondpmabphgl/), and that's it! No setup needed.

OR

1. Download this repository using "Download as ZIP" button (or clone if you cool enough)
2. Go to Chrome &rarr; Extensions &rarr; Load packed extension
3. Locate figma-anti-lgbt/src directory inside downloaded repository

## ARE u homophobic??

no!! please don't remove this repository again, it is used for educational purposes and has nothing to do with lgbt i promise!!!!
