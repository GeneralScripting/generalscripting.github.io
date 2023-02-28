---
layout: post
title:  "Tailwind CSS Color Assets for XCode"
---

# Tailwind CSS Color Assets for XCode

[Tailwind CSS](https://tailwindcss.com/) is an extremely useful utility-first CSS framework for web applications. One of the many useful features of Tailwind is its comprehensive color palette, which includes 22 colors in 10 shades each (as of v3.2).

To use Tailwind CSS colors in our XCode project you may stumble upon the [TailwindCSS-SwiftUI](https://github.com/joemasilotti/TailwindCSS-SwiftUI) library by [joemasilotti](https://github.com/joemasilotti). However, at the time of writing it was last updated August 2020 and only supports 10 of the 22 colors.

Managing colors in your XCode Assets has several benfits, i.e. conveniently providing different shades for light- and dark mode. It is a pain however, too. You have to create a new color asset for each color and shade, and then manually set the color values. This is especially painful when you have to do it for 220 colors.

So, to safe you the time and effort, here they are - 220 color assets from Tailwind CSS v3.2. Download and extract the zip file, then copy the _Colors_ folder into your XCode Assets (simple drag and drop).

<div style="display:flex;justify-content:center;margin:42px 23px;">
  <a href="/assets/files/TailwindCSS_Colors_XCode.zip" style="display:flex;align-items:center;gap:5px;">
      <img src="/assets/img/download.svg" height="26" />
      <strong>Tailwind CSS XCode Color Assets</strong>
      (ZIP)
  </a>
</div>

<div style="display:flex;flex-direction: column;align-items:center;gap:0px;">
  <p style="margin:0;">Here is how it should look like:</p>
  <img src="/assets/img/tailwind-css-xcode-colors.png" height="160" />
</div>
