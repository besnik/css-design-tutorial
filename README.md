# CSS Grid Tutorial

This repository contains tutorial of css grid concepts and collection of various web page layouts using css grid. Please note that CSS Grid is another tool in your toolbox and is not replacing other tools. Use right tool for right job and don't forget to keep it simple! 

# When to use CSS Grid

In general you want to use CSS Grid tool for page *layout* and other tools like flexbox for *aligning* items inside the layout.

CSS Grid allows you to specify layout in 2D (instead of e.g. flexbox that is 1D). This means you don't need extra wrappers, containers and rows to build wanted layout so your html code is simpler and easier to maintain. Simple is good.

Also look after css grid functionality in your favorite css framework (e.g. bootstrap), sooner or later all libraries will transform to use css grid for building layouts. Eventualy you might find more effective to build layouts by yourself and use lightweight css component library for styling buttons, menus, shadows, etc instead of using heavyweight css framework.

# How to use this repository

## Learning CSS Grid basics step by step

If you are new to CSS Grid start with [01-basic-concepts](/01-basic-concepts/).

Open each file in browser and play with code. There is documentation included in the source code including more examples to play with.

Watch live preview on `codepen`:
 - [01-plain-grid.html](https://codepen.io/besnik-the-sasster/pen/rNpyQwQ)
 - [02-columns-px-unit](https://codepen.io/besnik-the-sasster/pen/OJzmdwK)
 - [03-columns-fr-unit](https://codepen.io/besnik-the-sasster/pen/zYpwemP)
 - [04-columns-unequal-sizes](https://codepen.io/besnik-the-sasster/pen/XWVROoe)
 - [05-repeat-colums](https://codepen.io/besnik-the-sasster/pen/MWrmLxm)
 - [06-repeat-columns-multiple](https://codepen.io/besnik-the-sasster/pen/YzYVBMB)
 - [07-rows](https://codepen.io/besnik-the-sasster/pen/PoEmVro)
 - [08-rows-explicit-implicit](https://codepen.io/besnik-the-sasster/pen/jOYmdgV)
 - [09-auto-rows-size](https://codepen.io/besnik-the-sasster/pen/KKZmEPa)
 - [10-auto-rows-full-screen](https://codepen.io/besnik-the-sasster/pen/bGaWZNp)
 - [11-rows-minmax](https://codepen.io/besnik-the-sasster/pen/yLpbwNX)
 - [12-rows-minmax-all-same-size](https://codepen.io/besnik-the-sasster/pen/RwxVdWX)
 - [13-grid-lines-basics](https://codepen.io/besnik-the-sasster/pen/dyJWwEV)
 - [14-grid-lines-continued](https://codepen.io/besnik-the-sasster/pen/xxpdmYV)
 - [15-grid-lines-shorthands](https://codepen.io/besnik-the-sasster/pen/vYpmvbp)
 - [16-gaps-between-cells](https://codepen.io/besnik-the-sasster/pen/rNpmPLM)
 - [17-nested-grid](https://codepen.io/besnik-the-sasster/pen/QWavYrj)
 - [18-overlapping](https://codepen.io/besnik-the-sasster/pen/vYpmPjO)

## Learning CSS Grid layouts

Each directory contains different layouts with multiple examples. In *first* directory you will find tutorial for css grid itself. Just open `html` files in your browser, you don't need a http server to play with examples, it's pure css. Look after extra examples in code that are commented out, try to uncomment and have fun!

## Visual Studio Code setup

In case you're using [Visual Studio Code](https://code.visualstudio.com/) I recommend to use [Live preview](https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server) extension or any of your favorite html preview server. 

In case of Live review right click on the file in the `Explorer` and click `Live Preview:Show Preview`. I recommend to create shortcut `Alt+E` to preview current file inside editor and `Ctrl+Alt+E` to preview in external browser. 

You configure shortcuts using `Ctrl+K+S` and type `Live preview` in search.

# Have a new idea?

Do not hesitate to submit a merge request if you have found an error, better concept or new layout idea.
