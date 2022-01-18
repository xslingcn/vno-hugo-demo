---
layout: post
tags: ["Say Hi", "Vno"]
title: "Hello Vno"
date: 2021-07-19T07:28:27+08:00
math: false
draft: false
---
#### What's this

[Vno Hugo](https://github.com/xslingcn/vno-hugo) is a theme for [Hugo](https://gohugo.io). It is a port of [onevcat](https://onevcat.com)'s [Vno Jekyll](https://github.com/onevcat/vno-jekyll), which is originally developed from [Dale Anthony's Uno](https://github.com/daleanthony/uno).

#### Usage
Inside the folder of your Hugo site run:
```bash
$ git submodule add https://github.com/xslingcn/vno-hugo.git themes/vno-hugo
```
Copy everything in the `exampleSite` folder to the root of your hugo site, then run `hugo serve`. Your site with `Vno Hugo` enabled should be accessible in http://localhost:1313/.

For more information about Hugo, please visit [Hugo's site](https://gohugo.io).

#### Configuration

All configuration could be done in `config.yml`. Everything in the config file should be self-explanatory.

If you want to enable MathJax support, set `math` param in the front matter to `true`.

#### Background image and avatar

You could replace the background and avatar image in `static/images` folder to change them.

#### Sites using Vno

[My blog](https://xsl.sh) is using `Vno Hugo` as well, you could see how it works in real. There are some other sites using the same theme. You can find them below:

| Site Name    | URL                                                |
| ------------ | ---------------------------------------------------|
| Xsling's   | [https://xsl.sh](https://xsl.sh)           |

> If you happen to be using this theme, welcome to [send me a pull request](https://github.com/xslingcn/Vno-Hugo/pulls) to add your site link here. :)
