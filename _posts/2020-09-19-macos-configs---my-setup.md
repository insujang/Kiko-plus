---
layout: post
title: "macOS configs - my setup"
description: "First post! And some configs I like to set up"
date: 2020-09-19
tags: [macOS, configuration]
---

This is a first in an 4(5??)-part series in how I configure my mac & terminal/shell.

This part is a pretty short one, mostly a test first blog post to see how formatting & images look.

---

### Double-tap to drag

The first feature I like to enable is double-tap to drag. This allows dragging a window with the trackpad without having to make a force-click: just double-tap your cursor on the menu bar to lock it there, and then you can drag with a finger anywhere.

![Double-tap 2 drag](/assets/images/doubletap2drag.gif){: .center-image}

Removing the lock is as simple as letting go for about a second, or force-clicking once. Honestly it's a weird habit I picked up & grew comfortable with when using KDE on a previous Arch Linux desktop.

**Settings** -> **Accessibility** -> **Pointer Control** -> **Trackpad Options:**

![Double-tap 2 drag](/assets/images/doubletap2drag.png){: .center-image}

---

### Disabling Command+Q

The `⌘+w` & `⌘+q` shortcuts are too close to each other, and I often quit completely out of applications instead of closing a tab (pretty disastrous when keeping work open in multiple tabs). To remind myself I'm an idiot, I re-bind `⌘+q` to invert the screen's colors:

**Settings** -> **Keyboard** -> **Shortcuts** -> **Accessiblity:**

![Double-tap 2 drag](/assets/images/invertcolors.png){: .center-image}

Idiot-proof? check:

![Double-tap 2 drag](/assets/images/invertcolorscheck.png){: .center-image}

---

### Drag-anywhere

Finally, my favorite feature is one also picked up from a Linux DE: dragging a window from absolutely anywhere. Luckily, macOS provides this as a neat hidden feature - one that [Twitter user @nibroc](https://twitter.com/nibroc/status/963088893758259200) shows how to enable:

![Double-tap 2 drag](/assets/images/nibroc.png){: .center-image}

Enable 'drag anywhere' by running this in your terminal:

```bash
$ defaults write -g NSWindowShouldDragOnGesture -bool true
```

or to disable it:

```bash
$ defaults delete -g NSWindowShouldDragOnGesture
```

& restart your mac to enable it.

![Double-tap 2 drag](/assets/images/draganywhere.gif){: .center-image}

But unlike his tweet, you only need to hold down `⌘+ctrl`, and then click anywhere on a window. It bounces, indicating your cursor has grabbed it; you can even let go of `⌘+ctrl`, and as long as you hold down your cursor, you can continue dragging the window anywhere.

Much more fun than 'hunting' a tiny menubar!!

---

- [wallpaper link](/assets/images/A4D.jpg), because there's always someone who wants it ;)
