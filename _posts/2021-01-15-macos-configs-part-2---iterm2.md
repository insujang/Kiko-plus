---
layout: post
title: "macOS configs part 2 - iTerm2"
description: "Terminal environment configuration"
date: 2021-01-15
tags: [macOS, configuration, iTerm2, colorscheme, Homebrew, fonts]
---

The second part of this series covers a number of things I do to get my terminal environment _just_ right.

---

### Homebrew

<!-- ![homebrew](/assets/images/homebrew-256x256.png){: .center-image} -->

The very first thing I install on a mac is this package manager. We'll be using a lot of it later.

[https://brew.sh](https://brew.sh)

### iTerm2

Arguably the best terminal emulator available on any platform. Download link can be [found here](https://iterm2.com/).

![iTerm2 Screenfetch](/assets/images/iterm2-screenfetch.png){: .center-image}

I set a couple of preferences to get the minimal look with the left vertical tab-bar:

![iTerm2 Minimal Tab Bar](/assets/images/iterm2-minimal-tabbar.png){: .center-image}

### Colorscheme

Next up is the colorscheme. I use [Nord](https://www.nordtheme.com/), a blueish pastel palette of colors that has been ported for a number of applications. This is a really nice colorscheme that I use for any program I can theme - a muted artic-tinted scheme but colorful enough to be easy on the eyes. In this case, I use the [port for iTerm2](https://github.com/arcticicestudio/nord-iterm2).

![iTerm2 Colors](/assets/images/iterm2-colors.png){: .center-image}

The repo has instructions to install the theme: [Getting Started](https://github.com/arcticicestudio/nord-iterm2#getting-started)

Additionally, I make one tweak to the colorscheme - swapping the selection highlight color so it stands out better:

```
RGB Hex Codes:
Selection: #d8dee8
Selected text: #3b4251
```

![iTerm2 Selection Colors](/assets/images/iterm2-selection.png){: .center-image}

before vs. after:

![iTerm2 Selection Before](/assets/images/iterm2-selection-before.png){: .center-image}

![iTerm2 Selection After](/assets/images/iterm2-selection-after.png){: .center-image}

And a preview using a colorized terminal application like htop:

![iTerm2 Colors htop](/assets/images/iterm2-colors-htop.png){: .center-image}

### Font

A really good font is a huge deal for me - it makes a massive difference when visually scrolling through code all day. I prefer monospaced fonts that make it easy to differentiate between similar characters such as `l/1/I` or `O/0`, and additionally have nice ligatures that convert certain character combinations into their logical representation, like -> into an arrow.

The font that has really stood out for me & stood the test of time is [Fira Code Mono](https://github.com/tonsky/FiraCode):

![Fira Code Mono Ligatures](/assets/images/iterm2-fire-code-mono-ligatures.png){: .center-image}

It can be installed through Homebrew with:

```bash
$ brew install --cask font-fira-code
```

To enable it in iTerm2, select it in Profiles and be sure to check the "Use ligatures" option:

![iTerm2 Enable Fira Code Font](/assets/images/iterm2-enable-fira-code.png){: .center-image}

That's it for this part! Coming up will be configuring ZSH, setting a custom CLI prompt, and covering a number of CLI tools that I use to speed up my workflow.
